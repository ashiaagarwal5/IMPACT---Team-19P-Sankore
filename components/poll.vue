<template>
  <div id = "poll">
    <h1 id="pollh">{{ question }}</h1>
    <div>
      <table>
        <tr id="yesno">
          <td id="td1"><button id ="burefl2" @click="selectOption('Yes')">Yes</button></td>
          <td id="td2"><button id ="burefl2" @click="selectOption('No')">No</button></td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script setup>

const question = ref();

import OpenAI from 'openai';

const openai = new OpenAI({ apiKey: 'sk-proj-ibgwvRIRVCXmho6WLVNAT3BlbkFJ7Ug4oQaWoa07vK94zxJe', dangerouslyAllowBrowser: true});

async function main() {
  const completions = await openai.chat.completions.create({
    messages: [{ role: "system", content: "Please generate a poll question about creating a business. It should only be answerable in yes or no." }],//321
    model: "gpt-3.5-turbo",
  });

  question.value = completions.choices[0].message.content;
  console.log(completions.choices[0].message.content)
}

main();
</script>
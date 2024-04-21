<template>
    <div id="page">
      <h1>Reflection Time</h1>
      <p>Describe a situation where you had to innovate under pressure. What was the outcome, and what did you learn about your capacity for innovation?</p>
      <textarea id="tarefl" v-model="answer" placeholder="Your answer..."></textarea>
      <button id = "burefl" @click="saveAnswer">Save</button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        answer: '',
      }
    },
    methods: {
      saveAnswer() {
        localStorage.setItem('answer', this.answer);
      },
    },
    mounted() {
      this.answer = localStorage.getItem('answer') || '';
    }
  }
  </script>  
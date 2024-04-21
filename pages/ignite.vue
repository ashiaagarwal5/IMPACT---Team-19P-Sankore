<script setup>
    import Reflection from '~/pages/reflection.vue'
    import Footer from "../components/layout/footer.vue";
</script>
<template>
    <head>
        <title>Ignite</title>
    </head>
    <div id = "page">
        <h1>I: IGNITE</h1>
        <p>Igniting ideas, innovation, and initial examinations of purpose</p><!--321-->
        <p>Explore the core principles of innovation and strategic planning, understanding their distinct yet complementary roles in driving organizational success and societal impact</p>
        <!--      ---       ----     -->
        <h1>Question:</h1>
    </div>
        <Poll/>
    <div id = "page">
        <div id="resources">
            <a href = "https://www.canva.com/design/DAF9L7CEfRw/lgs7s0_scJgj-9V1bDanow/edit?utm_content=DAF9L7CEfRw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton"><img id="doc" src = "../igov.jpg"></a>
           <!-- <h2>For some inspiration, learn about TechNova Solutions</h2>
            <a href="https://docs.google.com/document/d/1GLOLDslyOu7VnD8hHl35CorxDbqHem1efxgHWlprlI0/edit?usp=sharing"><img id="doc" src = "../technova.jpg"></a>-->
        </div>
        <Reflection />
    </div>
    <Footer />
</template>
  
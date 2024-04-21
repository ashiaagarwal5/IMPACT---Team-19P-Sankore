<script setup>
import Footer from "../components/layout/footer.vue";
import Reflection from "./reflection.vue";
</script>
<template>
    <head>
        <title>Mobilize</title>
    </head>
    <div id="page">
        <h1>M: MOBILIZE</h1>
        <h3>Mobilizing insights through co-creation, seeking broad inputs</h3><!--321-->
        <p>Delve into various forms of innovation, such as disruptive, incremental, radical, and social innovation. They gain insights into the unique characteristics, applications, and potential societal benefits of each form.</p>
        <!--      ---       ----     -->
  
        <div id="resources">
            <a href="https://gamma.app/public/Introduction-to-Innovation-for-Leaders-24beiafqtyw0p1z"><img id="doc" src = "../guidetoinnov.jpeg"></a>
        </div>
        <div id="Reflection">
            <Reflection />
        </div>
    </div>
    <Footer />
</template>
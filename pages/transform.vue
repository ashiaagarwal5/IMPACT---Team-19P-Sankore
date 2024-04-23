<script setup>
import Footer from "../components/layout/footer.vue";
import Reflection from "./reflection.vue";
</script>
<template>
    <head>
        <title>Transform</title>
    </head>
    <div id="page">
        <h1>T: TRANSFORM</h1>
        <p>Transforming systems by institutionalizing improvements, enabling agility</p><!--321-->
        <p>Discover strategies for cultivating an organizational culture that encourages creativity, collaboration, and risk-taking. This step explores methods for building diverse teams, promoting open communication, and fostering an environment conducive to innovative thinking.</p>
        <!--      ---       ----     -->
        <div id="resources">
            <a href="https://docs.google.com/document/d/1GLOLDslyOu7VnD8hHl35CorxDbqHem1efxgHWlprlI0/edit?usp=sharing"><img id="doc" src = "../technova.jpg"></a>
        </div>
        <div id="Reflection">
            <Reflection/>
        </div>
    </div>
    <Footer />
</template>
  
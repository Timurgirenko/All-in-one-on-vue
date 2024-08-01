<script setup>
    import HeaderContent from './components/HeaderContent.vue';
    import MainContent from './components/MainContent.vue';
    import AboutContent from './components/AboutContent.vue';
    import ProgresContent from './components/ProgresContent.vue';
    import ProgramKurs from './components/ProgramKurs.vue';
</script>

<template>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="fonts/Inter-Italic.otf">
    
    <section>
        <HeaderContent />  
    </section>

    <section>
        <MainContent />
    </section>  
        
    <section>
        <AboutContent />
    </section>

    <section>
        <ProgresContent />
    </section>

    <section>
        <ProgramKurs />
    </section>

</template>

<style>
body{
    margin: 0px;
    background: #0F0F0C;
    
}

@font-face {
    font-family: "Kinetica";
    src: url(../src/assets/fonts/Kinetica-Light.otf);
  }

.container {
    max-width: 1440px;
    margin: 0 auto;
    z-index: 99;
}

</style>

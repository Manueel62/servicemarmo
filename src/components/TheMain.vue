<template>
    <div>
        <AboutUs></AboutUs>
        <Services></Services>
        <Project></Project>
    </div>
</template>

<script>
import AboutUs from './AboutUs.vue';
import Project from './Project.vue';
import Services from './Services.vue';

export default {
    components: { AboutUs, Services, Project }
}
</script>
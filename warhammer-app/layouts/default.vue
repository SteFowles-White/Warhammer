<template>
    <div>
        <TheHeader/>
        <Nuxt/>
        <TheFooter/>
    </div>
</template>
<script>
import TheHeader from '../components/layout/TheHeader.vue';
import TheFooter from '../components/layout/TheFooter.vue';
export default {
    components: {
        TheHeader,
        TheFooter
    }
    
}
</script>
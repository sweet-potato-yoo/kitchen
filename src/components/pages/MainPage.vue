<template>
    <div class="main">
        <HeaderComponent />
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import HeaderComponent from '../HeaderComponent.vue';
export default defineComponent({
    components: {
        HeaderComponent
    }
})
</script>
<style lang="scss" scoped>
    
</style>
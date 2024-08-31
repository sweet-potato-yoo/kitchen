<template>
    <div class="header">
        <HeaderMenu />
        <MainHeadComponent />
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import HeaderMenu from './HeaderMenu.vue';
import MainHeadComponent from './MainHeadComponent.vue';
export default defineComponent({
    components: {
        HeaderMenu,
        MainHeadComponent
    }
})
</script>
<style lang="scss" scoped>
    .header {
        height: 100vh;
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: #CEC5BE;
        justify-content: center;
    }
</style>
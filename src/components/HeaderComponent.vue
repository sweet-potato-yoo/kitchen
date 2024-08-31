<template>
    <div class="header">
        <HeaderMenu />
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import HeaderMenu from './HeaderMenu.vue';
export default defineComponent({
    components: {
        HeaderMenu
    }
})
</script>
<style lang="scss" scoped>
    .header {
        height: 100vh;
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        background-color: #CEC5BE;
    }
</style>
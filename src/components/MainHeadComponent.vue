<template>
    <div class="head">
        <HeaderTitle />
        <HeaderImage />
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import HeaderTitle from './HeaderTitle.vue';
import HeaderImage from './HeaderImage.vue';
export default defineComponent({
    components: {
        HeaderTitle,
        HeaderImage
    }
})
</script>
<style lang="scss" scoped>
    .head {
        max-width: 1624px;
        width: calc(100% - 176px);
        height: calc(100vh - 120px);
        border: 4px solid #A59D9A;
        border-top: none; 
        display: flex;
        flex-direction: row;
        align-items: center;
        padding: 0px 88px;
    }
</style>
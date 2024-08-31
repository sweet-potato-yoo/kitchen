<template>
    <div class="header-title">
        <div class="header-title-text">Set Out <br /> Life Beautiful <br /> Through Cooking.</div>
        <button class="header-title-button">Shop Out Collection</button>
    </div>
</template>
<script>
import { defineComponent } from 'vue';
export default defineComponent({
    
})
</script>
<style lang="scss" scoped>
    .header-title {
        max-width: 690px;
        width: 100%;
        display: flex;
        flex-direction: column;
        row-gap: 40px;
    }
    .header-title-text {
        font-size: 80px;
        text-align: left;
        font-weight: 600;
        color: #000000;
    }
    .header-title-button {
        max-width: 280px;
        width: 100%;
        height: 80px;
        background-color: #C2B8B2;
        color: #000000;
        border: 1px solid #A59D9A;
        font-size: 16px;
        font-weight: 600;
    }
</style>
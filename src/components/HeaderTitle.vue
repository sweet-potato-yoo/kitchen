<template>
    <div class="header-title">
        <div class="header-title-text">
            <div class="title-row">Set Out</div>
            <div class="title-row">Life
                <div class="header-title-text-beautiful">
                    Beautiful
                    <img src="../assets/icons/Curve.svg" class="curve" />
                </div>
            </div>
            <div class="title-row">Through Cooking.</div>
        </div>
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
    .title-row {
        display: flex;
        flex-direction: row;
        column-gap: 10px;
    }
    .header-title-text-beautiful {
        height: 102px;
        width: 377px;
        background-color: #000000;
        color: #CEC5BE;
        text-align: center;
        position: relative;
    }
    .curve {
        position: absolute;
        bottom: -10px;
        left: 80%;
        width: 425px;
    }
</style>
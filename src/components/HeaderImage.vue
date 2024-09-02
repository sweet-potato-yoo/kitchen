<template>
    <div class="header-image">
        <img src="../assets/icons/men-cooking 1.png" class="man-image" />
        <div class="customers-frame">
            <div class="customers">
                <img src="../assets/icons/cust-star.svg" class="customer-star" />
                <div class="customers__text">
                    <p class="customers__title">+708k</p>
                    <p>HAPPY CUSTOMERS</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    
})
</script>
<style lang="scss" scoped>
    .header-image {
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        position: relative;
    }
    .man-image {
        max-width: 660px;
        width: 100%;
        max-height: 675px;
        height: 100%;
    }
    .customers-frame {
        max-width: 467px;
        width: 100%;
        max-height: 224px;
        height: 100%;
        border: 4px solid #CEC5BE;
        position: absolute;
        display: flex;
        justify-content: center;
        align-items: center;
        top: 62%;
        left: 0px;
    }
    .customers {
        background-color: #1D1D1B;
        color: #CEC5BE;
        max-width: 367px;
        width: 100%;
        max-height: 150px;
        height: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        column-gap: 26px;
    }
    .customer-star {
        width: 80px;
        height: 80px;
    }
    .customers__text {
        display: flex;
        flex-direction: column;
        text-align: left;
        font-size: 20px;
        font-weight: 600;
        p {
            margin: 0;
            padding: 0;
        }
    }
    .customers__title {
        font-size: 32px;
    }
</style>
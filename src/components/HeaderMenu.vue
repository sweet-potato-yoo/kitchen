<template>
    <div class="menu">
        <img src="../assets/icons/logo.svg" class="menu-logo" />
        <div class="menu-links">
            <a href="/appliances" class="menu-links-link">Appliances</a>
            <a href="/cookware" class="menu-links-link">Cookware</a>
            <a href="/cooksTools" class="menu-links-link">Cook's tools</a>
            <a href="/recipes" class="menu-links-link">Recipes</a>
        </div>
        <div class="menu-sign">
            <a href="/signIn" class="menu-sign-link">Sign In</a>
            <img src="../assets/icons/line.svg" />
            <img src="../assets/icons/search.svg" class="menu-sign-search" />
        </div>
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'HeaderMenu'
})
</script>
<style lang="scss" scoped>
    .menu {
        background-color: #C3B9B0;
        border-bottom: 4px solid #A59D9A;
        color: black;
        padding: 0px 150px;
        height: 120px;
        width: calc(100% - 300px);
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        a {
            text-decoration: none;
            color: #000000;
            font-weight: 600;
        }
    }
    .menu-logo {
        width: 120px;
        height: auto;
        cursor: pointer;
    }
    .menu-links {
        max-width: 535px;
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        font-weight: 400;
    }
    .menu-sign {
        max-width: 100px;
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    .menu-sign-link, .menu-links-link {
        margin: 0;
    }
    .menu-sign-search {
        width: 14px;
        height: 14px;
        cursor: pointer;
    }
</style>
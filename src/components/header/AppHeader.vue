<script>

import AppLogo from './AppLogo.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo
    }
};
</script>

<template>
    <div class="top-page">
        <div class="top-items">
            <div class="white-text targets">
                <a href="#">Donna</a>
                <a href="#">Uomo</a>
                <a href="#">Bambini</a>
            </div>
            <div class="boolean-logo">
                <AppLogo/>
            </div>
            <div class="buttons white-text">
                   <a class="user">U</a>
                   <a class="favourite">H</a>
                   <a class="cart">C</a>
               </div>
        </div>
    </div>
</template>

<style>
.top-page {
    background-color: #FF6900;
}
.top-items {
    display: flex;
    justify-content: space-between;
    max-width: 70%;
    margin: auto;
    padding: 16px 0;
}
.white-text {
    color: white;
}
.buttons {
    display: flex;
    gap: 5px;
}
.boolean-logo img {
    height: 40px;
}
</style>
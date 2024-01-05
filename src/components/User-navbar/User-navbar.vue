<script setup>
import SearchBar from './Search-bar/Search-bar.vue';
</script>

<template>
    <div class="navbar">
        <div>
            <h2>Olá, Visitante!</h2>
        </div>

        <SearchBar />

        <ul class="navbar__user-icons">
            <li class="user-icons-icon">
                <a href="#" class="icon__link">
                    <img src="../../assets/svg/icons/save-outline-icon.svg" class="user-icon user-icon--save" alt="Icone de salvar">
                </a>
            </li>

            <li class="user-icons-icon">
                <a href="#" class="icon__link">
                    <img src="../../assets/svg/icons/doorbell-icon.svg" class="user-icon user-icon--doorbell" alt="Icone de notificação">
                </a>
            </li>

            <li class="user-icons-icon">
                <button class="icon-button icon-button--menu-vertical">
                    <img src="../../assets/svg/icons/menu-vertical-icon.svg" class="user-icon user-icon--menu-vertical" alt="Icone de menu vertical">
                </button>
            </li>
        </ul>
    </div>
</template>

<style lang="scss">
@import '_User-navbar.scss';
</style>
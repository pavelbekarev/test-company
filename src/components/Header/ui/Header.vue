<script setup lang="ts">
import Logo from '../../Logo';

</script>
<template>
    <header class="header">
        <div class="header__content">
            <div class="header__content-item">
                <Logo />
            </div>
            <div class="header__content-item header__content-item--middle">
                <nav class="nav">
                    <ul class="nav__list">
                        <li class="nav__item">
                            <a class="nav__link" href="/">О нас</a>
                        </li>
                        <li class="nav__item">
                            <a class="nav__link" href="/">Услуги</a>
                        </li>
                        <li class="nav__item">
                            <a class="nav__link" href="/">Проекты</a>
                        </li>
                        <li class="nav__item">
                            <a class="nav__link" href="/">Контакты</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="header__content-item header__content-buttons">
                <button class="button">EN</button>
                <button class="button discussButton button--accent">Обсудить</button>
            </div>
        </div>
    </header>
</template>
<style lang="scss">
@import url("../style.scss");
</style>
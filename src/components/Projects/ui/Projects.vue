<script lang="ts" setup>
import { ref } from 'vue';
import type { Project } from '../model/types';
import { defaultProjects } from '../model/defaultProjects';

const projects = ref<Project[]>(defaultProjects)
</script>
<template>
    <section class="projects">
        <div class="projects__content">
            <template v-for="item in projects">
                <div class="projects__item" >
                    <div class="projects__item-left">
                        <h2 class="projects__title">{{ item.title }}</h2>
    
                        <div class="projects__item-info">
                            <div class="projects__advantages">
                                <div class="projects__advantage" v-for="adv in item.advantages">
                                    {{ adv }}
                                </div>
                            </div>
                            <p class="projects__description">
                                {{ item.description }}
                            </p>
                        </div>
                    </div>
                    <div class="projects__item-right">
                        <img :src="item.imgPath" alt="Изображение проекта">
                    </div>
                </div>
                <span class="underline"></span>
            </template>
            <div class="projects__item projects__more">
                <h2 class="projects__title">Все проекты</h2>
                <button class="projects__moreButton">
                    <img src="/src/assets/arrowUp.png" alt="Стрелка вверх">
                </button>
            </div>
            <span class="underline"></span>
        </div>
    </section>
</template>
<style lang="scss">
@import url("../style.scss");
</style>
<script setup lang="ts">
import { ref } from 'vue';
import type { Brand } from '../model/types';
import { defaultBrands } from '../model/defaultBrands';

const brands = ref<Brand[]>(defaultBrands);
</script>
<template>
    <section class="brands">
        <div class="brands__content">
            <div class="brands__item" v-for="item in brands">
                <img class="brands__img" :src="item.path" alt="Логотип бренда">
            </div>
        </div>
    </section>
</template>
<style lang="scss">
@import url("../style.scss");
</style>
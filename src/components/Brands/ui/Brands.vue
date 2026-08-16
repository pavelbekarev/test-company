<script setup lang="ts">
import { ref } from 'vue';

interface Brand {
    id: number;
    path: string;
}

const defaultBrands: Brand[] = [
    {
        id: 1,
        path: "/src/assets/motorika.png"
    },
    {
        id: 2,
        path: "/src/assets/muiz.png"
    },
    {
        id: 3,
        path: "/src/assets/tinkoff.png"
    },
    {
        id: 4,
        path: "/src/assets/tomi-ai.png"
    },
    {
        id: 5,
        path: "/src/assets/energotek.png"
    },
    {
        id: 6,
        path: "/src/assets/Genezis.png"
    },
    {
        id: 7,
        path: "/src/assets/PolarBear.png"
    },
    {
        id: 8,
        path: "/src/assets/Ykigassen.png"
    },
]

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
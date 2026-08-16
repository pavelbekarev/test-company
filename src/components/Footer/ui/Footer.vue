<script setup lang="ts"></script>
<template>
    <footer class="footer">
        <div class="footer__content">
            <div class="footer__item">
                <div class="footer__top">
                    <h3 class="footer__subtitle">01 // Подробнее</h3>
                    <img src="/src/assets/dot.png" alt="Иконка точки">
                </div>
                <div class="footer__bottom">
                    <h2 class="footer__title">Создаем дизайн
                        для сильных брендов</h2>
                </div>
            </div>
            <div class="footer__item">
                <div class="footer__top">
                    <h3 class="footer__subtitle">02 // Услуги</h3>
                    <img src="/src/assets/square.png" alt="Иконка квадрата">
                </div>
                <div class="footer__bottom">
                    <div class="services">
                        <div class="services__item">
                            <h3 class="services__title">Дизайн</h3>
                            <ul class="services__list">
                                <li class="services__service">UX/UI</li>
                                <li class="services__service">Фирменный стиль</li>
                                <li class="services__service">Сайты / Приложения</li>
                                <li class="services__service">Графический дизайн</li>
                                <li class="services__service">Инфографика</li>
                                <li class="services__service">3D</li>
                            </ul>
                        </div>
                        <div class="services__item">
                            <h3 class="services__title">Сайты</h3>
                            <ul class="services__list">
                                <li class="services__service">HTML / CSS / JS</li>
                                <li class="services__service">Backend / API</li>
                                <li class="services__service">CMS</li>
                                <li class="services__service">iOS / Android</li>
                            </ul>
                        </div>
                        <div class="services__item">
                            <h3 class="services__title">Копирайтинг</h3>
                            <ul class="services__list">
                                <li class="services__service">SMM</li>
                                <li class="services__service">Сайты</li>
                                <li class="services__service">Ком. предложения</li>
                                <li class="services__service">Презентации</li>
                                <li class="services__service">Нейминг</li>
                                <li class="services__service">SEO тексты</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer__item">
                <div class="footer__top">
                    <h3 class="footer__subtitle">03 // Контакты</h3>
                    <img src="/src/assets/square.png" alt="Иконка квадрата">
                </div>
                <div class="footer__bottom">
                    <div class="footer__info">
                        <div class="footer__socials">
                            <a href="#"><img src="/src/assets/vk.png" alt="Иконка ВКонтакте" /></a>
                            <a href="#"><img src="/src/assets/max.png" alt="Иконка Макс" /></a>
                            <a href="#"><img src="/src/assets/tg.png" alt="Иконка ТГ" /></a>
                        </div>
                        <a href="tel: +7 999 999 99 99" class="footer__infoText footer__infoText--phone">+7 999 999 99 99</a>
                        <a href="mailto: team@TestCompany.ru" class="footer__infoText footer__infoText--email">team@TestCompany.ru</a>
                    </div>
                    <button class="footer__button">
                        <img src="/src/assets/footer__button.png" alt="Картинка кнопки">
                    </button>
                </div>
            </div>
        </div>

        <div class="footer__copyrights">
            <span class="footer__copyright">@ [2026] TestCompany.</span>
            <a class="footer__copyright" href="/">Политика конфиденциальности</a>
            <a class="footer__copyright" href="/">Условия и положения</a>
        </div>
    </footer>
</template>
<style lang="scss">
@import url("../style.scss");
</style>
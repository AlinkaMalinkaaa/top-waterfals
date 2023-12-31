<script>
import AOS from 'aos'
import 'aos/dist/aos.css'

export default {
    mounted(){
        AOS.init();
    }
}

</script>
<template>
    <h2 class=" font-engplot text-[2rem] md:text-[2.6rem] text-center mt-8">Our Tour Package</h2>
    <p class=" font-engplot text-[1.1rem] md:text-[1.3rem] md:mt-[-0.7rem] text-center">Best Tour And Travel Service Just For You</p>
    <div class=" flex justify-center gap-4 flex-wrap w-[80%] mx-auto mt-5">
        <!-- Водопад 1 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-1.jpg" alt="">
            <h3>Ангельский водопад</h3>
            <p>Самый высокий непрерывный водопад в мире, расположенный в национальном парке Канайма в регионе Гран-Сабана Венесуэлы.</p>
        </div>
        <!-- Водопад 2 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-2.jpg" alt="">
            <h3>Водопад Игуасу</h3>
            <p>Один из самых впечатляющих и широких водопадов, расположенный на границе Аргентины и Бразилии.</p>
        </div>
        <!-- Водопад 3 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-3.jpg" alt="">
            <h3>Великий Ниагара</h3>
            <p>Известный водопад на реке Ниагара на границе Канады и США.</p>
        </div>
        <!-- Водопад 4 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-4.jpg" alt="">
            <h3>Водопад Анхель</h3>
            <p>Один из самых высоких водопадов в мире, расположенный в Гренландии.</p>
        </div>
        <!-- Водопад 5 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-5.jpg" alt="">
            <h3>Печорский водопад</h3>
            <p>Крупнейший водопад на реке Печора в России.</p>
        </div>
        <!-- Водопад 6 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-6.jpg" alt="">
            <h3>Хоноко водопад</h3>
            <p>Один из самых известных водопадов в Японии, расположенный в национальном парке Фудзи-Хаконе-Изу.</p>
        </div>
        <!-- Водопад 7 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-7.jpg" alt="">
            <h3>Милфорд Саунд водопад</h3>
            <p>Удивительный водопад в регионе Милфорд Саунд, Новая Зеландия, в окружении красивых фьордов.</p>
        </div>
      <!-- Водопад 8 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-8.jpg" alt="">
            <h3>Кайетуэ водопад</h3>
            <p>Один из самых красивых водопадов в Южной Америке, расположенный в Амазонии, на границе Бразилии и Венесуэлы.</p>
        </div>
        <!-- Водопад 9 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-9.jpg" alt="">
            <h3>Водопад Пхи Пхи Лей</h3>
            <p>Красивый водопад на острове Пхи Пхи Лей в Таиланде, окруженный тропической природой.</p>
        </div>
        <!-- Водопад 10 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-10.jpg" alt="">
            <h3>Водопад Лена</h3>
            <p>Могучий водопад на реке Лена в России, один из крупнейших в Сибири.</p>
        </div>
        <!-- Водопад 11 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-11.jpg" alt="">
            <h3>Ньюпорт водопад</h3>
            <p>Красивый водопад в графстве Керри, Ирландия, окруженный зелеными холмами.</p>
        </div>
        <!-- Водопад 12 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-12.jpg" alt="">
            <h3>Бридальвейл водопад</h3>
            <p>Один из самых известных водопадов в Новой Зеландии, находится на Южном острове.</p>
        </div>
        <!-- Водопад 13 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-13.jpg" alt="">
            <h3>Хунза водопад</h3>
            <p>Красивый водопад в регионе Хунза, Пакистан, окруженный величественными горами.</p>
        </div>
        <!-- Водопад 14 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-14.jpg" alt="">
            <h3>Хюэльген водопад</h3>
            <p>Самый высокий водопад в Швеции, расположенный в Национальном парке Стурен.</p>
        </div>
        <!-- Водопад 15 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-15.jpg" alt="">
            <h3>Виктория водопад</h3>
            <p>Один из самых известных водопадов в мире, расположенный на реке Замбези в Африке.</p>
        </div>
        <!-- Водопад 16 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-16.jpg" alt="">
            <h3>Плитвицкие озера водопады</h3>
            <p>Каскадный комплекс водопадов в национальном парке Плитвицкие озера, Хорватия.</p>
        </div>
        <!-- Водопад 17 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-17.jpg" alt="">
            <h3>Африканский водопад Ливингстона</h3>
            <p>Один из крупнейших водопадов в Африке, на границе Замбии и Зимбабве.</p>
        </div>
        <!-- Водопад 18 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-18.jpg" alt="">
            <h3>Гуллифосс</h3>
            <p>Знаменитый водопад в Исландии, окруженный уникальным ландшафтом.</p>
        </div>
        <!-- Водопад 19 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-19.jpg" alt="">
            <h3>Ниагарский водопад</h3>
            <p>Славный водопад на границе Канады и США, один из семи чудес природы.</p>
        </div>
        <!-- Водопад 20 -->
        <div class="package" data-aos="zoom-in">
            <img src="/images/package-20.jpg" alt="">
            <h3>Анхельский водопад</h3>
            <p>Еще один потрясающий водопад, находящийся в парке Канайма, Венесуэла.</p>
        </div>


    </div>
</template>
<style>
.package {
    @apply bg-slate-200 w-[14rem] h-[17rem];
}
.package img {
    @apply w-full h-[10rem];
}
.package p{
    @apply font-engplot text-[0.8rem] px-1 text-center;
}
.package h3 {
    @apply font-engplot text-center mt-3;
}
</style>
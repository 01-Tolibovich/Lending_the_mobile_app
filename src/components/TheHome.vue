<script setup>
import TheHeader from './TheHeader.vue';
import TheFooter from "./TheFooter.vue";
import TheRates from './TheRates.vue';
</script>

<template>
<div class="relative">
    <TheHeader/>
    <div>
      <main class=" main flex flex-row justify-center">
        <div class="text-white grid grid-cols-1 text-center md:grid-cols-2 md:grid-rows-1 w-full lg:max-w-5xl mx-auto md:mt-28 items-center">
          <div class="md:col-start-2 md:col-end-3 md:row-start-1 md:row-end-2 md:flex md:items-end md:flex-col md:justify-end self-end custom-size">
            <h1 class="text-3xl p-8 lg:hidden">Взгляните на жизнь иначе!</h1>
            <img class="w-full " src="../assets/img/phone.png" alt="">
          </div>
          <div class="p-10 bg-slate-800 md:bg-transparent grid grid-cols-3 justify-items-center gap-10 md:gap-6 items-center md:col-start-1 md:col-start-2 md:row-start-1 md:row-end-2 lg:w-4/5 lg:justify-self-center">
            <h1 class="text-3xl p-8 hidden lg:block col-start-1 col-end-4 text-5xl md:font-extralight p-0">Взгляните на жизнь иначе!</h1>
            <button class="w-full border-4 text-xl rounded-full row-start-1 row-end-2 md:row-start-2 md:row-end-3 col-start-1 col-end-4 self-center p-4"><a href="">Скачать приложение</a></button>
            <a href="#"><img class="row-start-2 row-end-3 md:row-start-3 md:row-end-4" src="../assets/img/apple-logo.svg" alt=""></a>
            <a href="#"><img class="row-start-2 row-end-3 md:row-start-3 md:row-end-4" src="../assets/img/android-logo.svg" alt=""></a>
            <a href="#"><img class="row-start-2 row-end-3 md:row-start-3 md:row-end-4" src="../assets/img/microsoft-logo.svg" alt=""></a>
            <p class="row-start-3 row-end-4 col-start-1 col-end-4 md:row-start-4 md:row-end-5">Доступно для iPhone, iPad, Android, Windows Phone, OS X, Windows 8</p>
          </div>
      </div>
      </main>
      <section class="font-light text-center p-10 text-2xl md:text-4xl lg:text-5xl md:mt-10">
        <h2 class="mb-10">Устали от серости мегаполиса?</h2>
        <h2>Нам есть, что вам предложить!</h2>
      </section>
      <section class="custom-bg text-center px-10 pt-5 md:grid md:grid-cols-2 md:grid-rows-1 gap-x-12 lg:flex">
        <div class="mt-32 md:mt-0 md:col-start-2 md:col-end-3 md:row-start-1 md:row-end-2 md:text-left md:self-center lg:flex lg:text-center max-w-4xl mx-auto lg:text-lg lg:grid grid-cols-3 gap-8">
          <div class="">
            <div class="relative">
              <img class="hidden lg:block mx-auto" src="../assets/img/iphone1.png" alt="">
              <div class="hidden lg:block w-full h-16 absolute bottom-0 custom-background-and-shadow"></div>
            </div>
            <h3 class="text-xl font-bold my-4 lg:text-3xl lg:mt-0">Поднимает настроение</h3>
            <p class="leading-6">Приложение позволит вам победить осеннюю хандру и депрессию буквально в несколько кликов!</p>
            <br>
          </div>
          <div class="">
            <div class="relative">
              <img class="hidden lg:block mx-auto" src="../assets/img/iphone2.png" alt="">
              <div class="hidden lg:block w-full h-16 absolute bottom-0 custom-background-and-shadow"></div>
            </div>
            <h3 class="text-xl font-bold my-4 lg:text-3xl lg:mt-0">Меняет мир вокруг</h3>
            <p class="leading-6">Сделайте снимок и украсьте его смайликом или текстовой подписью, чтобы усилить эффект</p>
            <br>
          </div>
          <div class="">
            <div class="relative">
              <img class="hidden lg:block mx-auto" src="../assets/img/iphone4.png" alt="">
              <div class="hidden lg:block w-full h-16 absolute bottom-0 custom-background-and-shadow"></div>
            </div>
            <h3 class="text-xl font-bold my-4 lg:text-3xl lg:mt-0">Заводит новых друзей</h3>
            <p class="leading-6">Ставьте лайки, комментируйте, делитесь фотографиями с друзьями и заводите новых</p>
          </div>
          <div class="hidden lg:flex col-start-1 col-end-4 row-start-2 row-end-3 items-center mt-5 mb-14 gap-16 text-start">
            <img src="../assets/img/timer.png" alt="">
            <div class="text-lg">
              <h3 class="text-3xl font-bold my-6">Эффект на 24 часа!</h3>
              <p class="my-6">Британские ученые провели исследования и доказали, что положительный эффект от использования приложения длится целые сутки!</p>
              <a class="underline-offset-8 text-red-500 my-6" href="#">Узнать больше об исследовании</a>
            </div>
          </div>
        </div>
        <img class="mx-auto mt-16 md:mt-0 md:col-start-1 md:col-end-2 md:row-start-1 md:row-end-2 self-end md:w-full lg:hidden" src="../assets/img/iphone3.png" alt="">
      </section>
      <div class="hidden md:flex lg:hidden col-start-1 col-end-4 row-start-2 row-end-3 items-center mt-14 mb-14 gap-16 text-start px-10">
            <img src="../assets/img/timer.png" alt="">
            <div class="text-lg">
              <h3 class="text-3xl font-bold my-6">Эффект на 24 часа!</h3>
              <p class="my-6">Британские ученые провели исследования и доказали, что положительный эффект от использования приложения длится целые сутки!</p>
              <a class="underline-offset-8 text-red-500 my-6" href="#">Узнать больше об исследовании</a>
            </div>
          </div>
      <section class="text-center p-10">
        <div class="md:grid max-w-4xl mx-auto md:text-lg">
          <img class="hidden lg:block mx-auto row-start-1 row-end-2 " src="../assets/img/quotes.svg" alt="">
          <h2 class="text-xl font-bold my-5 md:text-2xl">Николай Петров</h2>
          <p class="hidden md:block">25 лет, водитель трамвая</p>
          <div class="flex row-start-2 row-end-3">
            <img src="../assets/img/arrow.svg" alt="">
            <p class="leading-8 md:m-6">«Это приложение перевернуло мой мир и позволило по-новому взглянуть на привычные серые вещи! А еще я познакомился со своей будущей женой в комментариях к выложенной фотографии!»</p>
            <img class="rotate-180" src="../assets/img/arrow.svg" alt="">
          </div>
        </div>
      </section>
      <TheRates/>
      <section class="p-4 mt-20">
        <div class="contacts text-center p-6 grid lg:grid-cols-3 md:grid-cols-2 md:gap-8 max-w-4xl mx-auto">
          <h2 class="text-2xl mb-4 font-light md:text-4xl lg:text-5xl max-w-xl mx-auto lg:col-start-1 lg:col-end-4 md:col-start-1 md:col-end-3 ">Остались вопросы? Свяжитесь с нами!</h2>
          <div class="mb-6 lg:col-start-1 lg:col-end-2 lg:row-start-2 lg:row-end-3">
            <p class="text-lg font-bold">Звоните:</p>
            <a class="text-2xl font-light text-rose-500 " href="tel:+992985223341">+992 985 22 33 41</a>
          </div>
          <div class="mb-6 lg:col-start-3 lg:col-end-4 lg:row-start-2 lg:row-end-3">
            <p class="text-lg font-bold">Пишите:</p>
            <a class="text-2xl font-light text-rose-500" href="mailto:01.tolibovich@gmail.com">01.tolibovich@gmail.com</a>
          </div>
          <div class="mb-6 md:col-start-1 md:col-end-3 lg:col-start-2 lg:col-end-3 lg:row-start-2 lg:row-end-3">
            <p class="text-lg font-bold">Приезжайте в гости:</p>
            <a class="text-2xl font-light text-rose-500" href="">ул. Большая Конюшенная, 19/8</a>
          </div>
        </div>
        <div class="relative custom-z-index">
          <img class="w-full md:hidden" src="../assets/img/map.png" alt="">
          <img class="w-full hidden md:block" src="../assets/img/map2.png" alt="">
          <img class="w-full absolute custom-top left-0" src="../assets/img/triangle white footer.svg" alt="">
        </div>
      </section>
      <TheFooter/>
    </div>
  </div>
</template>
<template>
    <nav class=" absolute w-full flex flex-row justify-center custom-background backdrop-opacity-50">
        <div class="text-white uppercase hidden md:flex justify-between px-8 items-center max-w-6xl w-full">
            <div class="flex justify-between py-5 px-3">
                <img src="../assets/logotype-white-desktop.png" alt="">
            </div>
            <ul class=" text-center flex gap-x-4">
                <li v-for="item in items" :key="item" class=""><a href="#" class="block py-5">{{ item }}</a></li>
            </ul>

        </div>
    </nav>
</template>

<script>
export default {
    name: "fade",
    data() {
        return {
            items: [
                "Главная",
                "Фотографии",
                "Конкурс",
                "html academy"
            ]
        }

    },


}
</script>
<template>
    <nav class="text-white uppercase md:hidden">
            <div class="flex justify-between py-5 px-3 border-b-2 border-black">
                <p class="text-2xl">Pink</p>
                <div class="cursor-pointer">
                    
                    <transition name="btn" mode="out-in">
                        <div v-if="!show" @click="show = !show" key="menu" class="relative"><span class="opacity-0 absolute">menu</span><img class="w-5"  src="../assets/img/hamburger-menu-svgrepo-com.svg" alt=""></div>
                        <div v-else @click="show = !show" key="clear" class="relative"><span class="opacity-0 absolute">clear</span><img class="w-5" src="../assets/img/close-svgrepo-com.svg" alt=""></div>
                    </transition>
                </div>
            </div>
            <transition name="fade">
                <ul class=" text-center " v-if="show">
                <li v-for="item in items" :key="item" class="border-t border-slate-600"><a href="#" class="block py-5 border-b-2 border-black">{{ item }}</a></li>
                </ul>
            </transition>
        
        </nav>
</template>

<script>
    export default {
    name: "fade",
    data() {
        return {
            show: false,
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
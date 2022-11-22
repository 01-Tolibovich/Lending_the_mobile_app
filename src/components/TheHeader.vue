
<template>
    <header class="bg-slate-800" id="app2">
        <TheDesktopMenu/>
        <TheMobileMenu/>
        
    </header>
</template>
<script>
import TheDesktopMenu from './TheDesktopMenu.vue';
import TheMobileMenu from './TheMobileMenu.vue';

export default {
    components: { TheMobileMenu, TheDesktopMenu }
}
</script>
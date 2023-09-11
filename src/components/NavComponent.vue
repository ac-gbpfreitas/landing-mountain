<template>
    <nav>
        <MegaMenu />
        <MobileMenu />
    </nav>
</template>

<script>
import MegaMenu from './menus/MegaMenu.vue';
import MobileMenu from './menus/MobileMenu.vue';

export default {
    name: "NavComponent",
    components: {
        MegaMenu,
        MobileMenu
    }
}
</script>
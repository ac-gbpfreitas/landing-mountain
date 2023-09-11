<template>
    <main>
        <!-- ABOUT SECTION -->
        <AboutComponent />
        <!-- ABOUT SECTION END -->
        <!-- FEATURES SECTION -->
        <FeaturesComponent />
        <!-- FEATURES SECTION END -->
        <!-- SUBSCRIBE SECTION -->
        <SubscribeComponent />
        <!-- SUBSCRIBE SECTION END -->
        <!-- CONTACT SECTION -->
        <ContactComponent />
        <!-- CONTACT SECTION END -->
        <a href="#">
            GO TO TOP
        </a>
    </main>
</template>

<script>
import AboutComponent from './content/AboutComponent.vue';
import FeaturesComponent from './content/FeaturesComponent.vue';
import SubscribeComponent from './content/SubscribeComponent.vue';
import ContactComponent from './content/ContactComponent.vue';

export default {
    name: "MainContent",
    components: {
        AboutComponent,
        FeaturesComponent,
        SubscribeComponent,
        ContactComponent
    }
}

</script>
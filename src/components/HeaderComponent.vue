<template>
    <header>
        <section>
            <NavComponent />
            <article>
                <h1>
                    Hello, Welcome to Mountains
                </h1>
                <p>
                    Mountains is a responsive website. You can use this mobile layout from
                    <a href="#"><span>Website</span>Mo</a>. Please, tell your friends about our website.
                </p>
                <div>
                    <a href="#">login</a>
                    <a href="#">sign up</a>
                </div>
            </article>
        </section>
    </header>
</template>

<script>
import NavComponent from './NavComponent.vue';


export default {
    name: "HeaderComponent",
    components: {
        NavComponent
    }
}
</script>
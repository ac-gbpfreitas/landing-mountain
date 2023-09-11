<template>
    <section class="contact" id="contact">
        <section class="title-section">
            <h2>
                Contact - Lorem ipsum dolor sit
            </h2>
            <h6></h6>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae non ea nesciunt vel! Delectus, provident? Ipsum, <a href="#">dolores</a> by <a href="#">laborum</a>!
            </p>
        </section>
        <form>
            <input type="text" placeholder="Your Name..." name="name">
            <input type="email" placeholder="Your Email..." name="email">
            <input type="text" placeholder="Your Subject..." name="subject">
            <textarea name="message" placeholder="Leave your message..."></textarea>
            <input type="submit" value="send message">
        </form>
    </section>
</template>

<script>
export default {
    name: "ContactComponent"
}
</script>
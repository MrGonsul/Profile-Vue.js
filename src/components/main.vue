<script setup>
import { ref } from 'vue'
const title = ref('Always Learning')
const midtitle = ref('Explore')
const lasttitle = ref('Develop!')

</script>
<template>
    <main>
        <section>
            <h2>
                I'm <span class="highlight">{{ title }}</span>
            </h2>
            <p>
                I'm constantly exploring new concepts in web development, especially Vue.js, JavaScript, HTML, and CSS.
                My goal is to grow into a professional Full-Stack Developer.
            </p>
        </section>
        <section>
            <h2>
                I'm <span class="highlight">{{ midtitle }}</span>
            </h2>
            <p>
                Explore new technologies, tools, and techniques to expand my knowledge and discover better ways to build
                web applications.
            </p>
        </section>
        <section>
            <h2>
                I'm <span class="highlight">{{ lasttitle }}</span>
            </h2>
            <p>
                A simple project built to practice and complete my Vue.js skills.
            </p>
        </section>
    </main>
</template>


<style scoped>
main {
    margin-top: 15px;
}

main section {
    margin-top: 25px;
}

main h2 {
    font-size: 1.3rem;
    color: #34495e;
    margin-bottom: 3px;
}

main p {
    font-size: 0.9rem;
    color: #555;
}
</style>
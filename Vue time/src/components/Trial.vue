<template>
    <h1> My Favourite movie is {{ movie }}</h1>
    <button v-on="functiony"> Caller</button>
    <div class="buttoncaller"></div>
</template>

<script>
import { createElementBlock, h } from 'vue';

export default {
    name: 'Trial',
    data() {

        return {

            movie: 'shrek'
        }
    },
    methods: {
        functiony() {
            return h('div', { class: 'buttoncaller' }, 'Hello brothers');
        }
    }
}

</script>

<style scoped>
h1 {
    font-weight: 500;
    font-size: 2.6rem;
    position: relative;
    top: -10px;
}

h3 {
    font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
    text-align: center;
}

@media (min-width: 1024px) {

    .greetings h1,
    .greetings h3 {
        text-align: left;
    }
}
</style>

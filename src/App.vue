<script setup>
    import HelloWorld from "./components/HelloWorld.vue";
    import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
    <div class="masthead">
        <div class="grid masthead__grid">
            <h1 class="masthead__logo">
                Marcel Moreau
            </h1>
            <div class="masthead__byline">
                Front-end developer in Maine, USA
            </div>
        </div>
    </div>
    <header>
        <div class="wrapper">
            <HelloWorld msg="Marcel, you did it!" />
        </div>
    </header>

    <main>
        <TheWelcome />
    </main>
</template>

<template>
    <section id="hero" class="hero-container flex flex-col items-center gap-4 mt-24 p-2">
        <img class="h-1/5 w-1/5 hover:motion-safe:animate-spin" src="../assets/png/Colada.png" />
        <h1 class="text-5xl font-bold text-orange-400">Colada</h1>
        <h3 class="text-2xl text-center">Time-travel debugging for <span class="text-yellow-500">Pinia</span>, <span class="text-emerald-500">Vue's</span> official state management library</h3>
        <div class="flex justify-between items-center">
            <a class="text-xl border border-orange-400 bg-orange-400 text-slate-900 rounded p-2 transition hover:bg-slate-900 hover:text-orange-400" href="#install">Get Started</a>
        </div>
    </section>
</template>

<script>

    export default {
        name:'HeroContainer'
    }
</script>

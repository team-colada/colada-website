<template>
    <section id="hero" class="hero-container flex flex-col items-center gap-4 mt-24 p-2">
        <img class="lg:w-1/6 lg:h-1/6 h-1/5 w-1/5 hover:motion-safe:animate-spin" src="../assets/png/Colada.png" />
        <h1 class="lg:text-5xl text-4xl font-bold text-orange-400">Colada</h1>
        <h3 class="lg:text-2xl text-xl text-center">Time-travel debugging for <span class="text-yellow-500">Pinia</span>, <span class="text-emerald-500">Vue's</span> official state management library</h3>
        <div class="flex justify-between items-center gap-8">
            <a class="lg:text-xl text-lg border border-orange-400 bg-orange-400 text-slate-900 rounded p-2 transition hover:bg-slate-900 hover:text-orange-400" href="#install">Get Started</a>
            <a class="lg:text-xl text-lg border border-orange-400 bg-slate-900 text-orange-400 rounded p-2 transition hover:bg-orange-400 hover:text-slate-900" href="#screenshots">Screenshots</a>
        </div>
    </section>
</template>

<script>

    export default {
        name:'HeroContainer'
    }
</script>

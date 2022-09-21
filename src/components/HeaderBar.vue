<template>
    <div class="header-bar fixed w-full flex justify-between items-center bg-slate-800 z-10">
        <div class="header-left flex justify-evenly items-center pl-8 gap-4">
            <img src="../assets/png/colada-logo.png" height="64" width="64" class="logo" alt="Colada logo" />
            <a href="#" class="text-xl font-bold text-orange-400 hover:text-orange-300">Colada</a>
            <a href="#features" class="text-lg text-slate-300 hover:text-slate-50">Features</a>
            <a href="#install" class="text-lg text-slate-300 hover:text-slate-50">Installation</a>
            <a href="#contributors" class="text-lg text-slate-300 hover:text-slate-50">Contributors</a>
        </div>
        <div class="header-right flex justify-end items-center pr-8 gap-4">
            <a href="https://www.npmjs.com/package/colada-plugin" target="_blank">
                <span class="rounded-lg border-2 border-slate-800 transition hover:border-orange-500 hover:text-orange-500 p-1 ">npm</span>
            </a>
            <a href="https://google.com/" target="_blank">
                <span class="rounded-lg text-slate-900 border-2 border-emerald-500 bg-emerald-500 transition hover:bg-slate-800 hover:text-emerald-500 p-1 ">Chrome Extension</span>
            </a>
        </div>
    </div>
</template>

<script>

    export default {
        name:'HeaderBar'
    }
</script>


<template>
    <nav class="header-bar fixed w-full flex justify-between items-center bg-slate-800 z-10">
        <div class="header-left  md:flex md:justify-evenly md:items-center md:w-auto hidden pl-8 gap-4">
            <img src="../assets/png/colada-logo.png" height="64" width="64" class="logo" alt="Colada logo" />
            <a href="#" class="text-xl font-bold text-orange-400 hover:text-orange-300">Colada</a>
            <a href="#features" class="text-lg text-slate-300 hover:text-slate-50">Features</a>
            <a href="#install" class="text-lg text-slate-300 hover:text-slate-50">Installation</a>
            <a href="#contributors" class="text-lg text-slate-300 hover:text-slate-50">Contributors</a>
        </div>
        <div class="header-right md:flex md:justify-end md:items-center md:w-auto hidden pr-8 gap-4">
            <a href="https://www.npmjs.com/package/colada-plugin" target="_blank">
                <span class="rounded border border-slate-800 transition hover:border-orange-500 hover:text-orange-500 p-1 ">npm</span>
            </a>
            <a href="https://google.com/" target="_blank">
                <span class="rounded text-slate-200 border border-blue-700 bg-blue-700 transition hover:bg-slate-800 hover:text-blue-500 p-1 ">Chrome Extension</span>
            </a>
        </div>
        <div class="flex justify-between items-center w-full md:hidden">
            <div class="flex justify-center items-center pl-4">
                <img src="../assets/png/colada-logo.png" height="64" width="64" class="logo" alt="Colada logo" />
                <a href="#" class="text-xl font-bold text-orange-400 hover:text-orange-300">Colada</a>
            </div>
            <div id="hamburger-icon" class="p-1 mr-3 border border-slate-800 rounded transition hover:border-slate-400 hover:cursor-pointer active:border-slate-200">
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-list" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"/>
                </svg>
            </div>
        </div>
        <div id="hamburger-menu" class="hidden flex flex-col justify-around items-start gap-2 p-2 transition bg-slate-800 border border-slate-400 rounded absolute right-4 top-12">
            <a href="#features" class="text-md w-full text-slate-300 hover:cursor-pointer hover:text-slate-50">Features</a>
            <a href="#install" class="text-md w-full text-slate-300 hover:cursor-pointer hover:text-slate-50">Installation</a>
            <a href="#contributors" class="text-md w-full text-slate-300 hover:cursor-pointer border-b border-slate-400 hover:text-slate-50">Contributors</a>
            <a href="https://www.npmjs.com/package/colada-plugin" target="_blank">
                <span class="text-md transition hover:cursor-pointer hover:text-orange-500">npm</span>
            </a>
            <a href="https://google.com/" target="_blank">
                <span class="text-md text-blue-500 font-semibold transition hover:cursor-pointer hover:text-blue-400">Chrome Extension</span>
            </a>
        </div>
    </nav>
</template>

<script>

    export default {
        name:'HeaderBar',
        mounted(){
            const hamburgerIcon = document.getElementById('hamburger-icon')
            hamburgerIcon.addEventListener('click', this.toggleMenu)
        },
        methods:{
            toggleMenu(){
                const hamburgerMenu = document.getElementById('hamburger-menu')
                hamburgerMenu.classList.toggle('hidden')
            }
        }
    }
</script>


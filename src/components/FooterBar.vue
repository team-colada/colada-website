<template>
    <div class="footer-bar flex justify-between items-center bg-gray-800">
        <div class="footer-left flex justify-start items-center pl-4 gap-4">
            <h1>FooterBar.vue - License MIT</h1>
        </div>
        <div class="footer-mid flex justify-center items-center gap-4">
            <img src="../assets/png/colada-logo.png" height="64" width="64" class="logo" alt="Github logo" />
            <h1 class="text-xl text-yellow-500">Colada</h1>
            <a href="#features">Features</a>
            <a href="#install">Installation</a>
            <a href="#contributors">Contributors</a>
            
        </div>
        <div class="footer-right flex justify-end items-center pr-4 gap-4">
            <a href="https://github.com/oslabs-beta/colada" target="_blank">
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                    <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                </svg>
            </a>
            <a href="https://www.npmjs.com/package/colada-plugin" target="_blank">
                <span class="p-2 rounded border hover:border-emerald-500">npm</span>
            </a>
            <a href="https://google.com/" target="_blank">
                <span class="rounded p-2 bg-emerald-500 hover:bg-emerald-700">Chrome Extension</span>
            </a>
        </div>
    </div>
</template>

<script>

    export default {
        name:'FooterBar'
    }
</script>

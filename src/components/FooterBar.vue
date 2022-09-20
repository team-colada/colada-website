<template>
    <div class="footer-bar flex justify-between items-center bg-slate-800">
        <div class="footer-left flex justify-center items-center gap-4 pl-8">
            <a href="#" class="animate-bounce text-xl text-emerald-500 p-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-chevron-double-up" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M7.646 2.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1-.708.708L8 3.707 2.354 9.354a.5.5 0 1 1-.708-.708l6-6z"/>
                    <path fill-rule="evenodd" d="M7.646 6.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1-.708.708L8 7.707l-5.646 5.647a.5.5 0 0 1-.708-.708l6-6z"/>
                </svg>
            </a>
            <a href="#features" class="text-slate-500">Features</a>
            <a href="#install" class="text-slate-500">Installation</a>
            <a href="#contributors" class="text-slate-500">Contributors</a>
        </div>
        <div class="footer-right flex justify-start items-center pr-8 gap-4">
            <h1>License MIT</h1>
        </div>
    </div>
</template>

<script>

    export default {
        name:'FooterBar'
    }
</script>

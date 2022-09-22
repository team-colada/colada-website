<template>
    <section id ="install" class="install-container flex flex-col items-center border-b-2 border-slate-800 pt-16 p-8">
        <h3 class="text-3xl text-center font-bold pb-8">Installation</h3>
        <ol class="list-decimal">
            <li class="p-1">Make sure you have the <a class="rounded text-sky-500 transition hover:text-sky-400 active:bg-sky-700 visited:text-purple-600 p-1" href="https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en" target="_blank">Vue.js DevTools extension</a> installed.</li>
            <li class="p-1">
                Install the <a class="rounded text-sky-500 transition hover:text-sky-400 active:bg-sky-700 visited:text-purple-600 p-1" href="https://www.npmjs.com/package/colada-plugin" target="_blank">Colada npm package</a> in your app's root directory.
                <div class="font-mono rounded-lg bg-slate-800 pl-4 mt-2 p-2">
                    <p class="font-mono">npm install colada-plugin --save-dev</p>
                </div>
            </li>
            <li class="p-1">
                Add Colada to your Vue app.
                <div class="font-mono rounded-lg bg-slate-800 pl-4 mt-2 p-2">
                    <p class="font-mono text-slate-500">//main.js</p>
                    <br/>
                    <p><span class="text-red-400">import</span> { createApp } <span class="text-red-400">from</span> <span class="text-sky-300">'vue'</span>;</p>
                    <p><span class="text-red-400">import</span> { createPinia } <span class="text-red-400">from</span> <span class="text-sky-300">'pinia'</span>;</p>
                    <p class="font-mono text-slate-500">// import Colada Plugin</p>
                    <p><span class="text-red-400">import</span> <span class="text-orange-400">Colada</span>, { <span class="text-orange-400">PiniaColadaPlugin</span> } <span class="text-red-400">from</span> <span class="text-sky-300">'colada-plugin'</span>;</p>
                    <p><span class="text-red-400">import</span> App <span class="text-red-400">from</span> <span class="text-sky-300">'./App.vue'</span>;</p>
                    <br/>
                    <p><span class="text-red-400">const</span> app = <span class="text-purple-400">createApp</span>(<span class="text-orange-400">App</span>);</p>
                    <p><span class="text-red-400">const</span> pinia = <span class="text-purple-400">createPinia</span>();</p>
                    <br/>
                    <p>app.<span class="text-purple-400">use</span>(pinia);</p>
                    <p>pinia.<span class="text-purple-400">use</span>(<span class="text-orange-400">PiniaColadaPlugin</span>);</p>
                    <p>app.<span class="text-purple-400">use</span>(<span class="text-orange-400">Colada</span>);</p>
                    <br/>
                    <p>app.<span class="text-purple-400">mount</span>(<span class="text-sky-300">'#app'</span>);</p>
                </div>
            </li>
            <li class="p-1">Download and install the 
                <a class="rounded text-sky-500 transition hover:text-sky-400 active:bg-sky-700 visited:text-purple-600 p-1" href="https://chrome.google.com/webstore/detail/colada-devtools/icdbaobbeemmhlmjolbkedcneadkfpdl" target="_blank">Colada Chrome Extension

                </a>
            </li>
            <li class="p-1">Make sure to enable the extension</li>
        </ol>
    </section>
</template>

<script>

    export default {
        name:'InstallContainer'
    }
</script>

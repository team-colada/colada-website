<template>
    <div id="features" class="features-container flex flex-col items-center  hover:border-2 border-red-500">
        <h3 class="text-3xl text-center font-bold">Core Features</h3>
        <ul class="list-disc">
            <li>Minimal installation and automatic detection of Vue app</li>
            <li>
                Direct integration into Vue.js DevTools, so developers can use Colada without needing to leave their existing devtool configuration.
                <ul>
                    <li>Time travel debugging</li>
                    <li>Inspector panel for viewing your Vue app's Pinia state</li>
                </ul>
            </li>
            <li>
                A Chrome DevTool Extension providing enhanced features, including:
                <ul>
                    <li>Time travel debugging</li>
                    <li>Inspector panel for viewing your Vue app's Pinia state</li>
                </ul>
            </li>
        </ul>
    </div>
</template>

<script>

    export default {
        name:'FeaturesContainer'
    }
</script>

<style scoped>
    .features-container{

    }
</style>

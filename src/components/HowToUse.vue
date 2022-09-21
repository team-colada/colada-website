<template>
    <div id="how-to-use" class="flex flex-col items-center border-b-2 border-slate-800 p-8">
        <h3 class="text-3xl text-center font-bold">How To Use</h3>
        <div class="flex flex-col justify-around max-w-4xl w-5/6 items-start border-2 rounded-lg border-slate-800 bg-slate-800 p-8">
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Using the Colada Vue DevTools <a class="text-orange-400 transition active:text-orange-200 hover:text-orange-300" href="https://www.npmjs.com/package/colada-plugin" target="_blank">Plugin</a></h4>
                <ul class="list-disc">
                    <li>Navigate to the Vue Devtools</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Time Travel Debugging</h4>
                <ul class="list-disc">
                    <li>Select the "Colada" timeline in the timeline view</li>
                    <li>**TURN OFF SCREENSHOTS**</li>
                    <li>Click on events automatically tracked on the timeline to travel through time and update your app's state</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Inspector Panel - View Your Apps State in Real Time!</h4>
                <ul class="list-disc">
                    <li>Select "Colada" in the component menu drop down</li>
                    <li>Click on your Pinia store to view state, actions, and getters, updated in real time</li>
                </ul>
            </div>
        </div>
        <br/>
        <div class="flex flex-col justify-around max-w-4xl w-5/6 items-start border-2 rounded-lg border-slate-800 bg-slate-800 p-8">
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Using the Colada DevTools <a class="text-emerald-500 transition active:text-emerald-300 hover:text-emerald-400" href="" target="_blank" >Extension</a></h4>
                <ul class="list-disc">
                    <li>Navigate to the Colada Devtools</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Time Travel Debugging</h4>
                <ul class="list-disc">
                    <li>Click on the [Timeline Icon]</li>
                    <li>Timeline nodes are automatically generated as store mutations are detected</li>
                    <li>Click on the timestamp to time travel and jump to that state!</li>
                    <li>You can also step through the timeline with the up and down buttons</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Current Node Panel - View Your Apps State in Real Time!</h4>
                <ul class="list-disc">
                    <li>As you time travel, the current state of all the stores is displayed on the right</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>

    export default {
        name:'HowToUse'
    }
</script>

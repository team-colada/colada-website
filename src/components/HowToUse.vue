<template>
    <section id="how-to-use" class="flex flex-col items-center border-b-2 border-slate-800 p-8">
        <h3 class="text-3xl text-center font-bold">How To Use</h3>
        <div class="flex flex-col justify-around max-w-4xl w-5/6 items-start border-2 rounded-lg border-slate-800 bg-slate-800 p-8">
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Using the Colada Vue DevTools <a class="text-orange-400 transition active:text-orange-200 hover:text-orange-300" href="https://www.npmjs.com/package/colada-plugin" target="_blank">Plugin</a></h4>
                <ul class="list-disc pl-8">
                    <li>Navigate to the Vue Devtools.</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Time Travel Debugging</h4>
                <ul class="list-disc pl-8">
                    <li>Select the "Colada" timeline in the timeline view.</li>
                    <li>**TURN OFF SCREENSHOTS**</li>
                    <li>Click on events automatically tracked on the timeline to travel through time and update your app's state.</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Inspector Panel - View Your Apps State in Real Time!</h4>
                <ul class="list-disc pl-8">
                    <li>Select "Colada" in the component menu drop down.</li>
                    <li>Click on your Pinia store to view state, actions, and getters, updated in real time.</li>
                </ul>
            </div>
        </div>
        <br/>
        <div class="flex flex-col justify-around max-w-4xl w-5/6 items-start border-2 rounded-lg border-slate-800 bg-slate-800 p-8">
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Using the Colada DevTools <a class="text-blue-500 transition active:text-blue-300 hover:text-blue-400" href="" target="_blank" >Extension</a></h4>
                <ul class="list-disc pl-8">
                    <li>Navigate to the Colada Devtools</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Time Travel Debugging</h4>
                <ul class="list-disc pl-8">
                    <li>
                        <p class="flex gap-2 justify-start items-center">
                            Click on the
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-clock-history" viewBox="0 0 16 16">
                                <path d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022l-.074.997zm2.004.45a7.003 7.003 0 0 0-.985-.299l.219-.976c.383.086.76.2 1.126.342l-.36.933zm1.37.71a7.01 7.01 0 0 0-.439-.27l.493-.87a8.025 8.025 0 0 1 .979.654l-.615.789a6.996 6.996 0 0 0-.418-.302zm1.834 1.79a6.99 6.99 0 0 0-.653-.796l.724-.69c.27.285.52.59.747.91l-.818.576zm.744 1.352a7.08 7.08 0 0 0-.214-.468l.893-.45a7.976 7.976 0 0 1 .45 1.088l-.95.313a7.023 7.023 0 0 0-.179-.483zm.53 2.507a6.991 6.991 0 0 0-.1-1.025l.985-.17c.067.386.106.778.116 1.17l-1 .025zm-.131 1.538c.033-.17.06-.339.081-.51l.993.123a7.957 7.957 0 0 1-.23 1.155l-.964-.267c.046-.165.086-.332.12-.501zm-.952 2.379c.184-.29.346-.594.486-.908l.914.405c-.16.36-.345.706-.555 1.038l-.845-.535zm-.964 1.205c.122-.122.239-.248.35-.378l.758.653a8.073 8.073 0 0 1-.401.432l-.707-.707z"/>
                                <path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0v1z"/>
                                <path d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5z"/>
                            </svg>
                        </p>
                    </li>
                    <li>Timeline nodes are automatically generated as store mutations are detected</li>
                    <li>Click on the timestamp to time travel and jump to that state!</li>
                    <li>You can also step through the timeline with the up and down buttons</li>
                </ul>
            </div>
            <div class="flex flex-col p-4">
                <h4 class="text-xl font-bold">Current Node Panel - View Your Apps State in Real Time!</h4>
                <ul class="list-disc pl-8">
                    <li>As you time travel, the current state of all the stores is displayed on the right</li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>

    export default {
        name:'HowToUse'
    }
</script>

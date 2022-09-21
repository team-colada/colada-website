<template>
    <section id="demo-project" class="flex flex-col items-center border-b-2 border-slate-800 p-8">
        <h3 class="text-3xl text-center font-bold">Demo Project Setup</h3>
        <div class="flex flex-col justify-around items-start p-8">
            <div class="flex flex-col p-4">
                <ol class="list-decimal flex flex-col justify-between items-start gap-4">
                    <li>Clone this repo.</li>
                    <li>
                        Navigate to the <span class="font-mono rounded-lg bg-gray-700 p-1">demo-project</span> directory.
                        <div class="font-mono rounded-lg bg-slate-800 pl-4 mt-2 p-2">
                            <p class="font-mono">cd demo-project</p>
                        </div>
                    </li>
                    <li>
                        Install packages.
                        <div class="font-mono rounded-lg bg-slate-800 pl-4 mt-2 p-2">
                            <p class="font-mono">npm install</p>
                            <p class="font-mono">npm install ../colada-plugin</p>
                            <p class="font-mono">npm run dev</p>
                        </div>
                    </li>
                </ol>
            </div>
        </div>
    </section>
</template>

<script>

    export default {
        name:'DemoProject'
    }
</script>

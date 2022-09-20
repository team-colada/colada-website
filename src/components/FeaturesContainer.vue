<template>
    <div id="features" class="features-container flex flex-col items-center mt-24 p-8  bg-slate-800">
        <!-- <h3 class="text-3xl text-center font-bold">Core Features</h3>
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
        </ul> -->
    <div class="overflow-hidden">
    <div class="relative mx-auto max-w-7xl py-16 px-4 sm:px-6 lg:px-8">
        <div class="absolute top-0 bottom-0 left-3/4 hidden w-screen bg-slate-600 lg:block"></div>
        <div class="mx-auto max-w-prose text-base lg:grid lg:max-w-none lg:grid-cols-2 lg:gap-8">
        <div>
            <h2 class="text-lg font-semibold text-indigo-600">DevTool</h2>
            <h3 class="mt-2 text-3xl font-bold leading-8 tracking-tight text-slate-200 sm:text-4xl">Features</h3>
        </div>
        </div>
        <div class="mt-8 lg:grid lg:grid-cols-2 lg:gap-8">
        <div class="relative lg:col-start-2 lg:row-start-1">
            <svg class="absolute top-0 right-0 -mt-20 -mr-20 hidden lg:block" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
            <defs>
                <pattern id="de316486-4a29-4312-bdfc-fbce2132a2c1" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                <rect x="0" y="0" width="4" height="4" class="text-slate-200" fill="currentColor" />
                </pattern>
            </defs>
            <rect width="404" height="384" fill="url(#de316486-4a29-4312-bdfc-fbce2132a2c1)" />
            </svg>
            <div class="relative mx-auto max-w-prose text-base lg:max-w-none">
            <figure>
                <div class="aspect-w-12 aspect-h-7 lg:aspect-none">
                <img class="rounded-lg object-cover object-center shadow-lg" src="../assets/png/Colada.png" alt="Screenshot of app GIF" width="1184" height="1376">
                </div>
                <figcaption class="mt-3 flex text-sm text-slate-400">
                <!-- Heroicon name: mini/camera -->
                <svg class="h-5 w-5 flex-none text-slate-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                    <path fill-rule="evenodd" d="M1 8a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 018.07 3h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0016.07 6H17a2 2 0 012 2v7a2 2 0 01-2 2H3a2 2 0 01-2-2V8zm13.5 3a4.5 4.5 0 11-9 0 4.5 4.5 0 019 0zM10 14a3 3 0 100-6 3 3 0 000 6z" clip-rule="evenodd" />
                </svg>
                <span class="ml-2">Photograph by Team Colada</span>
                </figcaption>
            </figure>
            </div>
        </div>
        <div class="mt-8 lg:mt-0">
            <div class="mx-auto max-w-prose text-base lg:max-w-none">
            <p class="text-lg text-slate-300">Sagittis scelerisque nulla cursus in enim consectetur quam. Dictum urna sed consectetur neque tristique pellentesque. Blandit amet, sed aenean erat arcu morbi.</p>
            </div>
            <div class="prose prose-indigo mx-auto mt-5 text-slate-300 lg:col-start-1 lg:row-start-1 lg:max-w-none">
            <p>Sollicitudin tristique eros erat odio sed vitae, consequat turpis elementum. Lorem nibh vel, eget pretium arcu vitae. Eros eu viverra donec ut volutpat donec laoreet quam urna.</p>
            <p>Bibendum eu nulla feugiat justo, elit adipiscing. Ut tristique sit nisi lorem pulvinar. Urna, laoreet fusce nibh leo. Dictum et et et sit. Faucibus sed non gravida lectus dignissim imperdiet a.</p>
            <p>Dictum magnis risus phasellus vitae quam morbi. Quis lorem lorem arcu, metus, egestas netus cursus. In.</p>
            <ul role="list">
                <li>Quis elit egestas venenatis mattis dignissim.</li>
                <li>Cras cras lobortis vitae vivamus ultricies facilisis tempus.</li>
                <li>Orci in sit morbi dignissim metus diam arcu pretium.</li>
            </ul>
            <p>Rhoncus nisl, libero egestas diam fermentum dui. At quis tincidunt vel ultricies. Vulputate aliquet velit faucibus semper. Pellentesque in venenatis vestibulum consectetur nibh id. In id ut tempus egestas. Enim sit aliquam nec, a. Morbi enim fermentum lacus in. Viverra.</p>
            <h3>How we helped</h3>
            <p>Tincidunt integer commodo, cursus etiam aliquam neque, et. Consectetur pretium in volutpat, diam. Montes, magna cursus nulla feugiat dignissim id lobortis amet. Laoreet sem est phasellus eu proin massa, lectus. Diam rutrum posuere donec ultricies non morbi. Mi a platea auctor mi.</p>
            <p>Sagittis scelerisque nulla cursus in enim consectetur quam. Dictum urna sed consectetur neque tristique pellentesque. Blandit amet, sed aenean erat arcu morbi.</p>
            </div>
        </div>
        </div>
    </div>
    </div>
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

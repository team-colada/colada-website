<template>
    <section id="features" class="features-container flex flex-col items-center mt-16 p-8  bg-slate-800">
      <div class="overflow-hidden">
        <div class="relative mx-auto max-w-7xl py-16 px-4 sm:px-6 lg:px-8">
          <div class="absolute top-0 bottom-0 left-3/4 hidden w-screen bg-slate-600 lg:block"></div>
          <div class="mx-auto max-w-prose text-base lg:grid lg:max-w-none lg:grid-cols-2 lg:gap-8">
            <div>
              <h2 class="text-lg font-semibold text-indigo-600">DevTools</h2>
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
                    <img class="rounded-lg object-cover object-center shadow-lg" src="../assets/gif/colada.gif" alt="gif of colada extension" width="1184" height="1376">
                    </div>
                    <figcaption class="mt-3 flex text-sm text-slate-400">
                    <!-- Bootstrap icon of 'image' -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-image" viewBox="0 0 16 16">
                        <path d="M6.002 5.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0z"/>
                        <path d="M2.002 1a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2h-12zm12 1a1 1 0 0 1 1 1v6.5l-3.777-1.947a.5.5 0 0 0-.577.093l-3.71 3.71-2.66-1.772a.5.5 0 0 0-.63.062L1.002 12V3a1 1 0 0 1 1-1h12z"/>
                    </svg>
                    <span class="ml-2">Colada Chrome Extension</span>
                    </figcaption>
                </figure>
                </div>
            </div>
          <div class="mt-8 lg:mt-0">
            <div class="mx-auto max-w-prose text-base lg:max-w-none">
              <p class="text-xl font-bold text-slate-300"><span class="text-orange-400">Colada</span> offers a suite of tools for Vue developers working with the <a class="rounded bg-slate-700 text-yellow-400 transition hover:bg-slate-600 active:bg-slate-500 pl-1 pr-1" href="https://pinia.vuejs.org/" target="_blank">Pinia</a> state management library</p>
            </div>
              <div class="prose prose-indigo mx-auto mt-5 text-slate-300 lg:col-start-1 lg:row-start-1 lg:max-w-none">
                <h4 class="text-xl font-bold border-b border-slate-500">Core Features</h4>
                <ol role="list" class="list-decimal pt-4">
                  <li><p class="text-lg">Minimal installation and automatic detection of Vue app in Vue.js DevTools.</p></li>
                  <li>
                    <p class="text-lg">Direct integration into <a class="rounded bg-slate-700 text-emerald-500 transition hover:bg-slate-600 active:bg-slate-500 pl-1 pr-1" href="https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en" target="_blank">Vue.js DevTools</a>, so developers can use Colada without needing to leave their existing devtool configuration.</p>
                    <div class="pl-8">
                        <ul role="list" class="list-disc">
                            <li>Time travel debugging</li>
                            <li>Inspector panel for viewing your Vue app's Pinia state</li>
                        </ul>
                    </div>
                  </li>
                  <li>
                    <p class="text-lg">A <a class="rounded bg-slate-700 text-blue-500 transition hover:bg-slate-600 active:bg-slate-500 pl-1 pr-1" href="https://chrome.google.com/webstore/detail/colada-devtools/icdbaobbeemmhlmjolbkedcneadkfpdl" target="_blank">Chrome DevTool Extension</a> providing enhanced features, including:</p>
                    <div class="pl-8">
                        <ul role="list" class="list-disc">
                            <li>Time travel debugging</li>
                            <li>Side panel for viewing your Vue app's current Pinia state</li>
                        </ul>
                    </div>
                  </li>
                </ol>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
</template>

<script>

    export default {
        name:'FeaturesContainer'
    }
</script>

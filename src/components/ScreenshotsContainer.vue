<template>
    <section id ="screenshots" class=" flex flex-col items-center border-b-2 border-slate-800 pt-16 p-8">
        <h3 class="text-3xl text-center font-bold pb-8">Screenshots</h3>
        <div id="carouselExampleCaptions" class="carousel slide relative" data-bs-ride="carousel">
            <div class="carousel-indicators absolute right-0 bottom-0 left-0 flex justify-center p-0 mb-4">
                <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="0"
                class="active"
                aria-current="true"
                aria-label="Slide 1"
                ></button>
                <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="1"
                aria-label="Slide 2"
                ></button>
                <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="2"
                aria-label="Slide 3"
                ></button>
                <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="3"
                aria-label="Slide 4"
                ></button>
                <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="4"
                aria-label="Slide 5"
                ></button>
            </div>
            <div class="carousel-inner relative w-full overflow-hidden">
                <div class="carousel-item relative float-left w-full">
                    <div class="relative overflow-hidden bg-no-repeat bg-cover" style="background-position: 50%;">
                        <img src="../assets/png/Plugin-timeline.png" class="block w-full" />
                    </div>
                    <div class="carousel-caption hidden md:block absolute text-center">
                        <h5 class="text-xl">Vue.js Plugin</h5>
                        <p>Colada Plugin Timeline</p>
                    </div>
                </div>
                <div class="carousel-item relative float-left w-full">
                    <div class="relative overflow-hidden bg-no-repeat bg-cover" style="background-position: 50%;">
                        <img src="../assets/png/Plugin-screenshots-off-toggle.png" class="block w-full" />
                    </div>
                    <div class="carousel-caption hidden md:block absolute text-center">
                        <h5 class="text-xl">Vue.js Plugin</h5>
                        <p>Colada Plugin - Turn off screenshots</p>
                    </div>
                </div>
                <div class="carousel-item relative float-left w-full">
                    <div class="relative overflow-hidden bg-no-repeat bg-cover" style="background-position: 50%;">
                        <img src="../assets/png/Plugin-inspector.png" class="block w-full" />
                    </div>
                    <div class="carousel-caption hidden md:block absolute text-center">
                        <h5 class="text-xl">Vue.js Plugin</h5>
                        <p>Colada Plugin - Inspector Panel</p>
                    </div>
                </div>
                <div class="carousel-item relative float-left w-full">
                    <div class="relative overflow-hidden bg-no-repeat bg-cover" style="background-position: 50%;">
                        <img src="../assets/png/Plugin-timeline-with-devtool-selection.png" class="block w-full" />
                    </div>
                    <div class="carousel-caption hidden md:block absolute text-center">
                        <h5 class="text-xl">Vue.js Plugin</h5>
                        <p>Colada Plugin - Navigate to Extension</p>
                    </div>
                </div>
                <div class="carousel-item active relative float-left w-full">
                    <div class="relative overflow-hidden bg-no-repeat bg-cover" style="background-position: 50%;">
                        <img src="../assets/png/Extension-time-travel.png" class="block w-full" />
                    </div>
                    <div class="carousel-caption hidden md:block absolute text-center">
                        <h5 class="text-xl">Chrome Extension</h5>
                        <p>Colada Timeline - Enables time-travel debugging</p>
                    </div>
                </div>
            </div>
            <button
                class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide="prev"
            >
                <span class="carousel-control-prev-icon inline-block bg-no-repeat" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button
                class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide="next"
            >
                <span class="carousel-control-next-icon inline-block bg-no-repeat" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </section>
</template>

<script>

import 'tw-elements'

export default {
    name: "ScreenshotsContainer"
}
</script>

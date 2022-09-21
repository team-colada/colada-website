<template>
    <section id="contributors" class="contributors-container overflow-hidden flex flex-col items-center gap-4 pt-16 p-8">
        <h3 class="text-3xl text-center font-bold">Contributors</h3>
        <div class="sm:columns-1 md:columns-2 xl:columns-4 p-8">
            <div :key="person.name" v-for="person in people" class="flex list-none">
                <ContributorCard  :person="person"/>
            </div>
        </div>
        <div>
            <p class="text-center p-8">Interested in contributing to Colada? Reach out to our core team for <a class="rounded text-sky-500 transition hover:text-sky-400 active:bg-sky-700 visited:text-purple-600 p-1" href="https://github.com/oslabs-beta/colada/issues" target="_blank">feature requests or issues/bugs</a> to report? Read our documentation on feature requests and issues/bugs.</p>
        </div>
    </section>
</template>

<script>
    import ContributorCard from './ContributorCard.vue'

    import VaughnImage from '../assets/png/vaughn-sulit.png'
    import ParkerImage from '../assets/png/parker-steinberg.png'
    import JonathanImage from '../assets/png/jonathan-chen.png'
    import DanImage from '../assets/png/dan-steinbrook.png'

    export default {
        name:'ContributorsContainer',
        components:{
            ContributorCard
        },
        data(){
            return{
                people: []
            }
        },
        mounted(){
            this.people = [
                {
                    image: VaughnImage,
                    name: 'Vaughn Sulit',
                    title: 'Software Engineer',
                    github:"https://github.com/bvaughnsulit",
                    linkedin: "https://www.linkedin.com/in/bvaughnsulit/"
                },
                {
                    image: ParkerImage,
                    name: 'Parker Steinberg',
                    title: 'Software Engineer',
                    github:"https://github.com/parkersteinberg",
                    linkedin: "https://www.linkedin.com/in/parker-steinberg/"
                },
                {
                    image: JonathanImage,
                    name: 'Jonathan Chen',
                    title: 'Software Engineer',
                    github:"https://github.com/JonHPC",
                    linkedin: "https://linkedin.com/in/jonathan-hp-chen"
                },
                {
                    image: DanImage,
                    name: 'Dan Steinbrook',
                    title: 'Software Engineer',
                    github:"https://github.com/dsteinbrook",
                    linkedin: "https://www.linkedin.com/in/daniel-steinbrook/"
                }
             ]
        }
    }
</script>


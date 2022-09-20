<template>
    <div id="contributors" class="contributors-container flex flex-col items-center gap-4 hover:border-2 border-red-500">
        <h3 class="text-3xl text-center font-bold">Contributors</h3>
        <div :key="person.name" v-for="person in people" class="flex">
            <ContributorCard  :person="person"/>
        </div>
        
    </div>
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
                    github:"https://github.com/bvaughnsulit",
                    linkedin: "https://linkedin.com"
                },
                {
                    image: ParkerImage,
                    name: 'Parker Steinberg',
                    github:"https://github.com/parkersteinberg",
                    linkedin: "https://linkedin.com"
                },
                {
                    image: JonathanImage,
                    name: 'Jonathan Chen',
                    github:"https://github.com/JonHPC",
                    linkedin: "https://linkedin.com/in/jonathan-hp-chen"
                },
                {
                    image: DanImage,
                    name: 'Dan Steinbrook',
                    github:"https://github.com/dsteinbrook",
                    linkedin: "https://linkedin.com"
                }
             ]
        }
    }
</script>


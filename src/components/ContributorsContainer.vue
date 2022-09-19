<template>
    <div class="contributors-container border border-green-500">
        <h1>ContributorsContainer.vue</h1>
        <div class="flex" v-for="person in people">
            <img class="rounded-full w-16 h-16" :src="person.image" />
            <p>{{person.name}}</p>
            <a href="" target="_blank">
                Github
            </a>
            <a href="" target="_blank">
                LinkedIn
            </a>
        </div>
    </div>
</template>

<script>
    import VaughnImage from '../assets/png/vaughn-sulit.png'
    import ParkerImage from '../assets/png/parker-steinberg.png'
    import JonathanImage from '../assets/png/jonathan-chen.png'
    import DanImage from '../assets/png/dan-steinbrook.png'

    export default {
        name:'ContributorsContainer',
        data(){
            return{
                people: []
            }
        },
        mounted(){
            this.people = [
                {
                    image: VaughnImage,
                    name: 'Vaughn Sulit'
                },
                {
                    image: ParkerImage,
                    name: 'Parker Steinberg'
                },
                {
                    image: JonathanImage,
                    name: 'Jonathan Chen'
                },
                {
                    image: DanImage,
                    name: 'Dan Steinbrook'
                }
             ]
        }
    }
</script>

<style scoped>
    .contributors-container{

    }
</style>

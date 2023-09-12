<template>
  <h2>{{ defaultTitle }}</h2>
  <p>{{ counter }}</p>
  <br>
  <button @click="increse" >+</button>
  <button @click="decrese">-</button>
</template>

<script>
export default {
    props:['title'],
    data(){
        return{
            counter: 5
        }
    },
    methods:{

        increse(){
            this.counter++;
        },
        decrese(){
            this.counter--;
        }

    },
    computed:{
        defaultTitle(){
            return this.title || 'Counter';
        }
    }
}
</script>

<style>

</style>
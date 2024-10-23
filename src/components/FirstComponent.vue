<template>
<div>
    <h1>i am First Component</h1>
    <button v-on:click="getName()">Click me</button>
    <div>{{ salary }}</div>
    <button v-on:click="salary++">Increment me</button>

</div>
</template>


<script>

export default {
    name:'FirstComponent',
    data(){
        return{
            salary:1500

        }
    },
    methods:{
        getName(){
            return alert ("hi  i am alert")
        }

    }
 }

</script>




<style>
.fl{
    color: blueviolet;
    font-size: 50px;
    font-weight: bold;
}
a{
    text-decoration: none;
    font-size: 30px;
}
</style>
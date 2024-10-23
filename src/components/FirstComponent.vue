<template>
<div>
    <h1>i am First Component</h1>
    <p>my name is : {{name}}</p>
    <p>my age is : {{age}}</p>
    <p>my country is : {{country[0]}}</p>
    <p>I am maried : {{verif}}</p>
    
</div>
</template>


<script>

export default {
    name:'FirstComponent',
    data(){
        return{
            age:50,
            name:'salem',
            country:['tunisia','algerie','egypt','jordan'],
            verif:true
        }
    }

}
</script>




<style>

</style>
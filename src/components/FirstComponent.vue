<template>
<div>
    <h1>i am First Component</h1>
    <h2>{{ msg }}</h2>
</div>
</template>


<script>

export default {
    name:'FirstComponent',
    props:{
        msg:String
    }
}
</script>




<style>

</style>
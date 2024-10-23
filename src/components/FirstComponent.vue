<template>
<div>
    <SecondComponent />
    <h1>i am FirstComponent</h1>
    

</div>
</template>


<script>
import SecondComponent from './SecondComponent';

export default {
    name:'FirstComponent',
    components:{
        SecondComponent
    }
}
</script>




<style>
h1{
    color: brown;

}

</style>
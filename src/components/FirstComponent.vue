<template>
<div>
    <h1>i am First Component</h1>
    <div :class="className">Salem Bahri</div>
    <!-- i can use method -->
    <!-- <div :class="getLink()">Salem Bahri</div> -->

    <a :href="link" target=_blank>Google</a><br>
    <img :src="linkImg" alt="">
    
</div>
</template>


<script>

export default {
    name:'FirstComponent',
    data(){
        return{
            className:'fl',
            link:'http://google.com',
            linkImg:'https://gratisography.com/wp-content/uploads/2024/01/gratisography-cyber-kitty-800x525.jpg'
            
        }
    },
    methods:{
        getLink(){
            return 'fl'
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
<template>
<div>
    <h1>i am First Component</h1>
    <div id="sal" style="font-weight: bold;">{{salary}}</div>
    <input type="text" v-model="salary" @input="testInput">
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
        testInput(){
            let s=document.getElementById('sal');
            if ((this.salary>2000)&&(this.salary<4000)) {
                s.style.color='green';
                
            } else {
                s.style.color='red';
            }
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
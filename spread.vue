<template>
    <div>
        <h1>spread operator</h1>
        <button @click="fun()">click</button>
    </div>
</template>
<script>
export default{
    name:"SpreaD",
    data(){
        return{
         array:[2,5,4,9,7,2]
       
        }
    },
methods:
    {
     fun(){
const array=[6,...this.array]
console.log(array);
        }
    }
   
}
</script>

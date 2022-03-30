<template>

<div>

<h1>ES6 methods </h1>

<h3>{{name}}</h3>

<button @click="fun()">change_name</button>

</div>

</template>

<script>


export default {

name:"SukanyA",

data(){

return{

name:"mantra",

}

},


methods:{

fun(){

this.name="technologies";

return this.name ;

}

}}


</script>


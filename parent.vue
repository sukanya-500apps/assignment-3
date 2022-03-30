<template>
    <div>
        <h2>message:{{message}}
        </h2>
        <h2>name:{{name}}</h2>
        <h2>mobile:{{mobile}}</h2>
    </div>
</template>
<script>
export default{
    name:"SuKanya",
    props:{
message:String,
name:String,
mobile:Number
    }
}
</script>

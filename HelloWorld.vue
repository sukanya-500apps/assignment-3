<template>
  <div class="hello">
    <sukanya :message="message" :name="name" :mobile=1564651231 />
  </div>
</template>

<script>
import sukanya from './parent.vue'
export default {
  name: 'HelloWorld',
components:{
  sukanya
},
data(){
return{
message:"welcome",
name:"sukanya",
mobile:1564651231
}
}
}
</script>


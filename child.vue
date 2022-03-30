<template>
    <button @click='emitcustomevent' >update</button>
</template>
<script>
export default{
    name:'ChiLd',
    methods:{
        emitcustomevent()
        {
        this.$emit('emit-name',{msg:'sukanya'})
    }
    }
}
</script>


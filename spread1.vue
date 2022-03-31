<template>
    <div>
        <button @click="fun1()">click</button>
    </div>
</template>
<script>
export default{
    name:"SpreaD1",
    data()
    {
        return{
            array1:[45,66,22,55,77],
            array2:[55,88,52,62,32],
        }
    },
    methods:
    {
        fun1(){
            this.array3=[...this.array1,...this.array2]
            console.log(this.array3)
        }
    }
}
</script>

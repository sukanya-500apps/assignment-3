<template>
    <div>
        <table align="centre">
            <thead>
                <th>Name</th>
                <th>Index</th>
                </thead>
                <tbody>
                    <tr v-for="user in users" :key="user.id">
                        <td>{{user.name}}</td>
                        <td>{{user.Index}}</td>
                    </tr>
                </tbody>
        </table>
    </div>
</template>
<script>
export default {
    name:"QuestioN1",
    data(){
        return{
users:[{"name":"AgileCRM" , "Index" : "1"},

{"name":"Mantra Technologies" , "Index" : "2"},

{"name":"500apps Python" , "Index" : "3"},

{"name":"500apps Infinity" , "Index" : "4"}]

}

},

}
</script>

<template>
    <div>
        <table align="centre">
           <h3>{{table_data}}</h3>
           <button @click="fun()">click</button>
            <tbody>
            <tr v-for="name in table_data" :key="name.id"></tr>
            <tr v-for="description in table_data" :key="description.id"> </tr>
<tr v-for="yearsofexperience in table_data" :key="yearsofexperience"></tr>
<tr v-for="Location in table_data" :key="Location"></tr>
<td>{{table_data.name}}</td>
<td>{{table_data.description}}</td>
<td>{{table_data.yearsofexperience}}</td>
<td>{{table_data.Location}}</td>
            </tbody>
        </table>
    </div>
</template>
<script>
export default{
    name:"QuestioN2",
    data(){
return{
    table_data :[{ 
        "name" :" Agile CRM" ,
         "description" :" A company of excellence",
          "Yearsofexperience":"12", 
          "Location":"Hyderabad"
    }]
}

    },
    methods:{
    fun(){
    const table_data=[table_data]
    console.log(this.table_data)
    }
    }
}
</script>

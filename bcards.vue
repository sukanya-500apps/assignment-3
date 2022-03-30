<template>
  <div class="hello">
    <b-card
    title="Card Title"
    img-src="https://picsum.photos/600/300/?image=25"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      [{ "name" :" Agile CRM" , "description" :" A company of excellence"}, {"name":"mantra technologies", "description":"500apps" },{"name":"500apps Python", "description":"Backend built using python" },{"name":"500apps infinity", "description":"Built
using vue JS" }]
    </b-card-text>

    
  </b-card>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>



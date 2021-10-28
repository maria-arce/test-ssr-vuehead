<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
   
  </div>
</template>

<script>
//import { defineComponent, computed, reactive } from 'vue'
//import { useHead } from '@vueuse/head'

export default{
name: 'Hello World',
  props:{
    msg:String
  }
}

 /* export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: String
  },
   setup() {
    const siteData = reactive({
      title: `SRR Test metas`,
      description: `Lorem ipsum dolor sit amet`,
    })

    useHead({
      // Can be static or computed
      title: computed(() => siteData.title),
      meta: [
        {
          name: `description`,
          content: computed(() => siteData.description),
        },
      ],
    })
  },
})*/
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

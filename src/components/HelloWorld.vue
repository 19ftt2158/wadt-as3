<template>
  <figure class="bg-gray-100 rounded-xl p-8">
  
  <div class="pt-6 space-y-4">
    <blockquote>
      <img class="w-32 h-32 rounded-full mx" src="./me.jpg" alt="" width="384" height="512">
      <p class="text-lg">
        “This will be info about myself”
      </p>
    </blockquote>
    <figcaption>
      <div>
        Muhammad Nabil Bin Muhammad Fauzi
      </div>
      <div>
        Student at Politeknik,
        Level 5 in Web Development,
        Dedicated (not really) Shadow Paladin Main
      </div>
    </figcaption>
  </div>
</figure>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
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
p {
  color: #42b983;
}
</style>

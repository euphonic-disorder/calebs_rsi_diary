<template>
  <div class="py-6 border-b-2 border-black flex flex-col space-y-2">
    
    <article class="prose lg:prose-xl prose-img:drop-shadow-md prose-img:rounded-xl prose-p:text-black">
  <h3># RSI Day ({{ day }})</h3>
  <img :src="imgSRC"/>
  <p>
    {{ body }}
  </p>
</article>
  </div>
</template>

<script>
export default {
  props: {
    day: Number,
    imgSRC: String,
    body: String,
  }
}
</script>

<style>

</style>
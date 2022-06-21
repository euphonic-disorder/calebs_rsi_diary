<template>
  <div class="py-6 border-b-2 border-black dark:border-white flex flex-col space-y-2">
    
    <article class="prose lg:prose-xl prose-img:drop-shadow-md prose-img:rounded-xl prose-p:text-black prose-img:max-h-64">
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
<template>
  <div class="py-6 border-b-2 border-black flex flex-col space-y-2">
    <img :src="imgSRC" class="h-fit w-3/5 self-center rounded-lg drop-shadow-md"/>
    <article class="prose lg:prose-xl">
  <h3>RSI Day ({{ day }})</h3>
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
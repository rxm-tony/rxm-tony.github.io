<script setup lang="ts">

</script>

<template>
  <!-- <div class="hidden lg:flex fixed left-8 bottom-4 bg-orange-200 p-4 flex-col gap-1 justify-center items-center">
    <div class="text-2xl font-bold">
      お問い合わせ
    </div>
    <div class="flex gap-4">
      <img 
        class="object-scale-down h-10"
        src="/images/LINE_Brand_icon.png"
      >
      <Icon
        name="material-symbols:mail-outline"
        size="3rem"
      />
    </div>
    <div class="font-bold">
      24H無料相談受付中
    </div>
    <div class="text-xl text-center font-bold">
      <Icon
        name="ic:twotone-call"
        size="1.5rem"
        color="white"
        class="bg-pink-300 rounded-full p-1"
      />
      {{ '0120-519-773' }}
    </div>
  </div> -->
  <div class="md:hidden grid grid-cols-1 w-7/12 mx-auto fixed left-0 right-0 bottom-3">
    <Button
      size="lg"
      as-child
      class="bg-green-500 w-full rounded-xl shadow-md shadow-slate-400 text-lg font-bold h-10"
    >
      <a
        href="https://lin.ee/HqEAKtY"
        target="_blank"
      >
        <img 
          class="object-scale-down h-10"
          src="/images/LINE_Brand_icon.png"
        >
        LINEで無料相談
      </a>
    </Button>
  </div>
</template>



<style scoped>

</style>
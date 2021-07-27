<template>
  <div class="   justify-center tracking-widest">
    <h1 class="justify-center">Let Live</h1>
    <div
      class="
        tracking-widest
        text-2xl
        font-bold
        justify-center
        text-transparent
        md:text-3xl
        bg-clip-text bg-gradient-to-r
        from-cyan-400
        to-blue-gray-800
      "
    >
      Sivasankaran T
    </div>
    <div
      class="
        py-5
        px-8
        mx-auto
        bg-white
        rounded-xl
        sm:py-4
        sm:flex
        sm:items-center
        sm:space-y-0 sm:space-x-6
      "
    >
      <img
        class="block mx-auto h-24 rounded-full sm:mx-0 sm:flex-shrink-0"
        src="@/assets/sivasan.jpeg"
        alt=""
      />
      <div class="text-center space-y-2 sm:text-left">
        <div class="space-y-0.5">
          <p class="text-lg text-black font-semibold">Sivasankaran T</p>
          <p class="text-gray-500 font-medium">Artist | Designer | Developer</p>
        </div>
        <button
          class="
            px-4
            py-1
            text-sm text-purple-600
            font-semibold
            rounded-full
            border border-purple-200
            hover:text-white
            hover:bg-purple-600
            hover:border-transparent
            focus:outline-none
            focus:ring-2 focus:ring-purple-600 focus:ring-offset-2
          "
        >
          Message
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<style>
</style>
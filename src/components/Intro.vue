<script setup>
import Heading from "../components/Heading.vue";

const work =
  "bg-gradient-to-tr from-slate-200 to-white py-5 rounded-xl shadow-xl";
</script>
<template>
  <section id="intro" class="bg-[#f1f3f6]">
    <div class="w-4/5 mx-auto py-10">
      <div class="text-center">
        <div class="text-[56px] text-[#5f5e5f1a] font-extrabold">
          <span>About Me!</span>
        </div>
        <div class="text-[35px] text-pink-400 font-bold -mt-10">
          <h2 class="">About Me!</h2>
        </div>
      </div>

      <div
        class="grid grid-cols-1 md:grid-cols-2 gap-5 md:gap-20 py-5 md:py-10"
      >
        <div class="text-left flex justify-center flex-col">
          <Heading>Hi, I'm Akhi Jannat</Heading>

          <small class="text-lg italic mt-1">FRONTEND DEVELOPER</small>
          <p class="mt-3">
            I'm a top-rated freelancer on Upwork with expertise in HTML, CSS,
            Bootstrap, Tailwind CSS, JavaScript, PHP, Laravel, Vue.js, and
            Alpine JS.
          </p>
          <p class="mt-3">
            I'm a top-rated freelancer on Upwork with expertise in HTML, CSS,
            Bootstrap, Tailwind CSS, JavaScript, PHP, Laravel, Vue.js, and
            Alpine JS.
          </p>
        </div>

        <div class="">
          <img
            src="../assets/girl's image.jpg"
            alt="/"
            class="rounded shadow-xl w-full"
          />
        </div>
      </div>
    </div>

    <div class="text-center py-10">
      <Heading>Why You Hire Me?</Heading>

      <div class="h-1 w-52 bg-slate-400 mx-auto rounded-full my-3"></div>

      <p class="w-full md:w-1/2 mx-auto">
        Over the past years, I created 50s of websites for my clients. I pride
        myself on doing quality work and maintain excellent communication. I
        enjoy working with include ReactJS, JavaScript as well as Laravel.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-5 items-center gap-5 px-2 mt-5">
        <div></div>
        <div :class="work" style="font-family: 'Bentham', serif">
          <h1 class="text-5xl">100 %</h1>
          <p>SUCCESS RATE</p>
        </div>
        <div :class="work" style="font-family: 'Bentham', serif">
          <h1 class="text-5xl">200 +</h1>
          <p>HAPPY CLIENTS</p>
        </div>
        <div :class="work" style="font-family: 'Bentham', serif">
          <h1 class="text-5xl">1,000 +</h1>
          <p>HOURS OF WORK</p>
        </div>
        <div></div>
      </div>

      <div class="mt-8">
        <a
          href="#"
          class="bg-gradient-to-r from-red-400 to-red-300 text-gray-600 hover:bg-gradient-to-l hover:from-red-600 hover:to-red-500 hover:text-white py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out"
          >You Can Hire Me</a
        >
      </div>
    </div>
  </section>
</template>

<style scoped></style>

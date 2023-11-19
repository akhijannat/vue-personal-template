<script setup>
const sectionBg =
  "relative h-screen flex flex-col justify-center items-center bg-cover bg-center bg-no-repeat";

const animationBtn =
  "animate-bounce w-16 h-16 bg-gradient-to-r from-[#f1f3f6] to-red-300 flex justify-center items-center rounded-full border shadow-2xl";
</script>

<template>
  <section id="welcome" :class="sectionBg" :style="welcomeBg">
    <div class="relative p-16 text-center text-white">
      <h1
        class="text-4xl md:text-8xl font-semibold mb-3"
        style="font-family: 'Bentham', serif"
      >
        Akhi Jannat
      </h1>
      <p class="sm:text-3xl pt-3 pb-5">
        FRONTEND
        <span
          class="italic font-bold bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600 text-transparent"
          >Vue 3 & Tailwind css</span
        >
        DEVELOPMENT
      </p>
      <p class="">
        Specializing In Custom Web Development. If You Are A Business Seeking A
        <br />
        Web Presence Or Are Looking To Hire, You can Contact with Me.
      </p>
    </div>

    <a href="#intro" :class="animationBtn">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="black"
        class="w-8 h-8 transform transition duration-500 hover:scale-125"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M12 3.75v16.5M2.25 12h19.5M6.375 17.25a4.875 4.875 0 004.875-4.875V12m6.375 5.25a4.875 4.875 0 01-4.875-4.875V12m-9 8.25h16.5a1.5 1.5 0 001.5-1.5V5.25a1.5 1.5 0 00-1.5-1.5H3.75a1.5 1.5 0 00-1.5 1.5v13.5a1.5 1.5 0 001.5 1.5zm12.621-9.44c-1.409 1.41-4.242 1.061-4.242 1.061s-.349-2.833 1.06-4.242a2.25 2.25 0 013.182 3.182zM10.773 7.63c1.409 1.409 1.06 4.242 1.06 4.242S9 12.22 7.592 10.811a2.25 2.25 0 113.182-3.182z"
        />
      </svg>
    </a>
  </section>
</template>
<style scoped>
#welcome {
  background-color: #000;
}

#welcome::before {
  content: " ";
  display: block;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  opacity: 0.3;
  background: url("https://images.unsplash.com/photo-1500534314209-a25ddb2bd429?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D")
    no-repeat center center;
  background-size: cover;
}
</style>

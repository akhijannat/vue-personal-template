<script setup>
import Heading from "../components/Heading.vue";

const uniqueItem =
  "flex-auto bg-cover bg-center transition-all duration-500 ease-in-out hover:flex-grow cursor-pointer";
</script>

<template>
  <section id="unique" class="bg-red-200">
    <div class="w-4/5 mx-auto text-center pt-10">
      <Heading>What makes me unique?</Heading>

      <div class="h-1 w-52 bg-slate-400 mx-auto rounded-full my-3"></div>
    </div>

    <div class="flex w-full h-full items-center justify-center py-7">
      <div class="flex w-5/6 h-[500px]">
        <div
          class="slide"
          :class="uniqueItem"
          style="
            background-image: url('https://images.unsplash.com/photo-1533468432434-200de3b5d528?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=975&q=80');
          "
        >
          <div class="hidden">
            <h1 class="5xl">Learn and Earn</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
              culpa.
            </p>
            <img
              src="../assets/64a7d84c315795109de4d218_food-p-500.webp"
              alt=""
              class="h-[200px]"
            />
          </div>
        </div>

        <div
          class="slide"
          :class="uniqueItem"
          style="
            background-image: url('https://images.unsplash.com/photo-1586254574632-55e4aaea7793?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80');
          "
        >
          <div class="hidden">
            <h1 class="5xl">Learn and Earn</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
              culpa.
            </p>
            <img
              src="../assets/64a7d84c315795109de4d218_food-p-500.webp"
              alt=""
              class="h-[200px]"
            />
          </div>
        </div>

        <div
          class="slide"
          :class="uniqueItem"
          style="
            background-image: url('https://images.unsplash.com/photo-1536536982624-06c1776e0ca8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80');
          "
        >
          <div class="hidden">
            <h1 class="5xl">Learn and Earn</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
              culpa.
            </p>
            <img
              src="../assets/64a7d84c315795109de4d218_food-p-500.webp"
              alt=""
              class="h-[200px]"
            />
          </div>
        </div>

        <div
          class="slide"
          :class="uniqueItem"
          style="
            background-image: url('https://images.unsplash.com/photo-1586254574632-55e4aaea7793?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80');
          "
        >
          <div class="hidden">
            <h1 class="5xl">Learn and Earn</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
              culpa.
            </p>
            <img
              src="../assets/64a7d84c315795109de4d218_food-p-500.webp"
              alt=""
              class="h-[200px]"
            />
          </div>
        </div>

        <div
          class="slide"
          :class="uniqueItem"
          style="
            background-image: url('https://images.unsplash.com/photo-1502827186494-9f7976a04548?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=976&q=80');
          "
        >
          <div class="hidden">
            <h1 class="5xl">Learn and Earn</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
              culpa.
            </p>
            <img
              src="../assets/64a7d84c315795109de4d218_food-p-500.webp"
              alt=""
              class="h-[200px]"
            />
          </div>
        </div>

        <div
          class="slide"
          :class="uniqueItem"
          style="
            background-image: url('https://images.unsplash.com/photo-1533468432434-200de3b5d528?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=975&q=80');
          "
        >
          <div class="hidden">
            <h1 class="5xl">Learn and Earn</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
              culpa.
            </p>
            <img
              src="../assets/64a7d84c315795109de4d218_food-p-500.webp"
              alt=""
              class="h-[200px]"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.slide:hover {
  flex: 5;
}
</style>

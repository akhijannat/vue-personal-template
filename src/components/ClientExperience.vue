<script setup>
import Heading from "../components/Heading.vue";
const clientExCard =
  "border bg-gradient-to-tr from-slate-200 to-white p-5 rounded-xl shadow-lg shadow-slate-300";
</script>
<template>
  <section id="clientExperience">
    <div class="w-4/5 mx-auto py-10 text-center col-span-full">
      <Heading>My Client Experience</Heading>

      <div class="h-1 w-52 bg-slate-400 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10">
        <div :class="clientExCard" style="font-family: 'Bentham', serif">
          <img
            class="h-28 w-28 rounded-full mx-auto"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoKJPxxwPeNvISnBbZsZHe887Ws0FnrL7o0w&usqp=CAU"
            alt=""
          />
          <h1 class="text-4xl">Hassan Asim</h1>
          <p class="font-serif">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            minus nihil doloremque. Incidunt accusamus magni, velit non quisquam
            nesciunt tenetur?
          </p>
        </div>

        <div :class="clientExCard" style="font-family: 'Bentham', serif">
          <img
            class="h-28 w-28 rounded-full mx-auto"
            src="../assets/girl's image.jpg"
            alt=""
          />
          <h1 class="text-4xl">Akhi Jannat</h1>
          <p class="font-serif">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            minus nihil doloremque. Incidunt accusamus magni, velit non quisquam
            nesciunt tenetur?
          </p>
        </div>

        <div :class="clientExCard" style="font-family: 'Bentham', serif">
          <img
            class="h-28 w-28 rounded-full mx-auto"
            src="https://engineering.unl.edu/images/staff/Kayla-Person.jpg"
            alt=""
          />
          <h1 class="text-4xl">Jain Doe</h1>
          <p class="font-serif">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            minus nihil doloremque. Incidunt accusamus magni, velit non quisquam
            nesciunt tenetur?
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

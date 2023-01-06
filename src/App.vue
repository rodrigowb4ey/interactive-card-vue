<template>
  <main class="flex border-4 border-yellow-500">
    <section
      id="card-faces"
      class="flex flex-col justify-around place-items-center border-2 border-blue-700 h-full w-1/2"
    >
      <img
        class="flex h-fit w-fit pr-16"
        src="/assets/images/bg-card-front.png"
        alt="Card Front"
      />
      <img
        class="flex h-fit w-fit pl-16"
        src="/assets/images/bg-card-back.png"
        alt="Card Back"
      />
    </section>
    <form action=""></form>
  </main>
</template>

<script>
export default {
  name: "App",
};
</script>

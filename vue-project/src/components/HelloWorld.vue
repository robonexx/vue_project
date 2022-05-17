<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
  greeting: {
    type: String,
    required: true,
  },
  name: {
    type: String,
    required: true,
  }
});
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h2 >{{greeting}} {{name}}</h2>
    <h3>
      You come to my new test website, you can find my latest projects here
      <a target="_blank" href="https://www.lockerlegends.org/">LockerLegends</a> +
      <a target="_blank" href="https://www.robertwagar.se/">Portfolio</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-size: 2.6rem;
  top: -10px;
  font-family: var(--font-big);
}

h2 {
  font-size: 1.2;
  font-weight: 800;
  color: #ee4e34;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>

<script setup>
import {ref} from 'vue'

const name = ref('')

</script>

<template>

 <main class="app">

<section class="greetin">
<h2 class="title">
  Welcome back, <input type="placeholder=Enter Name" v-model="name">
</h2>
</section>

<section class="create-Countdown">

</section>


<section class="countdown-list">

</section>


 </main>

</template>

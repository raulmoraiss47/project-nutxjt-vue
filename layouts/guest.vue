<script lang="ts">

</script>


<template>

<div>
    <ul class="bg-zinc-950 text-yellow-500 font-bold p-10 mb-4">
        <li>
            <NuxtLink href="/register" prefetch>Register</NuxtLink>
        </li>
      <li>
        <NuxtLink href="/login" prefetch>Login</NuxtLink>
      </li>
    </ul>
  </div>

  <slot/>
    
</template>



<style scoped>

</style>
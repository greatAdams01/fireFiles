<template>
  <main class="container">
    <section class="mt-20 mb-30">
      <div class="grid grid-cols-2 gap-4 px-10">
        <div class="create-acc bg-white rounded-xl">
          <div class="text-center pt-16 text-3xl">
            <h1>Create your <span class="free">free</span> account</h1>
          </div>
          <form class="px-10 py-10">
            <div class="flex justify-between py-10">
              <input class="input-style w-52" type="text" name="" id="" placeholder="First name">
              <input class="input-style w-52" type="text" name="" id="" placeholder="Last name">
            </div>
            <div class="py-10">
              <input class="input-style w-full" type="text" name="" id="" placeholder="Email">
            </div>
            <div class="py-10">
              <input class="input-style w-full" type="text" name="" id="" placeholder="Password">
            </div>
            <div class="flex">
              <input class="w-8" type="checkbox" name="" id="">
              <p class="">I agree with firefiles <span class="free">Terms and Services.</span> </p>
            </div>

            <div class="text-center py-10">
              <input class="btn-submit" type="submit" value="Create Account">
            </div>
          </form>
          <div class="log rounded-b-2xl text-white">
            <p class="p-5">Already have an account ? <NuxtLink class="underline" to="/">Login Here</NuxtLink> </p>
          </div>
        </div>
        <div class="p-20">
          <div class="gray p-20">
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script setup lang="ts">
</script>

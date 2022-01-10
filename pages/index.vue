<template>
  <header class="inline-block w-screen justify-items-stretch">
    <img src="../static/BLUR.png" class="inline-block w-25 mob-bl p-5" />
    <ul class="inline place-self-center place-content-center place-items-center">
      <li class="inline">
        <NuxtLink to="/"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-25 mob-bl p-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z"
            /></svg
        ></NuxtLink>
      </li>
      <li class="inline">
        <NuxtLink to="/about"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-25 mob-bl p-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z"
              clip-rule="evenodd"
            /></svg
        ></NuxtLink>
      </li>
      <li class="inline">
        <a href="https://exchange.crypto.puffercat.xyz">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-25 mob-bl p-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M4 4a2 2 0 00-2 2v4a2 2 0 002 2V6h10a2 2 0 00-2-2H4zm2 6a2 2 0 012-2h8a2 2 0 012 2v4a2 2 0 01-2 2H8a2 2 0 01-2-2v-4zm6 4a2 2 0 100-4 2 2 0 000 4z"
              clip-rule="evenodd"
            /></svg
        ></a>
      </li>
      <li class="inline">
        <NuxtLink to="/nft"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-25 mob-bl p-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
            /></svg
        ></NuxtLink>
      </li>
      <li class="inline">
        <a
          href="https://solscan.io/token/2CBJuwoaD3pb6RnHgqoreRGuoZJJbYUAoafiskYDH4iF"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="inline-block w-25 mob-bl p-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path d="M2 10a8 8 0 018-8v8h8a8 8 0 11-16 0z" />
            <path d="M12 2.252A8.014 8.014 0 0117.748 8H12V2.252z" /></svg
        ></a>
      </li>
    </ul>
    <NuxtLink to="/airdrop" class="inline">
<svg xmlns="http://www.w3.org/2000/svg" class="inline-block w-25 mob-bl p-5" viewBox="0 0 20 20" fill="currentColor">
  <path fill-rule="evenodd" d="M5 5a3 3 0 015-2.236A3 3 0 0114.83 6H16a2 2 0 110 4h-5V9a1 1 0 10-2 0v1H4a2 2 0 110-4h1.17C5.06 5.687 5 5.35 5 5zm4 1V5a1 1 0 10-1 1h1zm3 0a1 1 0 10-1-1v1h1z" clip-rule="evenodd" />
  <path d="M9 11H3v5a2 2 0 002 2h4v-7zM11 18h4a2 2 0 002-2v-5h-6v7z" />
</svg>
    </NuxtLink>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>

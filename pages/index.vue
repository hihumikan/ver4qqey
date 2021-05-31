<template>
  <div>
    <nav
      class="font-sans bg-white text-center flex justify-between my-4 mx-auto container overflow-hidden"
    >
      <a href="/" class="block text-left">
        <p class="text-2xl font-black">qqey.net</p>
      </a>
      <ul class="text-sm text-gray-700 list-none p-0 flex items-center">
        <li>
          <a
            href="#"
            class="inline-block py-2 px-3 text-gray-900 hover:text-gray-700 no-underline"
            >About</a
          >
        </li>
        <li>
          <a
            href="#"
            class="inline-block py-2 px-3 text-gray-900 hover:text-gray-700 no-underline"
            >Link</a
          >
        </li>
        <li class="pr-2">
          <a
            href="#"
            class="inline-block py-2 px-3 text-gray-900 hover:text-gray-700 no-underline"
          ></a>
        </li>
      </ul>
    </nav>
    <div class="w-screen h-screen flex justify-center items-center bg-gray-100">
      <form
        class="p-10 bg-white rounded flex justify-center items-center flex-col shadow-md"
      >
        <div class="flex flex-wrap justify-center">
          <div class="w-6/12 sm:w-4/12 px-4">
            <img
              src="https://avatars.githubusercontent.com/u/26848713?v=4"
              class="shadow rounded-full max-w-full h-auto align-middle border-none"
            />
          </div>
        </div>
        <p class="mb-5 mt-2 text-4xl text-gray-600">hihumikan</p>
        <p class="text-gray-600">最近、プログラミングはじめました。</p>
        <p class="text-gray-600">色々手を出し過ぎて全てが中途半端です。</p>
      </form>
    </div>
    <section class="font-sans container m-auto text-center py-8">
      <label
        for="tagline"
        class="uppercase tracking-wide font-bold text-gray-700"
        >Link</label
      >
      <h1 class="mt-2 mb-4 font-medium max-w-sm m-auto text-gray-700">
        日々、何かしてたり、してなかったり。
      </h1>
      <hr class="border-b w-8 m-auto my-6" />
      <div class="flex flex-wrap justify-between items-start">
        <div
          class="w-full sm:w-1/2 md:w-1/4 flex flex-col items-center justify-center p-4"
        >
          <fa class="text-gray-700 text-6xl" :icon="['fab', 'Github']" />
          <h2 class="my-4 font-medium">GitHub</h2>
          <p class="leading-normal mb-4 text-gray-700">
            何か色々リポジトリ作っては放置してる。最近はVue.jsとかGoとかRustとか。
          </p>
        </div>
        <div
          class="w-full sm:w-1/2 md:w-1/4 flex flex-col items-center justify-center p-4"
        >
          <div class="w-14 h-14 rounded-full bg-gray-100" alt="">
            <fa class="text-gray-700 text-6xl" :icon="['fab', 'twitter']" />
          </div>
          <h2 class="my-4 font-medium">Twitter</h2>
          <p class="leading-normal mb-4 text-gray-700">
            思ったことをただ呟くだけ。
          </p>
        </div>
        <div
          class="w-full sm:w-1/2 md:w-1/4 flex flex-col items-center justify-center p-4"
        >
          <div class="w-14 h-14 rounded-full mr-0 bg-gray-300" alt=""></div>
          <h2 class="my-4 font-medium">Blog</h2>
          <p class="leading-normal mb-4 text-gray-700">
            何か目次録として使うかも。
          </p>
        </div>
        <div
          class="w-full sm:w-1/2 md:w-1/4 flex flex-col items-center justify-center p-4"
        >
          <div class="w-14 h-14 rounded-full bg-gray-300" alt=""></div>
          <h2 class="my-4 font-medium">Telegram</h2>
          <p class="leading-normal mb-4 text-gray-700">
            何かあればこちらから。
            <fa :icon="['fas', 'home']" />
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>

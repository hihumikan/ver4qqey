<template>
<<<<<<< Updated upstream
  <div>
    <!-- component -->
    <div
=======
<<<<<<< Updated upstream
  <div class="container">
    <nav
>>>>>>> Stashed changes
      class="
        relative
        min-h-screen
        flex
        items-center
        justify-center
        bg-gray-50
        py-12
        px-4
        sm:px-6
        lg:px-8
        bg-gray-500 bg-no-repeat bg-cover
        relative
        items-center
        coverbg
      "
    >
      <div class="absolute bg-black opacity-60 inset-0 z-0"></div>
      <div class="max-w-md w-full space-y-8 p-10 bg-white rounded-xl z-10">
        <div class="text-center">
          <div class="flex flex-wrap justify-center">
            <div class="w-6/12 sm:w-4/12 px-4">
              <img
                src="https://avatars.githubusercontent.com/u/26848713?v=4"
                class="
                  shadow
                  rounded-full
                  max-w-full
                  h-auto
                  align-middle
                  border-none
                "
              />
            </div>
          </div>
          <h2 class="mt-6 text-3xl font-bold text-gray-900">hihumikan</h2>
          <p class="text-gray-600 pt-5">最近、プログラミングはじめました。</p>
          <p class="text-gray-600">色々手を出し過ぎて全てが中途半端です。</p>
          <div class="flex items-center justify-center space-x-3 pt-4">
            <button
              class="
                bg-gray-800
                px-4
                py-2
                font-semibold
                text-white
                inline-flex
                items-center
                space-x-2
                rounded
              "
            >
              <svg
                class="w-5 h-5 fill-current"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
                <fa class="text-white text-6xl" :icon="faGithub" />
              </svg>
              <span>GitHub</span>
            </button>
            <button
              class="
                bg-blue-300
                px-4
                py-2
                font-semibold
                text-white
                inline-flex
                items-center
                space-x-2
                rounded
              "
            >
              <svg
                class="w-5 h-5 fill-current"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
                <path
                  d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"
                />
              </svg>
              <span>Twitter</span>
            </button>
          </div>
        </div>
<<<<<<< Updated upstream
=======
        <p class="mb-5 mt-2 text-4xl text-gray-600">hihumikan</p>
        <p class="text-gray-600">最近、プログラミングはじめました。</p>
        <p class="text-gray-600">色々手を出し過ぎて全てが中途半端です。</p>
      </form>
    </div>
    <section class="font-sans container m-auto text-center py-8" id="link">
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
          class="
            w-full
            sm:w-1/2
            md:w-1/4
            flex flex-col
            items-center
            justify-center
            p-4
          "
        >
          <a href="https://github.com/hihumikan">
            <fa class="text-gray-700 text-6xl" :icon="faGithub" />
            <h2 class="my-4 font-medium">GitHub</h2>
            <p class="leading-normal mb-4 text-gray-700">
              何か色々リポジトリ作っては放置してる。最近はVue.jsとかGoとかRustとか。
            </p>
          </a>
        </div>
        <div
          class="
            w-full
            sm:w-1/2
            md:w-1/4
            flex flex-col
            items-center
            justify-center
            p-4
          "
        >
          <a href="https://twitter.com/mikan_54951">
            <fa class="text-gray-700 text-6xl" :icon="['fab', 'twitter']" />
            <h2 class="my-4 font-medium">Twitter</h2>
            <p class="leading-normal mb-4 text-gray-700">
              思ったことをただ呟くだけ。
            </p>
          </a>
        </div>
        <div
          class="
            w-full
            sm:w-1/2
            md:w-1/4
            flex flex-col
            items-center
            justify-center
            p-4
          "
        >
          <a href="https://blog.qqey.net/">
            <fa class="text-gray-700 text-6xl" :icon="faBlog" />
            <h2 class="my-4 font-medium">Blog</h2>
            <p class="leading-normal mb-4 text-gray-700">
              何かメモとして使うかも。
            </p>
          </a>
        </div>
        <div
          class="
            w-full
            sm:w-1/2
            md:w-1/4
            flex flex-col
            items-center
            justify-center
            p-4
          "
        >
          <a href="https://t.me/yata_touka">
            <fa class="text-gray-700 text-6xl" :icon="faTelegram" />
            <h2 class="my-4 font-medium">Telegram</h2>
            <p class="leading-normal mb-4 text-gray-700">
              何かあればこちらから。
            </p>
          </a>
=======
  <div>
    <!-- component -->
    <div
      class="
        relative
        min-h-screen
        flex
        items-center
        justify-center
        bg-gray-50
        py-12
        px-4
        sm:px-6
        lg:px-8
        bg-gray-500 bg-no-repeat bg-cover
        relative
        items-center
        coverbg
      "
    >
      <div class="absolute bg-black opacity-60 inset-0 z-0"></div>
      <div class="max-w-md w-full space-y-8 p-10 bg-white rounded-xl z-10">
        <div class="text-center">
          <div class="flex flex-wrap justify-center">
            <div class="w-6/12 sm:w-4/12 px-4">
              <img
                src="https://avatars.githubusercontent.com/u/26848713?v=4"
                class="
                  shadow
                  rounded-full
                  max-w-full
                  h-auto
                  align-middle
                  border-none
                "
              />
            </div>
          </div>
          <h2 class="mt-6 text-3xl font-bold text-gray-900">hihumikan</h2>
          <p class="text-gray-600 pt-5">最近、プログラミングはじめました。</p>
          <p class="text-gray-600">色々手を出し過ぎて全てが中途半端です。</p>
          <div class="flex items-center justify-center space-x-3 pt-4">
            <button
              class="
                bg-gray-800
                px-4
                py-2
                font-semibold
                text-white
                inline-flex
                items-center
                space-x-2
                rounded
              "
            >
              <svg
                class="w-5 h-5 fill-current"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
                <fa class="text-white text-6xl" :icon="faGithub" />
              </svg>
              <span>GitHub</span>
            </button>
            <button
              class="
                bg-blue-300
                px-4
                py-2
                font-semibold
                text-white
                inline-flex
                items-center
                space-x-2
                rounded
              "
            >
              <svg
                class="w-5 h-5 fill-current"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
                <path
                  d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"
                />
              </svg>
              <span>Twitter</span>
            </button>
          </div>
>>>>>>> Stashed changes
        </div>
>>>>>>> Stashed changes
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
<<<<<<< Updated upstream
=======
<<<<<<< Updated upstream
import { faBlog } from '@fortawesome/free-solid-svg-icons'
>>>>>>> Stashed changes
import { faGithub } from '@fortawesome/free-brands-svg-icons'

export default Vue.extend({
<<<<<<< Updated upstream
  data() {},
=======
  data() {
    return {
      telegram: 'https://github.com/hihumikan',
    }
  },
=======
import { faGithub } from '@fortawesome/free-brands-svg-icons'

export default Vue.extend({
  data() {},
>>>>>>> Stashed changes
>>>>>>> Stashed changes
  computed: {
    faGithub() {
      return faGithub
    },
<<<<<<< Updated upstream
=======
<<<<<<< Updated upstream
    faBlog() {
      return faBlog
    },
    faTelegram() {
      return faTelegram
    },
=======
>>>>>>> Stashed changes
>>>>>>> Stashed changes
  },
})
</script>

<style>
.coverbg {
  background-image: url('~/assets/castelmezzano-1979546_1920.jpg');
}
<<<<<<< Updated upstream
</style>
=======
</style>
>>>>>>> Stashed changes

<template>
  <section class="container px-5 py-12 mx-auto text-gray-600 body-font">
    <div class="flex flex-col w-full mb-8 text-center">
      <Heading1> Installed Vite plugins 📦 </Heading1>
      <p class="dark:text-gray-300">
        You can even find more awesome Vite plugins
        <a
          href="https://github.com/vitejs/awesome-vite"
          target="_blank"
          class="text-green-500"
        >
          here
        </a>
      </p>
    </div>
    <div class="flex flex-wrap -m-2">
      <div class="w-full p-2 md:w-1/2 lg:w-1/4">
        <Feature
          title="vite-plugin-vue2"
          text="Vue 2 support for Vite"
          url="https://github.com/underfin/vite-plugin-vue2"
        />
      </div>
      <div class="w-full p-2 md:w-1/2 lg:w-1/4">
        <Feature
          title="vite-plugin-windicss"
          text="Windi CSS for Vite"
          url="https://github.com/windicss/vite-plugin-windicss"
        />
      </div>
      <div class="w-full p-2 md:w-1/2 lg:w-1/4">
        <Feature
          title="unplugin-components"
          text="On demand components auto importing for Vite"
          url="https://github.com/antfu/unplugin-vue-components"
        />
      </div>
      <div class="w-full p-2 md:w-1/2 lg:w-1/4">
        <Feature
          title="unplugin-icons"
          text="Access thousands of icons as Vue components in Vite"
          url="https://github.com/antfu/unplugin-icons"
        />
      </div>
    </div>
  </section>
</template>

<script setup>
import { BloggerIcon, GitHubIcon, GmailIcon, MastodonIcon, TelegramIcon, XIcon } from 'vue3-simple-icons'

const { title, email, telegram, blog, twitter, mastodon, github } = useAppConfig()
</script>

<template>
  <section class="md:pt-6">
    <div class="container flex flex-col items-center py-8 mx-auto sm:flex-row">
      <a
        href="https://sink.cool"
        class="text-xl font-black leading-none text-gray-900 select-none dark:text-gray-100 logo"
        :title="title"
      >{{ title }}</a>
    </div>
  </section>
</template>

<script lang="ts" setup>
import { Button } from "@/components/ui/button";
</script>

<template>
  <aside class="px-5 py-8 bg-sidebar h-full relative w-full">
    <NuxtLink to="/" class="mb-10 block">
      <NuxtImg
        src="logo.jpg"
        alt="Logo"
        width="100px"
        class="mx-auto"
      ></NuxtImg>
    </NuxtLink>
    <Button variant="outline">Button</Button>
  </aside>
</template>

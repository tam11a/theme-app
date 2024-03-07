<script setup lang="ts">
import { Button } from "@/components/ui/button";
</script>

<template>
  <div class="flex flex-row items-center gap-3 flex-wrap m-4">
    <Button>Button</Button>
    <Button variant="outline">Button</Button>
    <Button variant="ghost">Button</Button>
    <Button variant="link">Button</Button>
    <Button variant="destructive">Button</Button>
    <Button variant="secondary">Button</Button>
  </div>
</template>

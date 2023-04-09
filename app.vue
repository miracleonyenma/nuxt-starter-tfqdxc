<template>
  <div>
    <PhHorse />
    <PhHeart :size="32" color="hotpink" weight="fill" />
    <PhCube />
  </div>
</template>
<script lang="ts" setup>
import { PhHorse, PhHeart, PhCube } from '@phosphor-icons/vue';
</script>

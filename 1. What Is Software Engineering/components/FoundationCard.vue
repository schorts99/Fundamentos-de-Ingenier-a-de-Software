<script setup lang="ts">
const { color, title, description } = defineProps<{
  color: string
  title: string
  description: string
}>()
</script>

<template>
  <div :class="`flex bg-slate-900 rounded p-3 border-l-3 border-l-${color} items-start`">
    <div :class="`rounded bg-${color}/10 py-1 p-2 aspect-square mr-3`">
      <slot />
    </div>

    <div>
      <div class="font-bold text-sm mb-1">
        {{ title }}
      </div>
      <div class="text-xs text-slate-500">
        {{ description  }}
      </div>
    </div>
  </div>
</template>

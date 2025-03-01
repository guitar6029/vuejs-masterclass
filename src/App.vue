<script setup lang="ts">
import { supabase } from '@/lib/supabaseClient'

console.log(supabase)
</script>

<template>
  <h3>Welcome</h3>
  <RouterView />
</template>

<style scoped></style>

<script setup lang="ts">
const { t } = useI18n({
  useScope: 'local'
})
</script>

<template>
  <p v-html="t('hello')" />
</template>

<i18n lang="yaml">
  en:
    hello: "Hello <em>World!</em>"
</i18n>

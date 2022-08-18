<template>
  <NConfigProvider inline-theme-disabled>
          <NDialogProvider>
             <NButton>Button</NButton>
              <NInput placeholder="NInput" />
              <NInputNumber placeholder="NInputNumger" />
          </NDialogProvider>
  </NConfigProvider>
</template>

<script lang="ts" setup>
import {
  NConfigProvider,
  NButton,
  NDialogProvider,
  NInput,
  NInputNumber,
} from 'naive-ui'

</script>

<style>
body {
  padding: 16px;
}
</style>

<script lang="ts" setup>
import zhCN from '@arco-design/web-vue/es/locale/lang/zh-cn';
</script>

<template>
  <a-config-provider :locale="zhCN">
    <RouterView />
  </a-config-provider>
</template>

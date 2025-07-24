<script lang="ts" setup>
import { Page, useVbenModal } from '@vben/common-ui';

import { NButton, NCard, useMessage } from 'naive-ui';

import { useVbenForm } from '#/adapter/form';
import { getAllMenusApi } from '#/api';

import modalDemo from './modal.vue';
import { router } from '#/router';


</script>
<template>
  <Page
    description="选择双列菜单模式并关闭标签页展示"
    title="bug演示"
  >
     这是页面
  </Page>
</template>

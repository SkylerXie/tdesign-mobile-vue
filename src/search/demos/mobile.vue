<template>
  <div class="tdesign-mobile-demo">
    <h1 class="title">Search 搜索框</h1>
    <p class="summary">用于用户输入搜索信息，并进行页面内容搜索。</p>
    <tdesign-demo-block title="01 组件类型" summary="基础搜索框">
      <baseDemo />
    </tdesign-demo-block>
    <tdesign-demo-block summary="字数限制">
      <maxLengthDemo />
    </tdesign-demo-block>
    <tdesign-demo-block summary="获取焦点后显示取消按钮">
      <actionDemo />
    </tdesign-demo-block>
    <tdesign-demo-block title="02 组件样式" summary="搜索框形状">
      <shapeDemo />
    </tdesign-demo-block>
    <tdesign-demo-block summary="默认状态其他对齐方式">
      <otherDemo />
    </tdesign-demo-block>
  </div>
</template>

<script lang="ts" setup>
import baseDemo from './base.vue';
import maxLengthDemo from './max-length.vue';
import actionDemo from './action.vue';
import shapeDemo from './shape.vue';
import otherDemo from './other.vue';
</script>

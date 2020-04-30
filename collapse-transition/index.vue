<template>
  <transition
    @beforeEnter="beforeEnter"
    @enter="enter"
    @afterEnter="afterEnter"
    @beforeLeave="beforeLeave"
    @leave="leave"
    @afterLeave="afterLeave"
  >
    <slot />
  </transition>
</template>

<script>
import func from './index';
export default {
  methods: {
    ...func,
  },
};
</script>


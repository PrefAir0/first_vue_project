<script setup>
import Header from '@/components/Header.vue';
import Preview from './components/Preview.vue';
</script>

<template>
  <div class="wrapper">
    <div class="content">
      <Header/>
      <Preview/>
    </div>
  </div>
</template>

<style scoped>
.content{
  display: flex;
  flex-direction: column;
  gap: 40px;
  /* padding: ; */
  color: var(--text-main);
  /* justify-content: space-around; */
}

.wrapper{
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}

.content a{
  color: var(--text-main);
}
</style>

<template>
  
  <div class="wrapper">
    <div class="content-wrapper">
      <h1 class="title-todo">TO-DO LIST</h1>
      <section>
        <MainPanel/>
      </section>  
    </div>
  </div>
  
</template>

<script>
import MainPanel from './components/MainPanel.vue';

export default {
  name: 'App',
  components: {
    MainPanel
  }
}
</script>

<style>

</style>

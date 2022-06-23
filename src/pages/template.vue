<template>
  <div class="text-bold" :title="name">
    Hello {{name}}
  </div>
  <div>Hello 2</div>

  <button :disabled="lock">{{age}}</button>
</template>

<script>
export default {
  data(){
    return {
      name : 'P',
      age : '27',
      lock: false,
    }
  },
}
</script>

<style>
.text-blod{
  font-weight: bold;
}
</style>
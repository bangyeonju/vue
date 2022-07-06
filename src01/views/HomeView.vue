<template>
  <div>
    <h1>HOME PAGE</h1>
    <YeonjuCoder title="home title" name="홍길동"/>
  </div>
</template>

<script>
import YeonjuCoder from '@/components/YeonjuCoder.vue';
export default {
  components: {
    YeonjuCoder
  },
  data(){
    return {
      name: 'YeonjuCoder'
    }
  }
}

</script>
<style scoped>
</style>


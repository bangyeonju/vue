<template>
  <div class="about">
    <h1>This is an about page</h1>
    <YeonjuCoder>
      <template #header22="{yeon}">
        <p>header11!{{yeon}}</p>
      </template>
      <template #default>
        hello
      </template>
    </YeonjuCoder>
  </div>
</template>
<script>
import YeonjuCoder from '@/components/YeonjuCoder.vue';

export default{
  components: {
    YeonjuCoder
  },
  // data(){
  //   return {
  //     title: 5
  //   }
  // }
}
</script>
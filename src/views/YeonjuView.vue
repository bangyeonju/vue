<template>
  <div>
    <h1>Yeonju PAGE</h1>
    <form action="">
      <InputField v-model="name"/>
      <br><button>Submit</button>
    </form>
    {{name}}
  </div>
</template>

<script>
import InputField from '@/components/InputField2.vue';

export default {
  components: {
    InputField
  },
  data() {
    return {
      name: ''
    }
  },
  // methods:{
  //   updateName(name){
  //     this.name= name;
  //   }
  // }
}

</script>
<style scoped>
</style>


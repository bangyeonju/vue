<template>
  <div>
    <h1>HOME PAGE!!</h1>
    <form action="">
      <InputField v-model="name"/>
      <!-- <InputField :name="name" @update-name="updateName"/> -->
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
  methods:{
    updateName(name){
      this.name= name;
    }
  }
}

</script>
<style scoped>
</style>


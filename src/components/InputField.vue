<template>
  <div>
    <label for="">Name</label>
      <input type="text" 
             :value="name"
             style="padding:30px; border: 2px solid green"
             @input="updateName"
             > 
             
  </div> 
</template>
<script>

export default {
  props:{
    name:{
      type:String,
      required:false
    }
  },
  methods:{
    updateName(e){
      console.log(e.target.value);
      this.$emit('update-name',e.target.value);
    }
  }
}
</script>

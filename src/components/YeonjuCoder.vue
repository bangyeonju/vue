
<template>
    <div>
        <p>header</p>
        <slot name="header22" :yeon="yeon"></slot>
        <p>Body</p>
        <slot></slot>
        <p>footer</p>

        <!-- <button @click="updateName">changeName</button> -->
    </div>
</template>
<script>

export default {
    props:{
        title:{
            type: String,
            default:'default title',
            
        },
        name:{
            type: String,
            default:'default name'
        }

    },
    data(){
        return {
            // name :'Yeonju Coder',
            yeon: 'coder'
        }
    },
    methods:{
        updateName(){
            // this.name ='Yeonju Coder Updated';
        }
    }
}
</script>
<style>
</style> 
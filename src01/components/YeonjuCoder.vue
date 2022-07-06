
<template>
    <div>
        <h1>{{title}}</h1>
        <p>{{name}}</p><br>
        <button @click="updateName">changeName</button>
    </div>
</template>
<script>

export default {
    // 부모컴포넌트에서 props로 자식컴포넌트로 데이터를 보냄!
    // 부모에서 자식으로 는 props를 사용하고, 반대로 자식에서 부모로 전달할 때는 events($emit)를 사용한다.
    props:{
        title:{
            type: String,
            default:'default title'
            
            
        },
        name:{
            type: String,
            default:'default name'
        }

    },
    data(){
        return {
            // name :'Yeonju Coder',
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
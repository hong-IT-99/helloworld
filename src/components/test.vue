<template>
    <div>
        <h1>{{test}}</h1>
        <h2>{{test2}}</h2>
        <h3>{{msg}}</h3>
    </div>
</template>

<script>
export default {
   data(){
       return{
           test:'Hello world',
           test2:'jhsjhsj'
       }
   },
   name : 'TestTest',
   props:{
       msg : String
   }
     
}
</script>


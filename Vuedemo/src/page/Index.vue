<template>
    <div id="index">
      <Banner/>
      <Login></Login>  
    </div>
</template>
<script>
import Banner from '../components/Index/Banner' 
import Login from '../components/Index/Login'    
export default {
 
    name:'Index',
    components:{
        Banner,
        Login,
    }
}
</script>
<style scoped>
#index{
    display: flex;
    height: 68rem;
    width: 110em;
   
}
</style>
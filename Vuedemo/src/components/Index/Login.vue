<template>
  <div id="login">
      <div class="loginbox">
   <Logo/>
      <Logindetail/>
      </div>

   
  </div>
</template>

<script>
export default {
components:{
    Logo:()=>import('./Logo'),
    Logindetail:()=>import('./Logindetail')
}
}
</script>

<style>
#login{
    width: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>
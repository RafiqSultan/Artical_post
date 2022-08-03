<template>
<div class="header">
    <div class="logo"><h1>RAAS</h1></div>
    <nav>
      <router-link to="/" exact><a>Home</a></router-link> 
      <router-link to="/about"><a>About</a></router-link>
      <router-link to="/help" replace><a>Help</a></router-link>
    </nav>
</div>
</template>


<script>
export default {
    name:'AppHeader'
}
</script>


<style lang="scss" scoped>
.header{
    background-color: #444;
    color: #FFF;
    overflow: hidden;
    height: 50px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px 0;
    .logo{
        text-align: left;
        font-size: 20px;
        width: 200px;
        color: #fff;
    }
    a{
        color: #FFF;
        margin: 0 10px;
    }
}

</style>
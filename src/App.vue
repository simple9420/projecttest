<template>
  <div id="app">
  	<leftNav></leftNav>
  	<div class="main">
    	<router-view/>
    </div>
  </div>
</template>

<script>
import leftNav from '@/components/common/leftNav'
export default {
  name: 'app',
  components:{
  	leftNav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.main{
	float: left;
	width: 95%;
	background-color: #eff2f7;
	height: 100%;
	overflow: hidden;
}
.el-tabs__nav{
	margin-left:20px ;
}
.el-tabs__active-bar{
	width: 28px !important;
}
</style>

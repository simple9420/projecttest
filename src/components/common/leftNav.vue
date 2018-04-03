<template>
	<div class="left-nav">
		<ul>
			<li>
				<i class="icon icon_sy"></i>
				<div>收银</div>
			</li>
			<li>
				<i class="icon icon_dp"></i>
				<div>店铺</div>
			</li>
			<li>
				<i class="icon icon_sp"></i>
				<div>商品</div>
			</li>
			<li>
				<i class="icon icon_vip"></i>
				<div>会员</div>
			</li>
			<li>
				<i class="icon icon_tj"></i>
				<div>统计</div>
			</li>
			<li>
				<i class="icon icon_sz"></i>
				<div>设置</div>
			</li>
		</ul>
	</div>
</template>

<script>
	export default{
		
	}
</script>

<style>
	.left-nav{
		color: #fff;
		font-size: 10px;
		height: 100%;
		background: #1D8CE0;
		float: left;
		width: 5%;
	}
	.icon{
		display: inline-block;
		width: 30px;
		height: 30px;		
	}
	.icon_dp{
		background: url(../../assets/images/dp.png) no-repeat;
		background-size: cover;
	}
	.icon_sy{
		background: url(../../assets/images/sy.png) no-repeat;
		background-size: cover;
	}
	.icon_sp{
		background: url(../../assets/images/sp.png) no-repeat;
		background-size: cover;
	}
	.icon_vip{
		background: url(../../assets/images/vip.png) no-repeat;
		background-size: 100%;
	}
	.icon_tj{
		background: url(../../assets/images/sy.png) no-repeat;
		background-size: cover;
	}
	.icon_sz{
		background: url(../../assets/images/sz.png) no-repeat;
		background-size: cover;
	}
	.left-nav ul{
		margin: 0;
		padding: 0;
	}
	.left-nav ul li{
		list-style: none;
		text-align: center;;
		border-bottom: 1px solid #20afff;
		padding: 10px;
	}
</style>
<template>
 	<div class="ticket-procard-con">
 		<div class="ticket-procard-title">【长隆周年庆】长隆水上乐园成人票（仅限8月28日）</div>
 		<div class="ticket-procard-pricecon">
 			<em class="ticket-procard-priceicon">&yen;</em>
 			<span class="ticket-procard-pricetext">140</span>
 			<span class="ticket-procard-marketprice">
 				票面价
 				<span class="ticket-underline">&yen;195</span>
 			</span>
 		</div>
 		<div class="ticket-procard-tagarea">
 			<div class="ticket-procard-ul">
 				<div class="ticket-procard-li"><span class="iconfont" style="color:#00bcd4;">&#xe610;</span>可定8月28日</div>
 				<div class="ticket-procard-li"><span class="iconfont" style="color:red; ">&#xe669;</span>不支持退款</div>
 				<div class="ticket-procard-supplier">去哪儿直销</div>
 			</div>
 		</div>
 	</div>
</template>

<script>
	export default {
		data () {
		    return {}
		}
	}
</script>

<style scoped>
    @import "../../assets/font/iconfont.css";
	.iconfont{
		speak: none;
		font-style: normal;
		font-weight: normal;
		font-variant: normal;
		text-transform: none;
		line-height: 1;
		font-size:.22rem;
		margin-right: .05rem;
	}
	.ticket-procard-con{
		position: relative;
		margin-top: -.1rem;
		padding: .2rem .2rem 0 .2rem;
		background: #fff;
		border-radius: .1rem .1rem 0 0;
	}
	.ticket-procard-title{
		padding-bottom: .1rem;
		line-height: .5rem;
		font-size: .36rem;
	}
	.ticket-procard-pricecon{
		line-height: .48rem;
	}
	.ticket-procard-priceicon{
		color: #ff8300;
		font-size: .24rem;
	}
	.ticket-procard-pricetext{
		margin-left: -.06rem;
		color: #ff8300;
		font-size: .48rem;
	}
	.ticket-procard-marketprice{
		color: #9e9e9e;
		font-size: .24rem;
		margin-left: .16rem;
	}
	.ticket-underline{
		text-decoration: line-through;
	}
	.ticket-procard-ul{
		position: relative;
		padding-right: 1.72rem;
		overflow: hidden;
		padding-bottom: .1rem;
		margin-left: -.4rem;
		font-size: .24rem;
		color: #9e9e9e;
	}
	.ticket-procard-li{
		float: left;
		white-space: nowrap;
		margin: .1rem 0;
		margin-left: .4rem;
		font-size: .24rem;
		vertical-align: middle;
	}
	.ticket-procard-supplier{
		overflow: hidden;
		position: absolute;
		top: 0;
		right: 0;
		margin-top: .1rem;
		width: 1.72rem;
		white-space: nowrap;
		text-align: right;
		text-overflow: ellipsis;
	}
</style>

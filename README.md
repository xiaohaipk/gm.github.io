<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,minimum-scale=1.0,user-scalable=no">
		<title>游戏库 | APP下载</title>
		<meta name="description" content="收集、整理和展示游戏软件平台，包含各种类型的游戏，如动作、冒险、角色扮演、体育、模拟、策略等等，玩家可以在其中浏览、搜索、筛选、购买、下载或试玩游戏，可以满足各种类型、主题和级别的玩家需求.">
		<meta name="keywords" content="您最好的游戏库,破解游戏,GM游戏,内购游戏">
		<script src="js/jquery.min.js" type="text/javascript" charset="utf-8"></script>
		<link rel="stylesheet" type="text/css" href="css/index.css" />
		<link rel="stylesheet" type="text/css" href="css/animate.compat.css" />
		<style type="text/css">
		</style>
	</head>
	<body>
		

	</body>
	<script type="text/javascript">
	
		var logo_app = "img/logo.png";//appLogo
		var title_app = "游戏库";//app名称
		var shouji_app = "img/app_sp.png";//电脑端app图片展示
		var banb_app = "版本：2.1.6丨大小：28.6M";//版本信息
		var fabu_app = "发布时间：2023-6-8丨 ssltgm.com";//发布信息
		var dibu_app = "Copyright © All Rights Reserved";//底部版权信息
		var ewm_app = "img/ewm.png";//app下载二维码地址
		var xiaz_app = "https://vip.123pan.cn/1811688083/%E7%9B%B4%E9%93%BE%E6%96%87%E4%BB%B6%E5%A4%B9/GM%E6%B8%B8%E6%88%8F%E5%BA%93.apk";//app下载地址
		var text_app = "收集、整理和展示游戏软件平台，包含各种类型的游戏，如动作、冒险、角色扮演、体育、模拟、策略等等，玩家可以在其中浏览、搜索、筛选、购买、下载或试玩游戏，可以满足各种类型、主题和级别的玩家需求。";//app介绍

				var win_width = $(window).width();
		win_app();
		function win_app(){
			win_width = $(window).width();
			if(win_width<700){
				$("body").html('<div id="boox_web"><div><div class="logo_web"><img src="'+logo_app+'"><p>'+title_app+'</p></div><a href="'+xiaz_app +'"><div class="xiazai_web">立即下载</div></a><div id="banben_web"><p class="text fs">'+banb_app+'</p><p class="text">'+fabu_app+'</p></div></div><div class="fixed_web">'+dibu_app+'</div></div>');
			}else{
				$("body").html('<div id="boox_pc"><div class="left_pc animated bounceInLeft"><img src="'+shouji_app+'"></div><div class="right_pc animated bounceInRight"><div class="right_logo_pc"><img src="'+logo_app+'"><div><p class="right_title_pc">'+title_app+'</p><p class="right_span_pc">您最好的游戏库</p></div></div><div class="right_text_pc">'+text_app+'</div><div class="right_banb_pc">'+banb_app+fabu_app+'</div><div class="right_ewm_pc"><img src="'+ewm_app+'"><a href="'+xiaz_app +'"><div class="right_xiazai_pc">立即下载</div></a></div></div></div>');
			}
		}
		function if_app(){
			if(win_width==$(window).width()){
				
			}else{
				win_app();
				}
		}
		
		setInterval("if_app()",500);
	</script>
	
</html>


<!DOCTYPE html>
<head lang="zh-Hans">
    <meta charset="UTF-8">
	<meta name="renderer" content="webkit" >
    <title>Ikaros的主页</title>
    <script src="js/jquery-2.2.3.min.js"></script>
    <script src="js/jquery-ui.min.js"></script>
    <link type="text/css" href="css/jquery-ui.min.css" rel="stylesheet">
    <!--<script src="zoom.js"></script>-->
    <!--<script src="transition.min.js"></script>-->
    <script src="js/my.js"></script>
    <!--<link href="zoom.css" type="text/css" rel="stylesheet">-->
    <link href="css/my.css" type="text/css" rel="stylesheet">
    <link href="css/reset.min.css" type="text/css" rel="stylesheet">
    <link href="css/style.css" type="text/css" rel="stylesheet">
	<!--
    <link rel="css/stylesheet" type="text/css" href="2d/waifu1.css"/>
    <link rel="css/stylesheet" type="text/css" href="2d/flat-ui.min1.css"/>
	-->
	<link rel="shortcut icon" href="img/logo.png" type="image/x-icon" />
	<link rel="icon" href="img/logo.png" type="image/gif">
	
	<!-- RainEffect -->
	<link rel="stylesheet" type="text/css" href="css/RainEffect/normalize.css" />
	<link rel="stylesheet" type="text/css" href="css/RainEffect/demo.css" />
	<link rel="stylesheet" type="text/css" href="css/RainEffect/style1.css" />
</head>
<body>
	<div class="slideshow">
		<canvas width="1" height="1" id="container" style="position:absolute"></canvas>
	</div>

	<!--<div id="container">-->
	<!--<div style="width: 10px;height: 960px;background-color: #2b2b2b" id="resizable"></div>-->
	<div id="a" style= "border:none">
		<ul id="menu" style= "width:72px;background-color: transparent;border:none">
			<li id="li1" style= "height:72px;border:none"><a href="#"></a></li>
			<li id="li2" style= "height:72px;border:none"><a href="#"></a></li>
			<li id="li3" style= "height:72px;border:none"><a href="#"></a></li>
			<li id="li4" style= "height:72px;border:none"><a href="#"></a></li>
			<li id="li5" style= "height:72px;border:none"><a href="#"></a></li>
			<li id="li6" style= "height:72px;border:none"><a href="#"></a></li>
			<li id="li7" style= "height:72px;border:none"><a href="#"></a></li>
		</ul>
		<div class="box">
			<div class="d1">
			<figure>
				<h10>昵称：伊卡酱&nbsp;&nbsp;性别：男&nbsp;&nbsp;<a href="https://gitee.com/ikaros-521/projects" target="_blank">我的码云</a>&nbsp;&nbsp;&nbsp;<a href="https://ikaros-521.github.io/" target="_blank">我的博客</a><br>爱好：看动漫，做视频&nbsp;&nbsp;<a href="http://space.bilibili.com/3709626" target="_blank">我的b站主页</a>&nbsp;&nbsp;<a href="https://github.com/Ikaros-521" target="_blank">我的GitHub</a></h10>
				<h10>昵称：伊卡酱&nbsp;&nbsp;性别：男&nbsp;&nbsp;<a href="https://gitee.com/ikaros-521/projects" target="_blank">我的码云</a>&nbsp;&nbsp;&nbsp;<a href="https://ikaros-521.github.io/" target="_blank">我的博客</a><br>爱好：看动漫，做视频&nbsp;&nbsp;<a href="http://space.bilibili.com/3709626" target="_blank">我的b站主页</a>&nbsp;&nbsp;<a href="https://github.com/Ikaros-521" target="_blank">我的GitHub</a></h10>
			</figure>
			</div>
			<div class="box1">
				<img id="img2" src="img/2.jpg">
				<img id="img3" src="img/3.jpg">
				<img id="img4" src="img/4.jpg">
				<img id="img6" src="img/5.jpg">
				<img id="img10" src="img/10.jpg">
			</div>
			<div class="d3">
				<audio controls="controls"  autoplay="autoplay" loop="loop">
					<source src="voice/Story-of-Mind.mp3" />
				</audio>
			</div>
			<div id="time">
			</div>
			<div class="d6">
				<a href="http://ikaros-521.gitee.io/js2048" target="_blank"><img id="img2048" src="img/2048.png"></a>
				<a href="http://ikaros-521.gitee.io/h5_3d_magic" target="_blank"><img id="3d_magic" src="img/3d_magic.png"></a>
				<a href="https://ikaros-521.gitee.io/wives/" target="_blank"><img id="wives" src="img/wives.png"></a>
				<a href="https://ikaros-521.gitee.io/the_choice_of_fate" target="_blank"><img id="fate" src="img/fate.png"></a>
				<a href="http://ikaros.xn--ses554g/WebGL/" target="_blank"><img id="WebGL" src="img/WebGL.png"></a>
			</div>
		</div>
	</div>
	<div id="img_eat"  style="opacity:1;">
		<img src="img/eat.gif" id="eat" alt="" style="width: 100px;"/>
	</div>
	<div class="d7">
		<img src="img/zfb.jpg" alt="" style="width: 150px;"/>
		<img src="img/wx.jpg" alt="" style="width: 150px;"/>
	</div>
	<!--
	<div id="layer1" style="position:absolute;left:150px;top:150px;width:150px;height:150px">
	-->
	<div id="layer1" style="position:absolute;zindex=-1" onmouseover="clearInterval(s);this.style.cursor='hand'" onmouseout="s=setInterval('move()',200)">
		<a href="#" id="b">
			<img src="img/动图.png" width="150" height="150">
		</a>
	</div>
	<div id="navbar">
	</div>
	
	<!--
	<div class="waifu">
		<div class="waifu-tips"></div>
		<canvas id="live2d" width="280" height="250" class="live2d"></canvas>
		<div class="waifu-tool">
			<span class="fui-home"></span>
			<span class="fui-chat"></span>
			<span class="fui-eye"></span>
			<span class="fui-user"></span>
			<span class="fui-photo"></span>
			<span class="fui-info-circle"></span>
			<span class="fui-cross"></span>
		</div>
	</div>
	-->

	<div id="SMS">
	</div>
	<!--
	<div id="bottom">
		<div class="footer">
			<span>Copyright © </span><a title="www.ikaros.网址"><span>Ikaros</span></a><span>, All Rights Reserved.</span>
			<span>备案号：<a href="http://beian.miit.gov.cn/" target="_blank" rel="nofollow"><span>浙ICP备20009665号</span></a></span>
		</div>
	</div>
	-->
</body>
<!--
<script src="2d/waifu-tips.js"></script>
<script src="2d/live2d.js"></script>
<script type="text/javascript">initModel()</script>
-->
<script src="js/RainEffect/index.min.js"></script>
</html>

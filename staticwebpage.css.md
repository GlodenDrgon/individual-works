# individual-works
my individual works
body,ul,p,h1,h2,h3,h4,dl,dd,form,input,textarea,select{padding:0;margin: 0;font-family: arial;}
li{list-style: none;}
img{border:none;}
a{text-decoration: none;}
a:hover{text-decoration: underline;}

.clear{zoom:1;}
.clear:after{content:'';display:block;clear:both;}
/*清除浮动 当子级使用浮动 而父级没有使用浮动的时候*/

body{background:#fff url(../img/body_backgroud.png);background-repeat: repeat-x;}

#top{width: 960px;height: 30px;margin:0 auto;}

.top_menu{float:left;}
.top_menu li{float:left;background: url(../img/header_png.png) no-repeat right 13px;
font-size: 13px;line-height: 30px;margin-right:15px;padding-right:13px;} 
.top_menu a{color:#c0c0c0;}
.top_menu a:hover{color: #fff;}
.top_menu .no_dot{background: none;}

.top_bar{float:right;}
.top_bar li{float:left;height: 30px;color: #fff;font-weight: bold;font-size: 13px;line-height: 30px;}
.top_bar .phone{background: url(../img/header_png.png) no-repeat 8px -16px;padding:0 38px;}
.top_bar .help{background: url(../img/header_png.png) no-repeat 0 -46px;padding:0 38px;}
.top_bar a{color:#fff;}

.top_bar .space{margin-right: 20px;}

#header{width: 960px;height: 100px;position: relative;margin: 0 auto;
background: url(../img/header_bg.png) no-repeat;}
#shopping{width:260px;height: 100px;background: url(../img/shop_png.png) no-repeat -15px 0px;
position: relative;}
#shopping p{font-size: 20px;color: #f7f7f7;padding:30px 0 0 84px;}
#shopping a{width: 114px;height: 23px;display: block;background: url(../img/shop_png.png) no-repeat 1px -104px;
position: absolute;top:64px; left:104px;font-size: 12px;color: #ffc200;line-height: 23px;text-align: center;
text-decoration: none;font-weight: bold;}
#shopping a:hover{color: #fbd14a;}
/*有时候少个标点符号就蛋疼*/
#header h1{width: 238px;margin: 0 auto;position: absolute;top:5px;left: 360px;}

.search{width: 292px;height: 31px;background: url(../img/iuput_box.png) no-repeat;position: absolute;}
.search .text{position:absolute;top:0;left:20px;width: 230px;height: 30px;
background: none;border:none;font-size:10px;color:#666;outline: none;}
.search .submit{position:absolute;top:0;right:0;width: 42px;height: 30px;background: none;border:none;height: 30px;}
/*outline去除google下的边框线*/
#header .search{top:34px;right: 0;}

#nav{width: 960px;height: 36px;margin:0 17%;padding-top:8px;}
#nav li{float: left;height: 28px;margin-right: 2px;}
#nav a{float: left;height: 28px;
text-decoration: none;color: #fff;font-size:15px;font-family: arial;line-height: 28px;}
#nav strong{float: left;height: 28px;font-weight: normal;}
#nav span{float: left;height: 28px;
padding: 0 16px 0 16px;}

#nav a:hover,#nav .active a{background: url(../img/nav_active_bg.png) repeat-x 0 -56px;}
#nav a:hover strong,#nav .active strong{background: url(../img/nav_active_bg.png) no-repeat;}
#nav a:hover span,#nav .active span{background: url(../img/nav_active_bg.png) no-repeat right -28px;}

#content{width: 1000px;margin: 24px auto 20px ;background: url(../img/content_bg.gif) repeat-y -1000px 0;}
#content_top{width: 1000px;background:url(../img/content_bg.gif) no-repeat;padding-top: 10px;}
#content_bottom{width: 1000px;background: url(../img/content_bg.gif) no-repeat -2000px bottom;}

#ad{width: 940px;height: 300px;position:relative;margin:0 auto;margin:0 auto;}
#ad ul{position: absolute;top:0;left:0;z-index: 1;}
#ad li{position: absolute;top:0;left:0;}
#ad h2{position: absolute;left:35px;bottom:15px;z-index:3;width:240px;text-align:center;font-size: 18px;font-weight: bold;color:#ffc600;}
#ad p{position: absolute;left:298px;bottom:9px;z-index:3;font-size:10px;line-height: 16px;color:#ffcccc;}
#ad .bg{width:940px;height: 52px;background-color:#000;filter: alpha(opacity:80);opacity: 0.8;position:absolute;bottom:0;left:0;z-index: 2;}
/*层级关系*/

#main{width: 942px;margin: 0 auto;margin-top: 30px;}
#side{width:210px;float:left;}
#wrap{width:706px;float:right;}


.module_menu{margin-bottom: 12px;}
.module_menu h2{height:29px;background: url(../img/content/module_menu.png) repeat-x 0 -29px;font-size: 11px;font-weight:bold;color: #fff;line-height: 29px;text-align: center;}
.module_menu strong{height: 29px;display: block;background: url(../img/content/module_menu.png) no-repeat ;}
.module_menu span{height: 29px;display: block;background: url(../img/content/module_menu.png) no-repeat right -58px;}

.list{background: url(../img/content/list_bg.gif) repeat-y;}
.list ul{background: url(../img/content/list_bg.gif) no-repeat -210px bottom;padding:18px 8px 15px 8px;}
.list li{}
.list a{height: 27px;display:block;font-size: 12px;font-weight:bold;line-height: 27px;color: #434343;text-decoration: none;border-bottom: 1px solid #fff;padding-left:32px;}
.list a:hover{border-bottom:1px solid #b20e00;color:#b20e00;background-color:#f7d872;}

.module_join{width:210px;background: url(../img/content/list_bg.gif) repeat-y -630px 0;}
.module_join_t{background: url(../img/content/list_bg.gif) no-repeat -420px 0;}
.module_join_b{background: url(../img/content/list_bg.gif) no-repeat -840px bottom;}

.Join_form { width:180px; margin:0 auto 12px; }
.Join_form p { font-size:15px; color:#666; line-height:18px; padding:12px 0; }
.Join_form .text { width:175px; height:25px; line-height:25px; background:#fff; border:1px solid #fff; border-top:1px solid #9c9c9c; border-left:1px solid #c0c0c0; margin-bottom:12px; }
.Join_form .btn { width:88px; height:25px; border:none; font-size:15px; color:#fff; font-weight:bold; background:url(../img/content/shop_png.png) no-repeat 0 -145px; margin:0 auto; display:block;cursor: pointer; }

.join_list{width:192px;padding:0 8px;background: url(../img/content/shop_png.png) no-repeat 10px -170px;}
.join_list li{padding-left: 62px;border-top:1px solid #fff;}
.join_list a{font-size: 13px;color:#434343;text-decoration:none;}
.space1{height: 45px;line-height: 45px;}
.space2{height: 38px;padding-top:5px;line-height: 18px;}
.space3{height: 45px;padding-top:5px;line-height: 18px;}
.join_list a:hover{color: #a89b9b;}
/*内部设置宽高还是要减掉padding值*/

#payment{margin:18px 0 0 20px;}

.sort{height:20px;}
/*设置父级高度（在父级允许有高度的情况下）来清除浮动*/
.sort dl{float: left;}
.sort dt{float: left;color:#747474;font-weight:bold;font-size: 12px;padding-right: 3px;line-height: 19px;}
.sort dd{float:left;position:relative;width: 109px;height: 19px;margin-right: 12px;}
.sort h2{width: 107px;height: 17px;line-height:19px;border: 1px solid #ccc;font-size: 12px;color: #747474;
font-weight: normal;text-indent: 5px;}
.sort a{position:absolute;top:0;left:90px;width: 19px;height: 19px;background:url(../img/content/shop_png.png) no-repeat 0 -376px;z-index: 2;}
.sort a:hover{background:url(../img/content/shop_png.png) no-repeat -19px -376px;}
.sort ul{width:108px;position: absolute;top:18px;left:0;border: 1px solid #ccc;background: #fff;z-index: 1;display:none;}
.sort li{font-size:12px;line-height: 20px;text-indent: 5px;}
.sort .active:hover{background:#7a4444;cursor: pointer;color: #fff;}
/*cursor(光标): pointer;*/
.sort p{float: right;color:#747474;font-size:12px;padding-left: 19px;height: 19px;line-height: 19px;}
.sort p strong{color: #999;}
.sort span{padding: 0 5px;}
.sort .color_style{color: #b20e00;}

.pic_list {width: 706px;}
.pic_list h2,#scroll_list h2{height:56px;line-height:62px;fint-size:18px;color: #666;overflow: hidden;}
.pic_list h3{font-size:15px;color:#666;font-weight: bold;}
.pic_list ul{width: 736px;}
.pic_list li{float: left;width: 182px;line-height: 16px;height:200px;}
.pic_list a{display:block;width: 154px;height: 114px;margin-bottom: 6px;}
.pic_list a:hover,{border: 1px solid #663;height: 114px;}
.pic_list span{color:#b20e00;}
.pic_list p{font-size:13px;color:#333;}

.page{text-align: center;border-bottom:1px solid #cdcdc8;padding-bottom:5px;}
.page a{display:inline-block;height: 20px;line-height:20px;color: #b20e00;text-decoration: none;padding:0 8px;font-size: 12px;}
.page a:hover,.page .active{color: #fff;background:#b20e00;}
.page span{font-family: "宋体"; }

.scroll_wrap{height: 196px;background:url(../img/content/scroll_bg.gif) repeat-x 0 -478px;}
.scroll_wrap_l{height:196px;background: url(../img/content/scroll_bg.gif) no-repeat 0 -86px;}
.scroll_wrap_r{height:196px;background: url(../img/content/scroll_bg.gif) no-repeat right -282px;position:relative;}


.prev,.next{width: 35px;height: 43px;position:absolute;top:70px;}

.prev{left:0;background: url(../img/content/scroll_bg.gif) no-repeat ;}
.next{right:0;background: url(../img/content/scroll_bg.gif) no-repeat 0 -43px;}

.list_wrap{width: 615px;height:150px;margin:0 auto;padding-top:32px;}
.list_wrap ul{height: 150px;}
.list_wrap li{width: 205px;float: left;}
.list_wrap a{display:block;height: 100px;}
.list_wrap p{font-size:12px;color: #660000;text-align: center;line-height: 14px;padding-top:20px;}
.list_wrap a,.list_wrap p{width: 145px;margin: 0 auto;}


#footer{background: url(../img/content/footer_bg.png) repeat-x;height: 304px;}
.footer_nav{height:62px ;position: relative;border-bottom: 1px solid #e23a39;}
.footer_nav li a{text-decoration: none;font-size:14px;color:#cbcbcb;}
.footer_nav a:hover{color: #fff;}
.footer_nav li{float:left;}
.footer_l{width: 350px;height: 62px;background: url(../img/content/footer_nav.png) no-repeat left 0;left:270px;top:0;}
.footer_r{width: 310px;height:62px ;background: url(../img/content/footer_nav.png) no-repeat left -62px;left:590px;top:0;}
.footer_l,.footer_r{height:62px;line-height: 62px;text-align: center;position: absolute;}
.footer_nav .search{position:absolute;left: 900px;top:15px;}

.footer_message{width:920px; margin:0 auto; overflow:hidden; padding-top:20px;}
.footer_message dl{float:left;width: 184px;}
.footer_message dt{font-size:15px; color:#fff; font-weight:bold; line-height:50px;}
.footer_message dd{ line-height:20px;}
.footer_message span{color: #ffcc00;}
.footer_message a{font-size:13px; color:#cfcfcf;}
.footer_message .space{padding-top:20px;}
.footer_message .special{position: relative;left: -20px;}

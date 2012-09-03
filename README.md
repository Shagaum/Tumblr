======<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<!-- 
 _ _ _ _    _ _   _ _ _   _ _   _ _  _ _ _   _ _ _ _    _ _       _ _ _ _
|   _   |  |   | |     | |   |/   / |     | |   _   |  |   |     |   _   |
|  |_|  |  |   | |    _| |   |   /  |   _ | |  |_|  |  |   |     |  |_|  |
|      -   |   | |  | _  |      -   |   _|  |      -   |   | _   |      -
|   |   \  |   | |     | |   |   \  |     | |   |   \  |       | |   |   \
|_ _|\_ _\ |_ _| |_ _ _| |_ _|\_ _\ |_ _ _| |_ _|\_ _\ |_ _ _ _| |_ _|\_ _\
    
    
********************************
Theme by: rickerlr.tumblr.com
On: www.themecloud.co
Name: LIGHTGLASS
Year: 2012
********************************
-->

<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">

<meta name="color:Background" content="#f5f5f5"/>
<meta name="color:Border Note Permalinks" content="#f5f5f5"/>
<meta name="color:Box Shadow Color" content="#e5e5e5"/>
<meta name="color:Link" content="#000000"/>
<meta name="color:Link active" content="#222222"/>
<meta name="color:Link hover" content="#444444"/>
<meta name="color:Link menu" content="#888888"/>
<meta name="color:Notes" content="#bbbbbb"/>
<meta name="color:Opacity Color Photo Effect" content="#000000"/>
<meta name="color:Post Background" content="#fbfbfb"/>
<meta name="color:Text" content="#777777"/>
<meta name="color:Text Description" content="#777777"/>
<meta name="color:Title" content="#444444"/>
<meta name="color:Title Header" content="#333333"/>

<meta name="image:Background image" content="http://static.tumblr.com/dbek3sy/noXm2qa7z/body_bg.jpg" />
<meta name="image:Header Image" content="" />

<!-- columns number -->
<meta name="if:1 Column" content="1"/>
<meta name="if:2 Columns" content="0"/>
<meta name="if:3 Columns" content="0"/>
<meta name="if:4 Columns" content="0"/>
<meta name="if:5 Columns" content="0"/>

<meta name="if:Border Rounded" content="0"/>
<meta name="if:Box Shadow" content="1"/>
<meta name="if:Container FadeIn" content="0"/>

<!-- fonts -->
<meta name="if:Font Francois One" content="0"/>
<meta name="if:Font Gochi Hand" content="0"/>
<meta name="if:Font Indie Flower" content="0"/>
<meta name="if:Font Leckerli One" content="0"/>
<meta name="if:Font Lilita One" content="0"/>
<meta name="if:Font Lobster" content="0"/>
<meta name="if:Font Mrs Sheppards" content="0"/>
<meta name="if:Font Oleo Script" content="0"/>
<meta name="if:Font Open Sans Condensed" content="0"/>
<meta name="if:Font Oswald" content="1"/>

<meta name="if:Hide Description" content="0"/>
<meta name="if:Infinite Scroll" content="1"/>
<meta name="if:Post Padding" content="0"/>
<meta name="if:Show Archive Link" content="1"/>
<meta name="if:Show Captions" content="0"/>
<meta name="if:Show Notes Permalink" content="0"/>
<meta name="if:Show RSS Link" content="0"/>
<meta name="if:Show Social" content="1"/>
<meta name="if:Tumblr Buttons Fixed" content="0"/>
<meta name="if:Tumblr Buttons Opacity" content="0"/>

<meta name="text:Back Top" content="Back to top" />
<meta name="text:Footer Text" content="" />
<meta name="text:Google Analytics ID" content="" />
<meta name="text:Link 1 title" content="" />
<meta name="text:Link 1 url" content="" />
<meta name="text:Link 2 title" content="" />
<meta name="text:Link 2 url" content="" />
<meta name="text:Link 3 title" content="" />
<meta name="text:Link 3 url" content="" />
<meta name="text:Link 4 title" content="" />
<meta name="text:Link 4 url" content="" />
<meta name="text:Link 5 title" content="" />
<meta name="text:Link 5 url" content="" />
<meta name="text:Link 6 title" content="" />
<meta name="text:Link 6 url" content="" />
<meta name="text:Page Text" content="Pages" />

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>{Title}{block:SearchPage}, {lang:Search results for SearchQuery}{/block:SearchPage}{block:PostSummary}, {PostSummary}{/block:PostSummary}</title>
{block:Description}<meta name="description" content="{MetaDescription}" />{/block:Description}
<link rel="shortcut icon" href="{Favicon}" />
<link rel="apple-touch-icon" href="{PortraitURL-128}"/>
<link rel="alternate" type="application/rss+xml" href="{RSS}" />

<link href='http://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Oswald' rel='stylesheet' type='text/css'>

<link href='http://fonts.googleapis.com/css?family=Lilita+One|Oleo+Script|Lobster|Gochi+Hand|Mrs+Sheppards|Open+Sans+Condensed:700|Leckerli+One|Francois+One|Indie+Flower' rel='stylesheet' type='text/css'>

<!-- Lightglass css code -->
<style>
/* CSS RESET */

html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,dd,dl,dt,li,ol,ul,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td{margin:0;padding:0;border:0;}table{border-collapse:collapse;border-spacing:0;}ol,ul{list-style:none;list-style-type: none;}q:before,q:after,blockquote:before,blockquote:after{content:"";}



*{

outline: none;

-moz-outline: none;

}



blockquote{    padding-left:10px;border-left:3px solid {color:Border Note Permalinks};margin:5px 0px 5px 0px;}

li{list-style-type: circle;margin-left: 15px;}

ul.titleLinks li, ul.bottomLinks li, ul.chat li, .note, .like{list-style-type: none;margin:0px;}

ol.notes{text-align: left;}

.note, .like{

    {block:IfNotShowNotesPermalink}margin: 5px 0px;{/block:IfNotShowNotesPermalink}

  {block:IfShowNotesPermalink}margin: 10px 0px;{/block:IfShowNotesPermalink}

}

ol.notes li .avatar {

	width:18px;

	height:18px;

	vertical-align: middle;

	{block:IfShowNotesPermalink}margin-right: 5px;{/block:IfShowNotesPermalink}

}



{block:IfNotShowNotesPermalink}

.note, .like{float:left;margin:5px 5px 0px 0px;line-height: 16px;}

.action, .note blockquote, .like blockquote{display:none;}

.more_notes_link_container{padding:0px !important;}

.action a{color: #fff !important;}

.note, .like{z-index:10;}

.note:hover, .like:hover{position:relative;z-index:100;}    		

.note:hover .action, .like:hover .action{

	display: block;

	position:absolute;

	float:left;

	white-space:nowrap;

	top:-2.2em;

	left:.5em;

	background:#000;

	color:#fff;

	padding: 1px 5px;

	z-index:10;

}

{/block:IfNotShowNotesPermalink}



h1,h2,h3,h4,h5,h6{font-weight: bold;}

.right{float: right;} .left{float: left;} .clear {clear: both;}



a:link, a:visited{color:{color:Link};}

a{

	text-decoration:none;

	opacity: 1;

	filter:alpha(opacity=100);

	-webkit-transition: opacity 0.5s ease, color 0.5s ease;

	-moz-transition: opacity 0.5s ease, color 0.5s ease;

	transition: opacity 0.5s ease, color 0.5s ease;

	-o-transition: opacity 0.5s ease, color 0.5s ease;

}

a:hover {

	color:{color:Link hover};

	opacity: 0.75;

	filter:alpha(opacity=75);

}

a:active {color:{color:Link active};}



#tumblr_controls{

	{block:IfTumblrButtonsFixed}

		position:fixed !important;

	{/block:IfTumblrButtonsFixed}

	

	{block:IfTumblrButtonsOpacity}

		opacity: 0.3;

		filter:alpha(opacity=30);

	{/block:IfTumblrButtonsOpacity}

	

	-webkit-transition: all 0.5s ease-out;

	-moz-transition: all 0.5s ease-out;

	transition: all 0.5s ease-out;

	-o-transition: all 0.5s ease-out;

}



{block:IfTumblrButtonsOpacity}

	#tumblr_controls:hover{

		opacity: 1;

		filter:alpha(opacity=100);

	}

{/block:IfTumblrButtonsOpacity}



body{

	font-size:100%;

	color: {color:Text};

	font-family: 'Open Sans', sans-serif;

	text-align: center;

	word-wrap: break-word;

	background-color: {color:Background};

	background-image: url({image:Background image});

	background-repeat: repeat;

	background-attachment: fixed;

	background-position: top left;

}

#container{

	{block:IndexPage}

		/*1 columns */

			{block:If1Column}width: 520px;{/block:If1Column}

		

		/*2 columns */

			{block:If2Columns}width: 840px;{/block:If2Columns}

			

		/*3 columns */

			{block:If3Columns}width: 870px;{/block:If3Columns}

			

		/*4 columns */

			{block:If4Columns}width: 1040px;{/block:If4Columns}

			

		/*5 columns */

			{block:If5Columns}width: 1300px;{/block:If5Columns}

		

	{/block:IndexPage}



	position: relative;

	text-align: left;

	height: 100%;

	margin: 0px auto;

	z-index:0;

	{block:IfContainerFadeIn}

		display:none;

	{/block:IfContainerFadeIn}

	{block:IfInfiniteScroll}

		{block:IndexPage}

			min-height: 800px;

			height: auto !important;

			height: 800px;

		{/block:IndexPage}

	{/block:IfInfiniteScroll}

}



#header{

	max-width: 1280px;

	width:expression(document.body.clientWidth > 940? "940px": "auto" );

	text-align:center;

	margin: 0px auto;

}



#header h1{

	margin-top:20px;

	font-size: 2em;

	text-align:center;

	

	{block:IfFontFrancoisOne}font-family: 'Francois One', sans-serif;{/block:IfFontFrancoisOne}

	{block:IfFontGochiHand}font-family: 'Gochi Hand', cursive;{/block:IfFontGochiHand}

	{block:IfFontIndieFlower}font-family: 'Indie Flower', cursive;{/block:IfFontIndieFlower}

	{block:IfFontLeckerliOne}font-family: 'Leckerli One', cursive;{/block:IfFontLeckerliOne}	

	{block:IfFontLilitaOne}font-family: 'Lilita One', cursive;{/block:IfFontLilitaOne}	

	{block:IfFontLobster}font-family: 'Lobster', cursive;{/block:IfFontLobster}		

	{block:IfFontMrsSheppards}font-family: 'Mrs Sheppards', cursive;{/block:IfFontMrsSheppards}

	{block:IfFontOleoScript}font-family: 'Oleo Script', cursive;{/block:IfFontOleoScript}

	{block:IfFontOpenSansCondensed}font-family: 'Open Sans Condensed', sans-serif;{/block:IfFontOpenSansCondensed}

	{block:IfFontOswald}font-family: 'Oswald', sans-serif;{/block:IfFontOswald}

	

	font-weight: normal !important;

	cursor: pointer;

	color:{color:Title Header};

}

#header h1 a{text-decoration: none;color:{color:Title Header};}



#head_description{

	font-size:0.7em;

	margin: 4px 0 10px;

    color:{color:Text Description};

	{block:IfHideDescription}

		display:none;

	{/block:IfHideDescription}

}

#head_description a{color:{color:Link menu};}



#imagetitle{

	margin-top:10px;

	max-width:940px;

	width:expression(document.body.clientWidth > 940? "940px": "auto" );

	cursor: pointer;

}



#content{

	margin:-10px auto;

	position:relative;

	padding-bottom:20px;

	

	{block:PermalinkPage}

		{block:IfNotShowNotesPermalink}width: 880px;{/block:IfNotShowNotesPermalink}

		{block:IfShowNotesPermalink}width: 520px;{/block:IfShowNotesPermalink}

	{/block:PermalinkPage}

}



ul#titlePages{display:none}



ul.titleLinks{

	margin:10px 0px;

	font-size: 0.6em;

	text-transform: uppercase;

}

ul.titleLinks li{display: inline;margin-left: 25px;}

ul.titleLinks li:first-child{margin-left: 0px;}

ul.titleLinks a, ul.bottomLinks a{

	color:{color:Link menu};

	text-decoration:none;

}



ul.bottomLinks{

    font-size:0.8em;

	text-transform: uppercase;

	padding-bottom: 5px;

	margin-bottom: 5px;

	border-bottom: 1px solid {color:Border Note Permalinks};

}

ul.bottomLinks li{

	text-align: right;

	margin-top:5px;

}



.posts{

	overflow: hidden;

	position:relative;

	margin: 20px 10px 0px;

	background-color: {color:Post Background};

	z-index:9000;

	

	{block:PermalinkPage}

		width:520px;

		float:left;

	{/block:PermalinkPage}

	{block:IndexPage}

		float: left;

	{/block:IndexPage}

	{block:IfBoxShadow}

		box-shadow: 0px 0px 3px {color:Box Shadow Color};

	{/block:IfBoxShadow}

}

{block:IndexPage}

.posts, .opacityColorPhotoEffect{

	width: 145px;

	

		/*1 columns */

			{block:If1Column}width: 500px !important;{/block:If1Column}

		

		/*2 columns */

			{block:If2Columns}width: 400px !important;{/block:If2Columns}

			

		/*3 columns */

			{block:If3Columns}width: 270px !important;{/block:If3Columns}

			

		/*4 columns */

			{block:If4Columns}width: 240px !important;{/block:If4Columns}

			

		/*5 columns */

			{block:If5Columns}width: 240px !important;{/block:If5Columns}

}

{/block:IndexPage}

{block:IfBorderRounded}

	.posts, img.photo, .opacityColorPhotoEffect, .albumArt_img_index, .odd, #zoomPost_content, .audioimage{

		-webkit-border-radius: 3px;

		-moz-border-radius: 3px;

		border-radius: 3px;

	}

{/block:IfBorderRounded}



img.photo{

	{block:IndexPage}

		{block:IfPostPadding}

		

		width: 125px;

			

		/*1 columns */

			{block:If1Column}width: 480px !important;{/block:If1Column}

		

		/*2 columns */

			{block:If2Columns}width: 380px !important;{/block:If2Columns}

			

		/*3 columns */

			{block:If3Columns}width: 250px !important;{/block:If3Columns}

			

		/*4 columns */

			{block:If4Columns}width: 220px !important;{/block:If4Columns}

			

		/*5 columns */

			{block:If5Columns}width: 220px !important;{/block:If5Columns}



			margin-bottom: -5px !important;

		{/block:IfPostPadding}

		{block:IfNotPostPadding}

			margin-top: -10px;

			margin-left: -10px;

		{/block:IfNotPostPadding}

		{block:IfShowCaptions}

			margin-bottom: -5px;

		{/block:IfShowCaptions}

		{block:IfNotShowCaptions}

			margin-bottom: -15px;

		{/block:IfNotShowCaptions}

	{/block:IndexPage}

	{block:PermalinkPage}

		margin-bottom: -5px;

	{/block:PermalinkPage}

}





.photosetPost{

	text-align:center;

	{block:IndexPage}

		margin-top: -10px;

		margin-left:-10px;

		margin-bottom: -15px;

		{block:If3Columns}

			{block:IfNot4Columns}

				{block:IfNot5Columns}

					margin-top: 0px;

					margin-left: 0px;

					margin-bottom: -5px;

				{/block:IfNot5Columns}

			{/block:IfNot4Columns}

		{/block:If3Columns}

	{/block:IndexPage}

}





.videoPost iframe, .video_player{

	

	{block:IfPostPadding}

		width: 125px;

		margin-bottom: -5px;

	

		/*1 columns */

			{block:If1Column}width: 480px !important;{/block:If1Column}

		

		/*2 columns */

			{block:If2Columns}width: 380px !important;{/block:If2Columns}

			

		/*3 columns */

			{block:If3Columns}width: 250px !important;{/block:If3Columns}

			

		/*4 columns */

			{block:If4Columns}width: 220px !important;{/block:If4Columns}

			

		/*5 columns */

			{block:If5Columns}width: 220px !important;{/block:If5Columns}

	{block:IfPostPadding}

	{block:IndexPage}

	{block:IfNotPostPadding}

		margin-top: -10px;

		margin-left: -10px;

		margin-bottom: -15px;

		

			width:145px;

		/*1 columns */

			{block:If1Column}width: 500px !important;{/block:If1Column}

		

		/*2 columns */

			{block:If2Columns}width: 400px !important;{/block:If2Columns}

			

		/*3 columns */

			{block:If3Columns}width: 270px !important;{/block:If3Columns}

			

		/*4 columns */

			{block:If4Columns}width: 240px !important;{/block:If4Columns}

			

		/*5 columns */

			{block:If5Columns}width: 240px !important;{/block:If5Columns}

	{block:IfNotPostPadding}

	{block:IndexPage}

	{block:PermalinkPage}

		width: 500px !important;

	{/block:PermalinkPage}

}



#footer{

	font-size: 0.6em;

	{block:IfInfiniteScroll}margin: 30px auto 50px;{block:IfInfiniteScroll}

	{block:IfNotInfiniteScroll}margin: 10px auto 50px;{block:IfNotInfiniteScroll}

	padding-top: 5px;

	width: 500px;

	border-top: 1px solid {color:Border Note Permalinks};

   color:{color:Text Description};

}

#footer a{text-decoration: none;color:{color:Link menu};}



.chat li.odd, .chat li.even{padding:5px;line-height:1em;}

.chat li.odd{color:{color:Title};background-color:{color:Border Note Permalinks};}

.chat li.even{color:{color:Link};margin:5px 0px}

.title{font-size:0.9em;color:{color:Title};}

.title a{color:{color:Title};text-decoration:none;}

.caption{font-size:0.7em;margin-left:3px;line-height:1.3em;margin-top:5px;text-align:left;}

.caption ul{margin-top: 5px;}

.label{font-weight:bold;font-size:1em}

.asker{color:{color:Link};font-weight:bold;text-decoration:none;}

.quest{

	font-size:0.7em;

	{block:PermalinkPage}

	width: 460px;

	{/block:PermalinkPage}

	{block:IndexPage}

		width: 145px;

		/*1 columns */

			{block:If1Column}width: 440px !important;{/block:If1Column}

		

		/*2 columns */

			{block:If2Columns}width: 360px !important;{/block:If2Columns}

			

		/*3 columns */

			{block:If3Columns}width: 210px !important;{/block:If3Columns}

			

		/*4 columns */

			{block:If4Columns}width: 180px !important;{/block:If4Columns}

			

		/*5 columns */

			{block:If5Columns}width: 180px !important;{/block:If5Columns}

	{block:IndexPage}

}

.askAnswer , .answer_form_container{margin-top:10px;}

.audiotrack{width: 207px;}

.audiotrack li{margin: 5px 0px 0px;font-size: 0.7em;list-style-type: none;}

.audiotrack li:first-child{margin-top: 0px;}



.album_art{

	height:151px;

	width: 193px;

	margin-right: 30px;

	background: url('http://static.tumblr.com/dbek3sy/jG9lswgfn/audio_cover.png') no-repeat -150px 0px;

	position: relative;

} 

.effectalbumart{

	height: 150px;

	width: 150px;

	position: absolute;

	top: 0px;

	left: 0px;

	background: url(http://static.tumblr.com/dbek3sy/L7vlsqr0w/audio_cover.png) no-repeat 0px 0px;

	z-index: 5000;

}

{block:IndexPage}

	.audioplayercontainer{

		{block:IfNotPostPadding}

			height:125px;

			

			/*1 columns */

				{block:If1Column}height: 480px !important;{/block:If1Column}

			

			/*2 columns */

				{block:If2Columns}height: 380px !important;{/block:If2Columns}

				

			/*3 columns */

				{block:If3Columns}height: 250px !important;{/block:If3Columns}

				

			/*4 columns */

				{block:If4Columns}height: 220px !important;{/block:If4Columns}

				

			/*5 columns */

				{block:If5Columns}height: 220px !important;{/block:If5Columns}

		{block:IfNotPostPadding}

		{block:IfPostPadding}

			height: 125px;

		

			/*1 columns */

				{block:If1Column}height: 480px !important;{/block:If1Column}

			

			/*2 columns */

				{block:If2Columns}height: 380px !important;{/block:If2Columns}

				

			/*3 columns */

				{block:If3Columns}height: 250px !important;{/block:If3Columns}

				

			/*4 columns */

				{block:If4Columns}height: 220px !important;{/block:If4Columns}

				

			/*5 columns */

				{block:If5Columns}height: 220px !important;{/block:If5Columns}

		{block:IfPostPadding}

	}

	

	.audioplayerout{

		position: absolute;

		background-color: #000;

		-webkit-border-radius: 50px;

		-moz-border-radius: 50px;

		border-radius: 50px;

		left: 50%;

		margin-left: -30px;

		top: 50%;

		margin-top: -30px;

	}

	.audioplayerinto{

		width: 20px;

		height: 30px;

		overflow: hidden;

		margin: 17px 24px 13px 16px;

	}

	.audioimage{

		background: {color:Border Note Permalinks};

		position: absolute;

		z-index: -1;

		{block:IfNotPostPadding}

			top: 0px;

			left: 0px;

			width:145px;

			

			/*1 columns */

				{block:If1Column}width: 500px !important;{/block:If1Column}

			

			/*2 columns */

				{block:If2Columns}width: 400px !important;{/block:If2Columns}

				

			/*3 columns */

				{block:If3Columns}width: 270px !important;{/block:If3Columns}

				

			/*4 columns */

				{block:If4Columns}width: 240px !important;{/block:If4Columns}

				

			/*5 columns */

				{block:If5Columns}width: 240px !important;{/block:If5Columns}

		{/block:IfNotPostPadding}

		{block:IfPostPadding}

			top: 10px;

			left: 10px;

			width: 125px;

			margin-bottom: -5px;

		

			/*1 columns */

				{block:If1Column}width: 480px !important;{/block:If1Column}

			

			/*2 columns */

				{block:If2Columns}width: 380px !important;{/block:If2Columns}

				

			/*3 columns */

				{block:If3Columns}width: 250px !important;{/block:If3Columns}

				

			/*4 columns */

				{block:If4Columns}width: 220px !important;{/block:If4Columns}

				

			/*5 columns */

				{block:If5Columns}width: 220px !important;{/block:If5Columns}

		{/block:IfPostPadding}

	}

	.noteAudio{

		padding:3px 6px;

		position:absolute;

		{block:IfNotPostPadding}

			bottom: 10px;

			right: 10px;

		{/block:IfNotPostPadding}

		{block:IfPostPadding}

			bottom: 15px;

			right: 15px;

		{/block:IfPostPadding}

		z-index: 10;

		background: {color:Post Background};

		opacity: 0;

		filter:alpha(opacity=0);

		font-size: 0.7em;

		

		-webkit-transition: opacity 0.3s ease;

		-moz-transition: opacity 0.3s ease;

		transition: opacity 0.3s ease;

		-o-transition: opacity 0.3s ease;

	}

	.noteAudio a{margin-left:5px;color:{color:Notes};}

	

	.audioplayercontainer:hover .noteAudio{

		opacity: 1;

		filter:alpha(opacity=100);

	}

	

{/block:IndexPage}





.link{text-decoration:underline !important;}



.postnotesdiv{

	font-size:0.7em;

	text-align:left;

	padding: 10px;

}



.countNote_pagePosts{

	margin: 5px 0px;

	border-bottom: 1px solid {color:Border Note Permalinks};

	padding: 5px 0px;

}





#pagination{

	{block:IfInfiniteScroll}

	display:none;

	{/block:IfInfiniteScroll}

	margin-top:20px;

}





#pagination li{

    display: inline-block;

    font-size: 0.7em;

    line-height: 35px;

    background-color: {color:Post Background};

    margin-left:10px;

    {block:IfBoxShadow}

        box-shadow: 0px 0px 2px {color:Box Shadow Color};

    {/block:IfBoxShadow}

}

#pagination li:first-child{margin-left: 0px;}



#pagination a{text-decoration:none;color: {color:Link};padding: 1px 15px;}

.current_page{color: {color:Text}}

.current_page{padding: 1px 15px;}



.sociallike{

	margin-top:10px;

	padding-top: 10px;

	border-top:1px solid {color:Border Note Permalinks};

}



.install:hover , .preview:hover{

    opacity:0.7;

    filter:alpha(opacity=70);

}



.opacityColorPhotoEffect{

	position:absolute;

	height:100%;

	background: {color:Opacity Color Photo Effect};

	top:0px;

	left:0px;

	z-index: 9998;

	opacity:0;

	filter:alpha(opacity=0);

	

	-webkit-transition: opacity 0.3s ease;

	-moz-transition: opacity 0.3s ease;

	transition: opacity 0.3s ease;

	-o-transition: opacity 0.3s ease;

}



.descriprion_icons{

	position: absolute;

	display: block;

	width: 25px;

	height: 25px;

	left: 50%;

	top: 65%;

	margin-top: -12px;

	background: url(http://static.tumblr.com/dbek3sy/Oufm2q70l/lightglass_icons.png) no-repeat;

	opacity:0;

	filter:alpha(opacity=0);

	z-index: 9999;

}

.reblog_icon{

	background-position: 0px 0px;margin-left: -60px;

	-webkit-transition: all 0.25s ease;

	-moz-transition: all 0.25s ease;

	transition: all 0.25s ease;

	-o-transition: all 0.25s ease;

}

.permalink_icon{

	background-position: -25px 0px;margin-left: -30px;

	-webkit-transition: all 0.45s ease;

	-moz-transition: all 0.45s ease;

	transition: all 0.45s ease;

	-o-transition: all 0.45s ease;

}

.zoom_icon{

	background-position: -50px 0px;margin-left: 0px;

	-webkit-transition: all 0.6s ease;

	-moz-transition: all 0.6s ease;

	transition: all 0.6s ease;

	-o-transition: all 0.6s ease;

}

.heart_icon{

	background-position: -75px 0px;margin-left: 30px;

	-webkit-transition: all 0.8s ease;

	-moz-transition: all 0.8s ease;

	transition: all 0.8s ease;

	-o-transition: all 0.8s ease;

}

.posts:hover .opacityColorPhotoEffect{opacity:0.4;filter:alpha(opacity=40);}

.posts:hover .descriprion_icons{top: 50%;opacity:1;filter:alpha(opacity=100);}



.description_posts{

	margin-top: 10px;

	font-size:0.6em;

	border-top: 1px solid {color:Border Note Permalinks};

	padding-top: 5px;text-align:center;

}



.description_posts a{text-decoration: none;color: {color:Notes};margin-left:10px;}

.description_posts a:hover, #zoomPost_content a:hover, .noteAudio a:hover{color: {color:Link};}

.description_posts a:first-child{margin-left: 0px;}



#postPageUl{

	{block:IfNotShowNotesPermalink}text-align:left;{/block:IfNotShowNotesPermalink}

	{block:IfShowNotesPermalink}text-align:center;{/block:IfShowNotesPermalink}

}

#postPageUl li{

	margin-left: 0px;

	list-style-type: none;

	margin-bottom: 5px;

}



#infscr-loading{

	bottom: -60px;

	position: absolute;

	left: 50%;

	margin-left:-8px;

	width:16px;

	height:20px;

	overflow:hidden;

	margin-bottom: 50px;

}



.atag{margin-right:7px;}



#zoomPost{

	display:none;

	width:100%;

	height:100%;

	position:fixed;

	top:0px;

	left:0px;

	z-index:9990;

}



#zoomPost_content{

	position: absolute;

	left: 50%;

	top: -300px;

	opacity: 0;

	margin-left: -260px;

	width: 520px;

	z-index:9992;

	background-color: {color:Post Background};

	box-shadow: 0px 0px 3px rgba(0,0,0,0.6);

	font-size:0.7em;

	

}

#zoomPost_content a{

	margin-right:10px;

	color: {color:Notes};

}



#zoomPost_background{

	width: 100%;

	height: 100%;

	background: #000;

	opacity: 0.7;

	filter:alpha(opacity=70);

	z-index:9991;

}



#closeZoom{

	width:15px;

	height:15px;

	position:absolute;

	top:0px;

	right:-25px;

	background: url(http://static.tumblr.com/dbek3sy/0HDm2tn21/closezoomx.png) no-repeat;

	cursor: pointer;

}



#videoZoom{

	margin-bottom: 5px;

	border:0px;

	overflow:0px;

	width:500px;

	min-height:300px;

	height:auto !important; 

	height: 300px;

	display:none;

}



#topDiv{

	position: fixed;

	bottom: 20px;

	right: 10px;

	z-index: 9999;

	display: none;

	font-size: 0.7em;

	cursor: pointer;

	color: {color:Text};

}



#topDivA{text-transform:uppercase;}
</style>

<style type="text/css" media="screen">{CustomCSS}</style>


<meta http-equiv="x-dns-prefetch-control" content="off"/><meta http-equiv="x-dns-prefetch-control" content="off"/><meta http-equiv="x-dns-prefetch-control" content="off"/>

<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-31700230-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>    
</head>
<body>


<div style="position:fixed;right:2px;top:25px;z-index:9999;">
<a href="http://www.themecloud.co/lightglass-tumblr-theme.asp" target="_blank">
<img class="normal" src="http://static.tumblr.com/dbek3sy/zESllc4x6/install_theme.png" alt="install theme" />
</a>
</div>


<div id="container">
<div id="header">

	<div id="nameBlog">
		{block:IfHeaderImageImage}
			<img id="imagetitle" src="{image:Header Image}">
		{/block:IfHeaderImageImage}
		
		{block:IfNotHeaderImageImage}
			<h1>{Title}</h1>
		{/block:IfNotHeaderImageImage}
	</div>

	<div id="head_description">{Description}</div>
	
	
	<ul class="titleLinks">
		<li><a href="/">Home</a></li>
		{block:AskEnabled}
			<li><a href="/ask" >{AskLabel}</a></li>
		{/block:AskEnabled}
		{block:IfShowRSSLink}
			<li><a href="/rss" >Rss</a></li>
		{block:IfShowRSSLink}
		{block:IfShowArchiveLink}
			<li><a href="/archive" >Archive</a></li>
		{block:IfShowArchiveLink}
		{block:IfLink1title}
			<li><a href="{text:Link 1 url}" >{text:Link 1 title}</a></li>
		{/block:IfLink1title}
		{block:IfLink2title}
			<li><a href="{text:Link 2 url}" >{text:Link 2 title}</a></li>
		{/block:IfLink2title}
		{block:IfLink3title}
			<li><a href="{text:Link 3 url}" >{text:Link 3 title}</a></li>
		{/block:IfLink3title}
		{block:IfLink4title}
			<li><a href="{text:Link 4 url}" >{text:Link 4 title}</a></li>
		{/block:IfLink4title}
		{block:IfLink5title}
			<li><a href="{text:Link 5 url}" >{text:Link 5 title}</a></li>
		{/block:IfLink5title}
		{block:IfLink6title}
			<li><a href="{text:Link 6 url}" >{text:Link 6 title}</a></li>
		{/block:IfLink6title}
        {block:HasPages} 
           <li><a id="pageLink" href="javascript:void(0)">{text:Page Text}</a></li>
        {/block:HasPages}
	</ul>
    <ul id="titlePages" class="titleLinks">
        {block:HasPages} 
    		{block:Pages} 
				<li><a href="{URL}" >{Label}</a></li>
			{/block:Pages}
		{/block:HasPages}
    </ul>

</div>



<div id="content">
{block:Posts}
<div class="posts" id="post_{PostID}">
<div style="padding:10px;">


{block:Text}
	{block:Title}
		<h3 class="title">{Title}</h3>
	{/block:Title}
	<div class="caption">{Body}</div>
	{block:IndexPage}
		{block:Date}
			<div class="description_posts">
				<a href="{Permalink}">{TimeAgo}</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		{/block:Date}
	{/block:IndexPage}
{/block:Text}


{block:Link}
	<h3 class="title"><a href="{URL}" class="link title" {Target}>{Name}</a></h3>
	{block:Description}
		<div class="caption">{Description}</div>
	{/block:Description}
	{block:IndexPage}
		{block:Date}
			<div class="description_posts">
				<a href="{Permalink}">{TimeAgo}</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		{/block:Date}
	{/block:IndexPage}
{block:Link}


{block:Photo}
	{block:IndexPage}
		<!-- without columns -->
			{block:IfNot1Column}
				{block:IfNot2Columns}
					{block:IfNot3Columns}
						{block:IfNot4Columns}
							{block:IfNot5Columns}
								<img class="photo" src="{PhotoURL-250}" alt="{PhotoAlt}" width="145"/>
							{/block:IfNot5Columns}
						{/block:IfNot4Columns}
					{/block:IfNot3Columns}
				{/block:IfNot2Columns}
			{/block:IfNot1Column}
	
		<!-- 1 columns -->
			{block:If1Column}
				{block:IfNot2Columns}
					{block:IfNot3Columns}
						{block:IfNot4Columns}
							{block:IfNot5Columns}
								<img class="photo" src="{PhotoURL-500}" alt="{PhotoAlt}" width="500"/>
							{/block:IfNot5Columns}
						{/block:IfNot4Columns}
					{/block:IfNot3Columns}
				{/block:IfNot2Columns}
			{/block:If1Column}
		
		<!-- 2 columns -->
			{block:If2Columns}
				{block:IfNot3Columns}
					{block:IfNot4Columns}
						{block:IfNot5Columns}
							<img class="photo" src="{PhotoURL-400}" alt="{PhotoAlt}" width="400"/>
						{/block:IfNot5Columns}
					{/block:IfNot4Columns}
				{/block:IfNot3Columns}
			{/block:If2Columns}
			
		<!-- 3 columns -->
			{block:If3Columns}
				{block:IfNot4Columns}
					{block:IfNot5Columns}
						<img class="photo" src="{PhotoURL-250}" alt="{PhotoAlt}" width="270"/>
					{/block:IfNot5Columns}
				{/block:IfNot4Columns}
			{/block:If3Columns}
			
		<!-- 4 columns -->
			{block:If4Columns}
				{block:IfNot5Columns}
					<img class="photo" src="{PhotoURL-250}" alt="{PhotoAlt}" width="240"/>
				{/block:IfNot5Columns}
			{/block:If4Columns}
			
		<!-- 5 columns -->
			{block:If5Columns}
				<img class="photo" src="{PhotoURL-250}" alt="{PhotoAlt}" width="240"/>
			{/block:If5Columns}
	
	
		{block:IfShowCaptions}
			{block:Caption}
				<div class="caption">{Caption}</div>
			{/block:Caption}
			{block:Date}
				<div class="description_posts">
					<a href="{Permalink}">{TimeAgo}</a>
					<a href="{Permalink}">{NoteCountWithLabel}</a>
					<a href="{ReblogURL}" target="_blank">Reblog</a>
					<a href="javascript:void(0);" class="zoom_icon" id="{PhotoURL-500}" rel="photoZOOM">Zoom</a>
				</div>
			{/block:Date}
		{/block:IfShowCaptions}
		{block:IfNotShowCaptions}
			<a href="{Permalink}" class="descriprion_icons permalink_icon"></a>
			<a href="{ReblogURL}" target="_blank" class="descriprion_icons reblog_icon"></a>
			<a href="javascript:void(0);" class="descriprion_icons zoom_icon" rel="photoZOOM" id="{PhotoURL-500}"></a>
			<a class="descriprion_icons heart_icon" href="javascript:void(0);" id="{PostID}" rel="{ReblogURL}"></a>
			<div class="opacityColorPhotoEffect"></div>
		{/block:IfNotShowCaptions}
	{/block:IndexPage}
	{block:PermalinkPage}
		<img class="photo" src="{PhotoURL-500}" alt="{PhotoAlt}" width="500"/>
		{block:Caption}
			<div class="caption">{Caption}</div>
		{/block:Caption}
	{/block:PermalinkPage}
{/block:Photo}


{block:Photoset}
	{block:IndexPage}
		<!-- without columns -->
			{block:IfNot1Column}
				{block:IfNot2Columns}
					{block:IfNot3Columns}
						{block:IfNot4Columns}
							{block:IfNot5Columns}
								<div class="photosetPost">{Photoset-250}</div>
							{/block:IfNot5Columns}
						{/block:IfNot4Columns}
					{/block:IfNot3Columns}
				{/block:IfNot2Columns}
			{/block:IfNot1Column}
	
		<!-- 1 columns -->
			{block:If1Column}
				{block:IfNot2Columns}
					{block:IfNot3Columns}
						{block:IfNot4Columns}
							{block:IfNot5Columns}
								<div class="photosetPost">{Photoset-500}</div>
							{/block:IfNot5Columns}
						{/block:IfNot4Columns}
					{/block:IfNot3Columns}
				{/block:IfNot2Columns}
			{/block:If1Column}
		
		<!-- 2 columns -->
			{block:If2Columns}
				{block:IfNot3Columns}
					{block:IfNot4Columns}
						{block:IfNot5Columns}
							<div class="photosetPost">{Photoset-400}</div>
						{/block:IfNot5Columns}
					{/block:IfNot4Columns}
				{/block:IfNot3Columns}
			{/block:If2Columns}
			
		<!-- 3 columns -->
			{block:If3Columns}
				{block:IfNot4Columns}
					{block:IfNot5Columns}
						<div class="photosetPost">{Photoset-250}</div>
					{/block:IfNot5Columns}
				{/block:IfNot4Columns}
			{/block:If3Columns}
			
		<!-- 4 columns -->
			{block:If4Columns}
				{block:IfNot5Columns}
					<div class="photosetPost">{Photoset-250}</div>
				{/block:IfNot5Columns}
			{/block:If4Columns}
			
		<!-- 5 columns -->
			{block:If5Columns}
				<div class="photosetPost">{Photoset-250}</div>
			{/block:If5Columns}
		{block:IfShowCaptions}
			{block:Caption}
				<div class="caption">{Caption}</div>
			{/block:Caption}
		{/block:IfShowCaptions}
		{block:Date}
			<div class="description_posts">
				<a href="{Permalink}">{TimeAgo}</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		{/block:Date}
	{/block:IndexPage}
	{block:PermalinkPage}
		<div class="photosetPost">{Photoset-500}</div>
		{block:Caption}
			<div class="caption">{Caption}</div>
		{/block:Caption}
	{/block:PermalinkPage}
{/block:Photoset}


{block:Answer}
	<img class="left" style="margin-right:10px;" width="30px" src="{AskerPortraitURL-30}"/>
	<div class="left quest">
		<b>{Asker}</b>:<br>
		{Question}
	</div>
	<div class="clear"></div>
	<div class="askAnswer">
		<img class="left" style="margin-right:10px;" width="30px" src="{PortraitURL-30}"/>
		<div class="left quest">
			<b>Me</b>:<br> 
			<i>{Answer}</i>
		</div>
		<div class="clear"></div>
	</div>
	{block:IndexPage}
		{block:Date}
			<div class="description_posts">
				<a href="{Permalink}">{TimeAgo}</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		{/block:Date}
	{/block:IndexPage}
{/block:Answer}


{block:Quote}
	<h3 class="title">"{Quote}"</h3>
	{block:Source}
		<div class="caption" style="text-align:right;">- {Source}</div>
	{/block:Source}
	{block:IndexPage}
		{block:Date}
			<div class="description_posts">
				<a href="{Permalink}">{TimeAgo}</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		{/block:Date}
	{/block:IndexPage}
{/block:Quote}


{block:Chat}
	{block:Title}
		<h3 class="title">{Title}</h3>
	{/block:Title}
		<ul class="chat">
			{block:Lines}
				<li class="{Alt} user_{UserNumber}">
					{block:Label}
						<span class="label">{Label}</span>
					{/block:Label}
					<span class="caption">{Line}</span>
				</li>
			{/block:Lines}
		</ul>
	{block:IndexPage}
		{block:Date}
			<div class="description_posts">
				<a href="{Permalink}">{TimeAgo}</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		{/block:Date}
	{/block:IndexPage}
{/block:Chat}

{block:Audio}

	{block:IndexPage}
		<div class="audioplayercontainer">
			<img class="audioimage" src="{block:AlbumArt}{AlbumArtURL}{/block:AlbumArt}" alt="{block:Artist}{Artist}{/block:Artist}{block:TrackName} - {TrackName}{/block:TrackName}" style="margin-bottom:10px;" />
			<div class="audioplayerout">
				<div class="audioplayerinto">{AudioPlayerBlack}</div>
			</div>
			<div class="noteAudio">
				<a href="{Permalink}">{FormattedPlayCount} plays</a>
				<a href="{Permalink}">{NoteCountWithLabel}</a>
				<a href="{ReblogURL}" target="_blank">Reblog</a>
			</div>
		</div>
		{block:IfShowCaptions}
			{block:Caption}
				<div class="caption" style="margin-top:15px;">{Caption}</div>
			{/block:Caption}
		
			{block:Date}
				<div class="description_posts">
					<a href="{Permalink}">{TimeAgo}</a>
					<a href="{Permalink}">{NoteCountWithLabel}</a>
					<a href="{ReblogURL}" target="_blank">Reblog</a>
				</div>
			{/block:Date}
		{/block:IfShowCaptions}
	{/block:IndexPage}
	
	{block:PermalinkPage}
		<div class="album_art left">
			<div class="effectalbumart"></div>
			{block:AlbumArt}
				<img width="150" src="{AlbumArtURL}" alt="{block:Artist}{Artist}{/block:Artist}{block:TrackName} - {TrackName}{/block:TrackName}"/>
			{/block:AlbumArt}
		</div>
		<ul class="audiotrack left">
			{block:Artist}<li><b>Artist:</b> {Artist}</li>{/block:Artist}
			{block:TrackName}<li><b>Song:</b> {TrackName}</li>{/block:TrackName}
			{block:Album}<li><b>Album:</b> {Album}</li>{/block:Album}
			<li><b>Plays:</b> {FormattedPlayCount}{block:ExternalAudio} <a href="{ExternalAudioURL}">(Download)</a>{/block:ExternalAudio}</li>
			<li>{AudioPlayerBlack}</li>
		</ul>
		<div class="clear"></div>
		{block:Caption}
			<div class="caption">{Caption}</div>
		{/block:Caption}
	{/block:PermalinkPage}
{/block:Audio}

{block:Video}
	{block:IndexPage}
		<!-- without columns -->
			{block:IfNot1Column}
				{block:IfNot2Columns}
					{block:IfNot3Columns}
						{block:IfNot4Columns}
							{block:IfNot5Columns}
								<div class="videoPost" id="video_{PostID}">{Video-250}</div>
							{/block:IfNot5Columns}
						{/block:IfNot4Columns}
					{/block:IfNot3Columns}
				{/block:IfNot2Columns}
			{/block:IfNot1Column}
	
		<!-- 1 columns -->
			{block:If1Column}
				{block:IfNot2Columns}
					{block:IfNot3Columns}
						{block:IfNot4Columns}
							{block:IfNot5Columns}
								<div class="videoPost" id="video_{PostID}">{Video-500}</div>
							{/block:IfNot5Columns}
						{/block:IfNot4Columns}
					{/block:IfNot3Columns}
				{/block:IfNot2Columns}
			{/block:If1Column}
		
		<!-- 2 columns -->
			{block:If2Columns}
				{block:IfNot3Columns}
					{block:IfNot4Columns}
						{block:IfNot5Columns}
							<div class="videoPost" id="video_{PostID}">{Video-400}</div>
						{/block:IfNot5Columns}
					{/block:IfNot4Columns}
				{/block:IfNot3Columns}
			{/block:If2Columns}
			
		<!-- 3 columns -->
			{block:If3Columns}
				{block:IfNot4Columns}
					{block:IfNot5Columns}
						<div class="videoPost" id="video_{PostID}">{Video-250}</div>
					{/block:IfNot5Columns}
				{/block:IfNot4Columns}
			{/block:If3Columns}
			
		<!-- 4 columns -->
			{block:If4Columns}
				{block:IfNot5Columns}
					<div class="videoPost" id="video_{PostID}">{Video-250}</div>
				{/block:IfNot5Columns}
			{/block:If4Columns}
			
		<!-- 5 columns -->
			{block:If5Columns}
				<div class="videoPost" id="video_{PostID}">{Video-250}</div>
			{/block:If5Columns}
			
		{block:IfShowCaptions}
			{block:Caption}
				<div class="caption">{Caption}</div>
			{/block:Caption}
			{block:Date}
				<div class="description_posts">
					<a href="{Permalink}">{TimeAgo}</a>
					<a href="{Permalink}">{NoteCountWithLabel}</a>
					<a href="{ReblogURL}" target="_blank">Reblog</a>
					<a href="javascript:void(0);" class="zoom_icon" rel="videoZOOM" id="{PostID}">Zoom</a>
				</div>
			{/block:Date}
		{/block:IfShowCaptions}
		{block:IfNotShowCaptions}
			<a href="{Permalink}" class="descriprion_icons permalink_icon"></a>
			<a href="{ReblogURL}" target="_blank" class="descriprion_icons reblog_icon"></a>
			<a href="javascript:void(0);" id="{PostID}" class="descriprion_icons zoom_icon" rel="videoZOOM"></a>
			<a class="descriprion_icons heart_icon" href="javascript:void(0);" id="{PostID}" rel="{ReblogURL}"></a>
			<div class="opacityColorPhotoEffect"></div>
		{/block:IfNotShowCaptions}
	{/block:IndexPage}
	{block:PermalinkPage}
		<div class="videoPost">{Video-500}</div>
		{block:Caption}
			<div class="caption">{Caption}</div>
		{/block:Caption}
	{/block:PermalinkPage}
{/block:Video}

{block:PermalinkPage}
	{block:IfShowSocial}
		{block:Date}
			<div class="sociallike" >
				<div style="display:inline-block;"><g:plusone annotation="none" size="medium" href="{Permalink}"></g:plusone></div>
				<span style="margin-left:5px;"><a href="https://twitter.com/share" class="twitter-share-button" data-via="rickerlr" data-count="none">Tweet</a>
				<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script></span>
				<span style="margin-left:4px;"><iframe id="facebookiframe" src="http://www.facebook.com/plugins/like.php?locale=en_US&href={Permalink}&width=45&colorscheme=light&layout=button_count" scrolling="no" frameborder='0' style="border:none; overflow:hidden; width:50px; height:20px;"></iframe></span>
			</div>
		{/block:Date}
	{/block:IfShowSocial}
{/block:PermalinkPage}
</div>
</div><!-- .posts -->

{block:PermalinkPage}
{block:Date}
<div class="posts" style="{block:IfNotShowNotesPermalink}width:320px;{/block:IfNotShowNotesPermalink}overflow: visible;">
	<div class="postnotesdiv">
		<ul id="postPageUl">
			<li>
				On <a href="/day/{Year}/{MonthNumberWithZero}/{DayOfMonthWithZero}">{DayOfMonthWithZero} {ShortMonth} {Year}</a><br>
			</li>
			<li>
				{TimeAgo} | {12HourWithZero}:{Minutes}{AmPm}
			</li>
			{block:RebloggedFrom}
				<li>
					Reblogged from <a href="{ReblogParentURL}">{ReblogParentName}</a>
				</li>
				<li>
					Posted by <a href="{ReblogRootURL}">{ReblogRootName}</a>
				</li>
			{/block:RebloggedFrom}
			{block:HasTags}
				<li style="margin:10px 0px 15px;">
					{block:Tags}<a class="atag" href="{TagURL}">#{Tag} </a>{/block:Tags}
				</li>
			{/block:HasTags}
		</ul>
{block:IfShowNotesPermalink}
	</div>
</div>
	<div class="posts"><div class="postnotesdiv">
{/block:IfShowNotesPermalink}
		<div class="countNote_pagePosts">
			<div class="left">
				{block:NoteCount}{NoteCountWithLabel}{/block:NoteCount}
			</div>
			{block:PermalinkPagination}
				<div id="paginationPost" class="right">
					{block:NextPost}<a id="paginationPost_prev" href="{NextPost}">« Prev </a>{/block:NextPost}
					{block:PreviousPost}<a id="paginationPost_next" href="{PreviousPost}"> Next »</a>{/block:PreviousPost}
				</div>
			{/block:PermalinkPagination}
			<div class="clear"></div>
		</div>
		
		{block:PostNotes}
			{PostNotes}
		{/block:PostNotes}
		<div class="clear"></div>
</div>

	</div><!-- .posts -->
{/block:Date}
{/block:PermalinkPage}

<!-- zoom -->
{block:IndexPage}
	<div id="zoomPost">
		<div id="zoomPost_content"><div style="padding:10px;">
			<div class="closeZoom" id="closeZoom"></div>
			<!-- image -->
				<img id="photoZoom" src="" width="500" style="margin-bottom:-3px;display:none;" />
			<!-- video -->
				<iframe id="videoZoom" src="" style="margin-bottom:-3px;display:none;"></iframe>
		</div></div>
		<div id="zoomPost_background" class="closeZoom"></div>
	</div>
{/block:IndexPage}

{/block:Posts}
<div class="clear"></div>
</div><!-- content -->

<div class="clear"></div>
</div><!-- container -->
<div id="topDiv">
	
	<ul class="bottomLinks">
		<li><a href="/">Home</a></li>
			{block:AskEnabled}
			<li><a href="/ask" >{AskLabel}</a></li>
		{/block:AskEnabled}
		{block:IfShowRSSLink}
			<li><a href="/rss" >Rss</a></li>
		{block:IfShowRSSLink}
		{block:IfShowArchiveLink}
			<li><a href="/archive" >Archive</a></li>
		{block:IfShowArchiveLink}
		{block:IfLink1title}
			<li><a href="{text:Link 1 url}" >{text:Link 1 title}</a></li>
		{/block:IfLink1title}
		{block:IfLink2title}
			<li><a href="{text:Link 2 url}" >{text:Link 2 title}</a></li>
		{/block:IfLink2title}
		{block:IfLink3title}
			<li><a href="{text:Link 3 url}" >{text:Link 3 title}</a></li>
		{/block:IfLink3title}
		{block:IfLink4title}
			<li><a href="{text:Link 4 url}" >{text:Link 4 title}</a></li>
		{/block:IfLink4title}
		{block:IfLink5title}
			<li><a href="{text:Link 5 url}" >{text:Link 5 title}</a></li>
		{/block:IfLink5title}
		{block:IfLink6title}
			<li><a href="{text:Link 6 url}" >{text:Link 6 title}</a></li>
		{/block:IfLink6title}
	</ul>
	
	<a href="javascript:void(0);" id="topDivA">{text:Back Top}</a>
</div>

{block:IndexPage}
	{block:Pagination}
		<ul id="pagination">
			{block:PreviousPage}
				<li><a href="{PreviousPage}">«</a></li>
			{/block:PreviousPage}
			{block:JumpPagination length="5"}
			{block:CurrentPage}
				<li><span class="current_page numbersNav"><strong>{PageNumber}</strong></span></li>
			{/block:CurrentPage}
			{block:JumpPage}
				<li><a class="jump_page numbersNav" href="{URL}">{PageNumber}</a></li>
			{/block:JumpPage}
			{/block:JumpPagination}
			{block:NextPage}
				<li><a id="nextPage" href="{NextPage}">»</a></li>
			{/block:NextPage}
		</ul>
	{/block:Pagination}
{/block:IndexPage}

<div id="footer">
	{block:IfFooterText}
		{text:Footer Text}
		<br>
	{/block:IfFooterText}
	theme <a href="http://www.themecloud.co/lightglass-tumblr-theme.asp" target="_blank">LIGHTGLASS</a> by <a rel="author" href="http://rickerlr.tumblr.com/" target="_blank">rickerlr</a>
	<br>
	<a href="http://rickerlrthemes.tumblr.com/" target="_blank">rickerlrthemes</a>
</div>

<!-- Jquery -->
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>

<!-- Lightglass js functions -->
<script type="text/javascript" src="http://www.themecloud.co/themes/lightglass/getjs.asp?id=182953"></script>


{block:IfHideDescription}
<script type="text/javascript">
	$(function(){
		$("#nameBlog").click(function(){
			$("#head_description").fadeToggle(500);
		});
	});
</script>
{/block:IfHideDescription}
{block:IndexPage}
<script type="text/javascript"  src="http://static.tumblr.com/dbek3sy/4IKlvmzup/jquery.masonry.min.js"></script>
{block:IfInfiniteScroll}
<script type="text/javascript" src="http://static.tumblr.com/dbek3sy/Qyblrgjfn/jqueryinfintescroll.js"></script>
{/block:IfInfiniteScroll}
<script type="text/javascript">
$(window).load(function () {
var $content = $('#content');
$content.masonry({
    itemSelector: '.posts',
    isAnimated: true
    }),
$content.infinitescroll({
    	navSelector    : '#pagination',  
      nextSelector   : '#pagination a#nextPage', 
      itemSelector   : '.posts',
      loading: {
          finishedMsg: '',
          img: 'http://static.tumblr.com/dbek3sy/pX1lrx8xv/ajax-loader.gif'
      },
      bufferPx       : 200,
      debug          : false,
},
// call masonry as a callback.
function( newElements ) {
	var $newElems = $( newElements );
		$newElems.hide();
	// ensure that images load before adding to masonry layout
	$newElems.imagesLoaded(function(){
		$content.masonry( 'appended', 
        $newElems, true,
        function(){$newElems.fadeIn(300);} 
    );

		
	});
});
});
</script>
{/block:IndexPage}
{block:IfContainerFadeIn}
<script type="text/javascript">
	$(function(){
		$("#container").fadeIn(500);
	});
</script>
{/block:IfContainerFadeIn}

<script type="text/javascript">
  (function() {
    var po = document.createElement('script'); po.type = 'text/javascript'; po.async = true;
    po.src = 'https://apis.google.com/js/plusone.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(po, s);
  })();
</script>

{block:IfGoogleAnalyticsID}
<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', '{text:Google Analytics ID}']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>
{/block:IfGoogleAnalyticsID}
<iframe id="likeIframe" src="" style="width:1px;height:1px;position:absolute;left:-9999px;"></iframe>

</body>
</html>

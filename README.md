# samerezare.githab.ion/*!
 * Documenter 1.6
 * http://rxa.li/documenter
 *
 * Copyright 2011, Xaver Birsak
 * http://revaxarts.com
 *
 */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td{
	margin:0;
	padding:0;
	border:0;
	outline:0;
	font-weight:inherit;
	font-style:inherit;
	font-size:100%;
	font-family:inherit;
	vertical-align:baseline;
}
html { 
	font-size:101%;
	font-family:Arial,verdana,arial,sans-serif;
	font-size:12px;
	-webkit-text-size-adjust:none;
	color:#6F6F6F;
	background-color:#efefef;
}
body{
	min-height:100%;
	height:auto;
	width:100%;
	font-size:14px;
	font-family: 'Roboto';
	line-height:24px;
}
footer, header, section {
	display:block;
}
a{ color:#6F6F6F; text-decoration:none; cursor:pointer; }
a:hover { text-decoration:underline }
p, ul, ol{
	margin:0px 0;
	line-height:1.5em;
}
li{
	list-style:none;
}
li.placeholder{
	height:70px;
	width:100%;
	font-size:16px;
}
hr { 
	display:block;
	height:0px;
	line-height:0px;
	border:0;
	border-top:1px solid #ddd;
	border-bottom:1px solid #aaa;
	margin:16px 0;
	padding:0;
}
hr.notop{
	margin-top:0;
}
strong{
	font-weight:700;
}
.clr{
	 clear:both;
	}
#documenter_content{
	position:absolute;
	right:18px;
	left:262px;
	padding-left:10px;
	padding-bottom:800px;
	min-height:100%;
	height:auto;
	z-index:1;
}
#documenter_sidebar{
	-moz-box-shadow:0 0 6px rgba(3,3,3,0.6);
	-webkit-box-shadow:0 0 6px rgba(3,3,3,0.6);
	box-shadow:0 0 6px rgba(3,3,3,0.6);
	position:fixed;
	left:0;
	width:238px;
	height:100%;
	min-height:100%;
	z-index:100;
}
#documenter_sidebar a{
	position:relative;
	z-index:100;
}
img{
	border:0;
}
#documenter_copyright{
	position:absolute;
	bottom:10px;
	font-size:10px;
	right:15px;
	width:200px;
	text-align:right;
	z-index:1
}
noscript{
	display:block;
	position:absolute;
	top:238px;
	margin:0 auto;
	width:800px;
	bottom:0;
	z-index:20;
}
noscript p{
	width:800px;
	font-size:20px;
	padding-top:20px;
	margin:0 auto;
	color:#4D4D4D;
}
.small{
	font-size:10px;
	letter-spacing:0;
}

/*----------------------------------------------------------------------*/
/* Sidebar
/*----------------------------------------------------------------------*/

#documenter_sidebar #documenter_logo{
	display:block;
	height:33%;
	max-height:200px;
	min-height:70px;
	width:100%;
	background-position:center center;
	background-repeat:no-repeat;
}
#documenter_sidebar ol{
	font-size:12px;
	font-weight:700;
	min-height:150px;
	height:75%;
	overflow:auto;
}

#documenter_sidebar ol li{
	text-align:right;
	padding:0;
}
#documenter_sidebar ol a{
	display:block;
	border-top:1px solid #ddd;
	border-bottom:1px solid #aaa;
	padding:11px 15px 13px 0;
	text-align:right;
}
#documenter_sidebar ol a:hover,#documenter_sidebar ol a.current{
	-webkit-text-shadow:none;
	-moz-text-shadow:none;
	text-shadow:none;
	text-decoration:none;
}
#documenter_sidebar ol li ol{
	border-top:0;
	font-size:10px;
	min-height:10px;
	height:auto;
	overflow:auto;
	margin:0;
	display:none;
}
#documenter_sidebar ol li ol li a{
	display:block;
	padding:4px 15px 5px 0;
	text-align:right;
}

/*----------------------------------------------------------------------*/
/* Content
/*----------------------------------------------------------------------*/

#documenter_cover{
	height:800px;
	padding-top:200px !important;
}
#documenter_cover li{
	list-style:none !important;
	margin-left:0 !important;
}
#documenter_cover p{
	width:500px;
}
#documenter_content section{
	padding-top:70px;
}
#documenter_content h1{
	font-size:30px;
	font-weight:700;
}
#documenter_content h2{
	font-size:20px;
	margin-bottom:18px;
	font-weight:100;
}
#documenter_content h3{
	font-size:26px;
	text-transform:capitalize;
	margin:18px 0 14px;
	font-weight:100;
}
#documenter_content h4{
	font-size:20px;
	margin:18px 0;
	font-weight:100;
}
#documenter_content h5{
	font-size:16px;
	margin:18px 0;
	font-weight:100;
}
#documenter_content h6{
	font-size:14px;
	margin:18px 0;
	font-weight:100;
}
#documenter_content p{
	margin:18px 0;
}
#documenter_content ol li{
	list-style:decimal;
	margin-left:36px;
}
#documenter_content ul li{
	list-style:square;
	margin-left:36px;
}
#documenter_content dl{
}
#documenter_content dl dt{
	padding-top:12px;
	font-weight:700;
	font-size:14px;
}
#documenter_content dl dd{
	padding-top:3px;
	margin-left:18px;
}
#documenter_content table{
	border-collapse:collapse;
}
#documenter_content table th{
	font-weight:700;
}
#documenter_content table th, #documenter_content table td{
	padding:3px;
	text-align:left;
}
#documenter_content code, #documenter_content pre{
	font-family:"Courier New", Courier, monospace;
	font-size:12px;
}
#documenter_content .warning{
	padding:10px 10px 10px 30px;
	border:1px solid #D5D458;
	background-color:#F0FEB1;
	background-image:url(img/warning.png);
	background-repeat:no-repeat;
	background-position: 8px 11px;
}
#documenter_content .info{
	padding:10px 10px 10px 30px;
	border:1px solid #6AB3FF;
	background-color:#A3D0FF;
	background-image:url(img/info.png);
	background-repeat:no-repeat;
	background-position: 8px 11px;
}
#documenter_content pre{
	background-image:url(img/pre_bg.png);
	line-height:19px;
}

.layout{ float:left; margin-right:15px;}


/*----------------------------------------------------------------------*/
/* Print Styles
/*----------------------------------------------------------------------*/

@media print {
	 * { background: transparent !important; color: black !important; text-shadow: none !important; filter:none !important;
	-ms-filter: none !important; } /* Black prints faster: sanbeiji.com/archives/953 */
	a, a:visited { color: #444 !important; text-decoration: underline; }
	a[href]:after { content: " (" attr(href) ")"; }
	abbr[title]:after { content: " (" attr(title) ")"; }
	.ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after { content: ""; }  /* Don't show links for images, or javascript/internal links */
	pre, blockquote { border: 1px solid #999; page-break-inside: avoid; }
	thead { display: table-header-group; } /* css-discuss.incutio.com/wiki/Printing_Tables */
	tr, img { page-break-inside: avoid; }
	@page { margin: 0.5cm; }
	p, h2, h3 { orphans: 3; widows: 3; }
	h2, h3{ page-break-after: avoid; }
	hr { border-top:1px solid #000 !important;border-bottom:0 !important; }
	
	#documenter_sidebar{
		-moz-box-shadow:none;
		-webkit-box-shadow:none;
		box-shadow:none;
		position:absolute;
		left:10px;
		top:0;
		width:100%;
		margin-top:500px;
	}
	#documenter_sidebar ol:before { content: "Table of Contents"; }
	
	#documenter_sidebar ol{
		border:0 !important;
	}
	#documenter_sidebar ol li{
		border:0 !important;
		text-align:left;
	}
	#documenter_sidebar ol li a{
		border:0 !important;
		text-align:left;
		padding:4px;
	}
	#documenter_sidebar ol li a:hover{
		border:0 !important;
	}
	#documenter_sidebar #documenter_logo{
		display:none;
	}
	#documenter_sidebar #documenter_copyright{
		display:none;
	}
	#documenter_content{
		left:10px;
	}
	#documenter_cover{
		margin-bottom:300px;
	}
	#documenter_content .warning{
		background-image:url(img/warning.png) !important;
		background-repeat:no-repeat !important;
		background-position: 8px 11px !important;
	}
	#documenter_content .info{
		background-image:url(img/info.png) !important;
		background-repeat:no-repeat !important;
		background-position: 8px 11px !important;
	}
	#documenter_content pre{
		background-image:url(img/pre_bg.png) !important;
		line-height:19px;
	}
}

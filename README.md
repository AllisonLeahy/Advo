Advo
====

advocacy

/* THEME BASICS
 * Predefined CSS that correspond to the LESS variables. It's best to
 * avoid adding additional styles for your theme here, unless you are
 * trying to hard-code a value such that an NC cannot customize it.
 * Most of these properties are defined with LESS variables; those that
 * are hard-coded are just there for the purpose of valid CSS.
 */
body {
  	background:@ning-body-background-color @ning-body-background-image @ning-body-background-repeat scroll 0 0;
}
.xg_theme .xg_user_generated p,
.xg_theme .xg_user_generated ol,
.xg_theme .xg_user_generated ul,
.xg_theme .xg_user_generated dl,
.xg_theme .xg_user_generated blockquote,
.xg_theme .xg_user_generated table,
.xg_theme .xg_user_generated h1,
.xg_theme .xg_user_generated h2,
.xg_theme .xg_user_generated h3,
.xg_theme .xg_user_generated h4,
.xg_theme .xg_user_generated h5,
.xg_theme .xg_user_generated h6 {
        margin-bottom:@ning-p-margin-bottom;
}
.xg_theme #xg_themebody {
        font-weight:@ning-body-font-weight;
        font-size:@ning-body-font-size;
        font-family:@ning-body-font-family;
        color:@ning-body-color;
}

.xg_theme a {
        color:@ning-a-color;
        font-weight:@ning-a-font-weight;
        text-decoration:@ning-a-text-decoration;
        border-bottom:@ning-a-border-bottom;
}

.xg_theme a:hover {
        color:@ning-a-hover-color;
        font-weight:@ning-a-hover-font-weight;
        text-decoration:@ning-a-hover-text-decoration;
        border-bottom:@ning-a-hover-border-bottom;
}

.xg_theme h1, .xg_theme h2, .xg_theme h3, .xg_theme h4, .xg_theme h5, .xg_theme h6 {
        font-weight:@ning-heading-font-weight;
        font-family:@ning-heading-font-family;
        color:@ning-heading-color;
}

.xg_theme button,
.xg_theme a.button,
.xg_theme input.button {
        background:@ning-button-background-color @ning-button-background-image @ning-button-background-repeat scroll 0 0;
        color:@ning-button-color;
        font-weight:@ning-button-font-weight;
        font-size:@ning-body-font-size;
        font-family:@ning-button-font-family;
        border-width:@ning-button-border-width;
        border-style:@ning-button-border-style;
        border-color:@ning-button-border-color;
}

.xg_theme #xg_head {
        background:@ning-header-background-color @ning-header-background-image @ning-header-background-repeat scroll 0 0;
        border-width:@ning-header-border-width;
        border-style:@ning-header-border-style;
        border-color:@ning-header-border-color;
}

.xg_theme h1#xg_sitename {
        font-size:@ning-site-name-font-size;
}

.xg_theme h1#xg_sitename a {
        color:@ning-site-name-color;
        font-weight:@ning-site-name-font-weight;
        font-family:@ning-site-name-font-family;
}

.xg_theme p#xg_sitedesc {
        color:@ning-site-desc-color;
        font-weight:@ning-site-desc-font-weight;
        font-size:@ning-site-desc-font-size;
        font-family:@ning-site-desc-font-family;
}

.xg_theme #xg_navigation {
        background:@ning-navigation-background-color @ning-navigation-background-image @ning-navigation-background-repeat scroll 0 bottom;
        border-width:@ning-navigation-border-width;
        border-style:@ning-navigation-border-style;
        border-color:@ning-navigation-border-color;
}

.xg_theme #xg_navigation ul li a {
        color:@ning-navigation-a-color;
        background-color:@ning-navigation-a-background-color;
        font-weight:@ning-navigation-font-weight;
        font-size:@ning-navigation-font-size;
        font-family:@ning-navigation-font-family;
}

.xg_theme #xg_navigation ul li a:hover {
        color:@ning-navigation-a-hover-color;
        background-color:@ning-navigation-a-hover-background-color;
}

.xg_theme #xg_navigation ul div.xg_subtab ul li a {
        color:@ning-sub-navigation-a-color;
        background:@ning-sub-navigation-a-background-color;
}
.xg_theme #xg_navigation ul div.xg_subtab ul li a:hover {
        color:@ning-sub-navigation-a-hover-color;
        background:@ning-sub-navigation-a-hover-background-color;
}

.xg_theme #xg {
        background:@ning-main-background-color @ning-main-background-image @ning-main-background-repeat scroll 0 0;
}

.xg_theme #xg_body {
        background:@ning-main-content-background-color @ning-main-content-background-image @ning-main-content-background-repeat scroll 0 0;
        border-width:@ning-main-content-border-width;
        border-style:@ning-main-content-border-style;
        border-color:@ning-main-content-border-color;
        width: auto;
}

.xg_theme .xg_module {
        background:@ning-module-background-color @ning-module-background-image @ning-module-background-repeat scroll 0 0;
        border-width:@ning-module-border-width;
        border-style:@ning-module-border-style;
        border-color:@ning-module-border-color;
}

.xg_theme .xg_module_head {
        background:@ning-module-head-background-color @ning-module-head-background-image @ning-module-head-background-repeat scroll 0 0;
        border-width:@ning-module-head-border-width;
        border-style:@ning-module-head-border-style;
        border-color:@ning-module-head-border-color;
}

.xg_theme .xg_module_head h2 {
        color:@ning-module-head-color;
        font-weight:@ning-module-head-font-weight;
        font-size:@ning-module-head-font-size;
        font-family:@ning-module-head-font-family;
}

.xg_theme .xg_module_body {
        background:@ning-module-body-background-color @ning-module-body-background-image @ning-module-body-background-repeat scroll 0 0;
        font-size:@ning-body-font-size;
}

.xg_theme #xg_foot {
        background:@ning-foot-background-color @ning-foot-background-image @ning-foot-background-repeat scroll 0 0;
        border-width:@ning-foot-border-width;
        border-style:@ning-foot-border-style;
        border-color:@ning-foot-border-color;
}

.xg_theme #xg_footcontent {
        background:@ning-foot-content-background-color @ning-foot-content-background-image @ning-foot-content-background-repeat scroll 0 0;
        border-width:@ning-foot-content-border-width;
        border-style:@ning-foot-content-border-style;
        border-color:@ning-foot-content-border-color;
        color:@ning-foot-content-color;
}

.xg_theme .xg_floating_container {
		background-color:@ning-floating-container-background-color;
		color:@ning-floating-container-color;
		font-weight:@ning-body-font-weight;
        font-size:@ning-body-font-size;
        font-family:@ning-body-font-family;
}

.xg_theme .mediabutton-c {
		color:@ning-player-color;
}

.xg_theme .mediaplayer-bc {
		background-color:@ning-player-background-color;
}

.xg_theme .mediaplaylist-bc {
        background-color:@ning-playlist-background-color;
}

#xn_bar, .xg_theme-ningbar-bc {
        background-color:@ning-ningbar-background-color;
}

#xn_bar #xn_bar_menu a, .xg_theme-ningbar-c {
		color:#333;
}

.xg_theme-ningbar-c .xg_sprite {
    background-image: url(/xn_resources/widgets/index/gfx/icons/xg_sprite-333333.png) !important; /* override bottom-bar.css */
}

.xg_theme-ningbar-c a:hover {
    color: #000 !important; /* override bottom-bar.css */
}

.xg_theme-ningbar-c a.xg_sprite:hover {
    background-image: url(/xn_resources/widgets/index/gfx/icons/xg_sprite-000000.png) !important; /* override bottom-bar.css */
}

#xn_bar #xn_bar_menu_search_submit {
		background-position:0 -100px;
}

.xg_theme .icon-color {
		color:@ning-icon-color;
}

.xg_theme .xg_lightborder {
		border-color:#c4d0d5;
}

.xg_theme .xg_lightfont {
		color:#666;
}

.xg_theme .xg_theme-button-c {
		color:@ning-button-color;
}

.xg_theme .xg_theme-button-bc {
		background-color:@ning-button-background-color;
}

.xg_theme .xg_theme-link-c {
		color:@ning-a-color;
}

/* THEME EXTRA
 * Add your additional CSS below. Also consider setting the following:
 * -Default sizes for h1, h2, etc.
 * -Default list styles
 * -Etc
 * Remember that #xg_body must have an inner width of 982px.
 * Note that you can use the LESS variables you set above to tie styles of various elements to
 * match the theme.
 */

.xg_theme #xg_head {
	background-position:center bottom;
}

.xg_theme .xg_lightborder.paid-module #xg_head {
	background-color: @ning-body-background-color;
}



.xg_theme h1#xg_sitename {
	text-align:center;
	text-transform:uppercase;
	letter-spacing:1px;
	line-height:1em;
	margin:0;
	padding-top:20px;
	text-shadow:#222 1px 1px 2px;
}

.xg_theme p#xg_sitedesc {
	text-align:center;
	text-transform:uppercase;
	letter-spacing:2px;
	margin:0;
	text-shadow:#222 1px 1px 2px;
}

.xg_theme #xg_navigation {
	padding:10px 0;
}

.xg_theme #xg_navigation ul {
	width:982px;
	margin:0 auto;
	padding-bottom:20px;
}

.xg_theme #xg_navigation li {
	float:left;
	text-transform:uppercase;
	margin:6px 12px 0;
}

.xg_theme #xg {
	position:relative;
	top:-6px;
	padding-top:20px;
}

.xg_theme .xg_module_head h2 {
	text-transform:uppercase;
	float:none;
	text-align:center;
}

.xg_theme #xg_foot {
	position:relative;
	top:-6px;
	background-position:0 bottom;
	margin-bottom:60px;
}

.xg_theme #xg_footcontent {
	margin:0 auto;
	width:982px;
	text-transform:uppercase;
	padding:10px 0;
}

.xg_theme .xj_ad_below_header {
	background:@ning-main-background-color @ning-main-background-image @ning-main-background-repeat scroll 0 0;
position: relative;
    top: -6px;}
.xg_ad {
	width:100%;
	}
.xg_ad .xg_module, .xg_ad .xg_module_head, .xg_ad .xg_module_body {
    margin: 0 auto !important;
    width: 982px;
    }


/* OPTIONAL
 * Additional elements that are reused by applications that the theme
 * should style. Includes form elements, sub-tabs, etc. Remove the
 * comment blocks to include this CSS, and only remove them if you
 * are actually changing the predefined values. Otherwise, you'll
 * have redundant CSS. Note that there is more CSS that makes elements
 * like lightboxes work, but only the styles that may be theme-
 * pertinent are included below. You only need to be concerned with
 * aesthetic properties.
 *
 * TBD
 */

.xg_chatArea .xg_chatBar.xg_titleBar {
    border-bottom: 1px solid #ccc;
}
.xg_theme #xg_head {
 background: none;
}
.xg_theme #xg_masthead {
 width: 1010px;
 margin: auto;
background-color: #DEDACB;

-webkit-box-shadow: 0px 0px 28px 1px rgba(0, 0, 0, 0.4);
-moz-box-shadow: 0px 0px 28px 1px rgba(0, 0, 0, 0.4);
box-shadow: 0px 0px 28px 1px rgba(0, 0, 0, 0.4); 
}

.xg_theme #xg_navigation {
z-index: 1008;
background: #ffffff; /* Old browsers */
background: -moz-linear-gradient(top, #ffffff 0%, #ffffff 76%, #dcd9cb 100%); /* FF3.6+ */
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#ffffff), color-stop(76%,#ffffff), color-stop(100%,#dcd9cb)); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(top, #ffffff 0%,#ffffff 76%,#dcd9cb 100%); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(top, #ffffff 0%,#ffffff 76%,#dcd9cb 100%); /* Opera 11.10+ */
background: -ms-linear-gradient(top, #ffffff 0%,#ffffff 76%,#dcd9cb 100%); /* IE10+ */
background: linear-gradient(top, #ffffff 0%,#ffffff 76%,#dcd9cb 100%); /* W3C */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffffff', endColorstr='#dcd9cb',GradientType=0 ); /* IE6-9 */
-webkit-box-shadow: 0px 3px 3px 1px rgba(0, 0, 0, 0.1);
-moz-box-shadow: 0px 3px 3px 1px rgba(0, 0, 0, 0.1);
box-shadow: 0px 3px 3px 1px rgba(0, 0, 0, 0.1); 
position: relative; 
z-index: 1000;
padding-bottom: 0;
}

.xg_theme #xg {
    padding-top: 0px;
    position: relative;
z-index: 100;
    top: 0px;
    width: 1010px;
    margin: auto;
-webkit-box-shadow: 0px 0px 28px 1px rgba(0, 0, 0, 0.4);
-moz-box-shadow: 0px 0px 28px 1px rgba(0, 0, 0, 0.4);
box-shadow: 0px 0px 28px 1px rgba(0, 0, 0, 0.4); 
}

.xg_theme #xg_navigation ul {
padding-bottom: 0;
padding-top: 0px;
background-image: url("http://api.ning.com:80/files/xvbBnabMFrRJkQXf2LV6D90AoAHqb989fTr*X0lSaIvoePUbdxf6pHLu5nEh--6CcRBvU0pywhuPJlLxKEyQ3gzJsqo9Uecm/navdivider.gif");
background-repeat: no-repeat;
background-position: left bottom;
line-height: 30px;
width: 1010px;
}
.xg_theme #xg_navigation ul li {
background-image: url("http://api.ning.com:80/files/xvbBnabMFrRJkQXf2LV6D90AoAHqb989fTr*X0lSaIvoePUbdxf6pHLu5nEh--6CcRBvU0pywhuPJlLxKEyQ3gzJsqo9Uecm/navdivider.gif");
background-repeat: no-repeat;
background-position: right bottom;
padding: 6px 12px 0;
margin: 0;
}

.xg_theme h1#xg_sitename {
 font-size: 0;
position: relative; 
z-index: 900;
width: 100%;
background-color: #DDDACB;
}

.xg_theme .xg_module {
background: #eeece5; /* Old browsers */
background: -moz-linear-gradient(top, #eeece5 0%, #ffffff 31%, #ffffff 100%); /* FF3.6+ */
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#eeece5), color-stop(31%,#ffffff), color-stop(100%,#ffffff)); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(top, #eeece5 0%,#ffffff 31%,#ffffff 100%); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(top, #eeece5 0%,#ffffff 31%,#ffffff 100%); /* Opera 11.10+ */
background: -ms-linear-gradient(top, #eeece5 0%,#ffffff 31%,#ffffff 100%); /* IE10+ */
background: linear-gradient(top, #eeece5 0%,#ffffff 31%,#ffffff 100%); /* W3C */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#eeece5', endColorstr='#ffffff',GradientType=0 ); /* IE6-9 */
padding: 10px;
}

.calendarWrap .xg_module {
padding: 0px;
}

#column1 {
margin-left: 15px;
}

#xg_foot, .xj_after_content {
display: none;
}

.xg_theme .xg_module_head h2 {
text-align: left;
color: #5D3743;
font-style: italic;
font-size: 17px;
text-transform: none;
background-image: url("http://api.ning.com:80/files/DygRyM8aGHzOyqSU54gRBnyUv*Vbafarq9ams3I910xcyECa2AmMD447ysMhPMvCCqSMpn0HF-LEcgH82Sf2G-0*338HQrrH/quotebox.png");
padding-left: 40px;
height: 27px;
line-height: 27px;
background-repeat: no-repeat;
margin-top: 4px;
margin-left: 4px;
}

.xg_theme #xg_navigation ul div.xg_subtab ul li a {
background-color: #603844;
color: #BFB4AB;
font-style: italic;
font-size: 14px;
text-transform: none;
font-weight: normal;
}

.xg_floating_module .xg_floating_container {
background-color: #F9FDE6;
}



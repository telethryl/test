<head>
  <meta name="robots" content="nofollow" />
</head>
title: Stuff and Such

<!DOCTYPE html>
 
<!--
A THEME BY SODAPOPCODES - PAGE 001 (GIF PAGE)
 
    - icons by themehive
    - fonts from google fonts
    - pop up code by str-wrs
 
 
<html lang="en"><head><title>{block:PostSummary}{PostSummary} | {/block:PostSummary}{Title}</title><link rel="shortcut icon" href="{favicon}"><link href="//dl.dropbox.com/s/vpi3f9s7nhpe7v7/honeybee.css" rel="stylesheet"><link href="https://fonts.googleapis.com/css?family=Poppins" rel="stylesheet">
 
<style>
 
iframe.tmblr-iframe {display:none;}body {background:#eeeeee;font-family: 'Poppins', sans-serif;color:#222222;} a {text-decoration:none;color:#fe6f61;}   #footer {margin:0 auto;position:fixed;top:0px; left:0px;width:50px;padding-top:15px;padding-bottom:15px;background:#ffffff;border-right:1px solid #cccccc;height:100%;font-size:20px;}    #footer a{margin:15px;} #footer span{margin-bottom:20px;}   #pagetitle {width:300px;font-weight:bold;color:#fe6f61;bottom:0px;left:10px;position:fixed;transform: rotate(-90deg);transform-origin: left top 0;}   #content {margin:10px;margin-left:60px;}    #content img {margin-right:10px;margin-bottom:3px;}  #s-m-t-tooltip {max-width:300px;margin:20px;background:#fe6f61; font-size:8px;text-transform:uppercase;letter-spacing:1px;border-radius:5px;padding:5px;color:#ffffff;z-index:999999999999999999999999999999999999;}   .popup_block{display:none;background:#fff;padding:20px;padding-bottom:15px;border:1px solid #cccccc;font-size:12px;float:left;position:fixed;top:50%;left:50%;z-index: 99999;-webkit-box-shadow: 0px 0px 20px #000; -moz-box-shadow: 0px 0px 20px #000; box-shadow: 0px 0px 20px #000;}   *html #fade {position: absolute;}
*html .popup_block {position: absolute;}    #fade {display:none;position:fixed;left:0px;top:0px;width:100%;height:100%;z-index:9999;background:#000; opacity:0.5;}  h2 {margin:0px;padding:15px;background-color:#fe6f61;color:#ffffff;text-align:center;}    p {width:175px;padding:10px;font-size:9px;background-color:#fe6f61;color:#ffffff;text-transform:uppercase;display:inline-block;margin-bottom:0px;}    p span {float:right;font-weight:bold;}  #stats {columns:2;}    #links {text-align:center;font-size:20px;margin-top:20px;margin-bottom:0px;}    #links a{margin-left:10px;margin-right:10px;margin-bottom:0px;}   #description {margin:10px;font-weight:11px;text-align:justify;margin-bottom:0px;}p a {color:#fff;text-decoration:underline;}
 
 
</style></head><body>
 
<div id="footer">
<a href="#?w=400" rel="box1" class="poplight" title="information"><span class="th th-information"></span></a>
 
<div id="pagetitle">
GIF PACK TITLE HERE                     <!-- PAGE TITLE -->
</div>
</div>
 
<div id="box1" class="popup_block">
<h2>GIF PACK TITLE HERE</h2>            <!-- PAGE TITLE -->  
 
<div id="description">                  <!-- PAGE DESCRIPTION (optional)-->
<i>to save your gifs just right click on the page & select the 'Save as..' options. This will save the entire page to your device.</i>
</div>
 
<div id="stats">                        <!-- INFORMATION -->
<p>name                 <span>NAME HERE</span></p>
<p>project              <span>PROJECT HERE</span></p>
<p>role                 <span>CHARACTER HERE</span></p>
 
<p>gif count            <span>000</span></p>
<p>dimensions           <span>000 x 000</span></p>
<p>download link        <span>DOWNLOAD LINK HERE</span></p>
</div>
 
<div id="links"><a href="/" title="back to home"><span class="th th-tumblr"></span></a><a href="/ask" title="ask a question"><span class="th th-question"></span></a><a href="https://sodapopcodes.tumblr.com/" title="theme credit"><span class="th th-settings"></span></a></div></div></div></div></div></div></div></div></div></div></div></div>
 
<div id="content">                      <!-- IMAGE URLS GO HERE-->
 
<img src="https://placehold.it/100">
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
</div>
 
</body>
<script type="text/javascript"
src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.1/jquery.min.js"></script>
<script>
$(document).ready(function() {
//
$('a.poplight[href^=#]').click(function() {
var popID = $(this).attr('rel'); //Get Popup Name
var popURL = $(this).attr('href'); //Get Popup href to define size
var query= popURL.split('?');
var dim= query[1].split('&');
var popWidth = dim[0].split('=')[1]; //Gets the first query string value
$('#' + popID).fadeIn().css({ 'width': Number( popWidth ) }).prepend('<a href="#" class="close"></a>');
var popMargTop = ($('#' + popID).height() + 80) / 2;
var popMargLeft = ($('#' + popID).width() + 80) / 2;
//Apply Margin to Popup
$('#' + popID).css({
'margin-top' : -popMargTop,
'margin-left' : -popMargLeft
});
$('body').append('<div id="fade"></div>');
$('#fade').css({'filter' : 'alpha(opacity=80)'}).fadeIn(); //Fade in the fade layer - .css({'filter' : 'alpha(opacity=80)'})
return false;
});
$('a.close, #fade').live('click', function() {
$('#fade , .popup_block').fadeOut(function() {
$('#fade, a.close').remove(); //fade them both out
});
return false;
});
});
</script>
 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script><script src="https://static.tumblr.com/iuw14ew/VSQma1786/jquery.style-my-tooltips.js"></script>
 
<script>
(function($){
$(document).ready(function(){
$("[title],a[title],img[title]").style_my_tooltips({
tip_follows_cursor:true,
tip_delay_time:90,
tip_fade_speed:600,
attribute:"title"
});
});
})(jQuery);
</script>
</html>

---
permalink: /conference/
title: "FIMH Conference"
---
<link rel="stylesheet" type="text/css" media="all" href="/_pages/conf-styles.css" />

<body id="all-content">
<div class="content" markdown="1">
<!-- end header -->
  <button id="open_button" onclick="open_convo()">&laquo; Open Conversation</button>
 <figure class="video">
  <iframe src="https://youtu.be/qvUWA45GOMg" style="min-height: calc(90vh - 254px);" width="100%" height="100%" frameborder="0" scrolling="no" allowfullscreen> </iframe>
  <br/><br/>
 </figure>
  <p style="text-align: center;">Please ask your questions using the chat box to the right of the videoor at <a href="http://www.slido.com" target="_blank"> slido.com</a> using the event code #CODE</p>
   <div class="slido wrap-collapsible" id="slido-panel" markdown="1">
   <button id="close-button" onclick="close_convo()">&raquo; Close Conversation</button>
   <figure class="content-inner"><iframe scr="https://app.sli.do/event/h0z3zaz5" style="min-height: calc(100vh - 85px);" height"100%" width="100%" style="min-height: 560px;" title="Chat window"></iframe>
   </figure>
  </div>
</div>
<!-- end content -->

    function close_convo() {
	document.getElementById("all-content").style.marginRight = "0%";
	document.getElementById("slido-panel).style.display = "none";
	document.getElementById("open_button").style.display = "block";
    }
	
    function open_convo() {
	document.getElementById("all-content").style.marginRight = "25%";
	document.getElementById("slido-panel").style.display = "block";
	document.getElementById("open_button").style.display. = "none";
    }


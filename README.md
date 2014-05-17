jQueryTouchPlugin
=================

jQuery TouchPlugin

usage

1. link jQuery
2. link vinytouch.js

============================================
short touch

$(Selector).touch(function(){console.log("hello");},"pressed style css class name");

============================================

long touch 

$(Selector).longtouch(function(){console.log("hello");},"pressed style css class name");

*. When you are pressing button , CallBack continously invoke 

  if you want to control invoke time , you have to use option like below
  

$(Selector).longtouch(function(){console.log("hello");},"pressed style css class name",{time:200});

============================================


this library tested in Android 4.0+ , iOS 4.0 + , Chrome , Safari (dont support IE , I made for Mobile Web or Mobile WebApp)


=============================================

example)

$(document).ready(function(){

	$(".btn").touch(function(){console.log("touched!!");},"btn_presss");
	
	$(".btn_long").longtouch(function(){console.log("long touched Callback!!");},"btn_presss");
	
	$(".btn_long_3000").longtouch(function(){console.log("long touched Callback!! -3000ms");},"btn_presss",{time:3000);
	
});



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
  

$(Selector).longtouch(function(){console.log("hello");},"btn_presss",{time:200});

============================================


this library tested in Android 4.0+ , iOS 4.0 + , Chrome , Safari (dont support IE , I made for Mobile Web or Mobile WebApp)



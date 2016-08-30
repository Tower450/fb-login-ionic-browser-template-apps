# fb-login-template-apps
 This is an ionic template i made for people who wants to make apps with Facebook login and their own database login.
 It makes an easy cross plate-form UI for login and Facebook Login.

I did all the architecture you need, you can customize this template and then run it without
configuring the fblogin yourself.

Setting up ngFB/OpenFB
-----------------------

In your app.js put the Facebook_ID in this method.

ngFB.init({appId: 'YOUR_FB_APP_ID'});

Running your application
------------------------

You need to add the platform you need with those command and run it(do not forget sudo for unix!).
//For Android
--------------
ionic platform add android

ionic run android

//For iOS
------------

ionic platform add ios

ionic run iOS

if you plug your device while running those command it will execute your application.


Or you can create some build .apk

ionic build ios

ionic build android

then run your .apk or iOS installer on your device

**DO NOT FORGET TO ADD THIS PLUGIN: cordova plugin add cordova-plugin-inappbrowser**

**DO NOT FORGET TO PUT THE GOOD OAuth URL redirect in developers.facebook.com in the
  facebook connexion ( left panel of the application page ) either way you will get
	AN URL ERROR OR CANNOT LOGIN by example http://localhost/oauthcallback.html**



Author: Jonathan Tourangeau

Thanks for the help of those:

https://ccoenraets.github.io/ionic-tutorial/ionic-facebook-integration.html

https://github.com/shukerullah/ionic-facebook-integration

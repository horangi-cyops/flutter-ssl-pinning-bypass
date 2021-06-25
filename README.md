# Flutter SSL Pinning Bypass
Frida script to bypass SSL Pinning on Android application built using Flutter SDK.

Reference: 
* https://blog.nviso.eu/2019/08/13/intercepting-traffic-from-android-flutter-applications/
* https://blog.nviso.eu/2020/05/20/intercepting-flutter-traffic-on-android-x64/
* https://frida.re/docs/javascript-api/

Requirement:
* Frida - https://frida.re/

How to:
* Modify variable *pattern*
* Modify variable *armversion*
* Execute: `$ frida -Ul flutter-bypass-sslpinning.js -f com.package.name --no-pause`

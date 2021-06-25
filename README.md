# horangi-android
Horangi tools for Android penetration testing

## flutter-bypass-sslpinning.js
Reference: 
* https://blog.nviso.eu/2019/08/13/intercepting-traffic-from-android-flutter-applications/
* https://blog.nviso.eu/2020/05/20/intercepting-flutter-traffic-on-android-x64/
* https://frida.re/docs/javascript-api/

How to:
* Modify variable *pattern*
* Modify *armversion*
* Save the file
* Execute: `$ frida -Ul flutter-bypass-sslpinning.js -f com.package.name --no-pause`

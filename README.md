# -esp32

# ماهي esp 32
هي عبارة عن شريحة واي فاي+بلوتوث من شركة (espressif) و هي افضل من شريحة esp8266 حيث تحتوي على الواي فاي و البلوتوث وتحتوي على وحدة المعالجة المركزية مزدوجة 32bit

يدعم ESP32 أيضًا خدمة WiFi Direct ، وهو خيار جيد للاتصال من نظير إلى نظير دون الحاجة إلى نقطة وصول . يعد إعداد WiFi Direct أسهل في الإعداد وسرعات نقل البيانات أفضل بكثير من تقنية Bluetooth

# طريقة تشغيل esp32 :
1- تثبيت الاداة في الحاسوب


2- تثبيت برنامجArduino
3-

3- مثال بسيط على الاداة 


# تثبيت الاداة على الحاسوب:


عند ايصال الاداة بالحاسب الالي سيظهر لنا اولا انها غير معروفة للجهاز

لكي تكون الاداة مثبتة وجاهزة عن طريق :

ملف التعريف ورابط تثبيت مكتبة esp32  :

https://drive.google.com/file/d/1IQmNKHLzTgl0ZZ_JNijEcCkhCLoP1lSM/view



التثبيت يكون على حسب نظام التغيل , مثلا نظام windows هل 32 او 64



# تثبيت برنامج Arduino 
https://www.alsindibad.com/136387-Arduino.html



1- نقوم بفتح واجهة البرنامج والذهاب الى tools  ثم board سيظهر لنا esp32 Arduino  نقوم باختياره



2- نقوم بعمل نسخ لرابط الـ board  ثم الى file  من اعلى الشاشة ونقوم باختيار  references ونلصق الرابط بجانب خانة addtonal boards  



3- نذهب مرة اخرى الى tools   ثم board ,  ونختار boards manager  ثم نكتب في خانة الـ type  
esp32 

4- ستظهر لنا الاداة ونقوم بعمل  install 


# مثال ( عملية البحث عنwifi )


1-سيتم البحث عن الواي فاي في الغرفة وعرضها في السريال 


2- نذهب الى tools  ونقوم باختيار الـ board   ونختار DOIT esp32 DEVKIT V1



3- نذهب الى file ثم examples  ثم wifiscan  سيظهر لنا كود wifi  وهو غير قابل للتعديل وكذلك رقم السريال


4- نضغط علامة ( + ) اعلى الصفحة لتحميل الكود


5- عند انتهاء التحميل سيطلب عمل reset  للـ board 




6- سنذهب للسريال اعلى الصفحة علامة ( المكبر ) سوف يظهر ان هناك واي فاي networks found  وايضا اسم الواي فاي

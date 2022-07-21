في هذه المحاولة سنقوم بتحويل قطعة esp32 الى access point  و نتحكم بها عن بعد من خلال الويب 

اول خطوة نقوم بتوصيل esp32

ثاني خطوة نذهب الى ملف > امثلة > wifi > نختار Wifi access point
<img scr=https://user-images.githubusercontent.com/108413904/180274734-e73467cf-f169-44b7-902b-4e1b5679c1db.png >

الان يجب ان نضيف ssid  و password لكي نتعرف على شبكة wifi الخاصة بالقطعة 

<img scr=https://user-images.githubusercontent.com/108413904/180275725-d95fb147-dd4f-44e6-ba26-8e31be40792c.png >

الان نقوم بارسال امر الى القطعة 

بعد برمجة قطعة esp32 و الاتصال بشبكة الواي فاي الخاصه به نقتح صفحة الويب الخاصة بالقطعة http://192.168.4.1/

ستظهر لنا صفحة نقدر من خلالها التحكم بتشغيل و اغلاق الضوء الخاصه بقطعة esp32 

<img scr=https://user-images.githubusercontent.com/108413904/180276795-a8d8fdb6-20dc-4c02-b1f8-e04384ec16fa.png >

<img scr=https://user-images.githubusercontent.com/108413904/180277201-788d6689-11af-42a8-b7b6-6f26bd8514e5.png >


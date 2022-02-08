# typescript
ملاحظات خلال تعلم لغة typescript
---
1- $npm init

يُنشئ الأمر npm init بلغة JSON ملف package.json للواجهة الأمامية لمشروعك. ملف package.json هو ملف يحتوي على معلومات حول حزم المشروع والاعتماديات. يحتوي أيضًا على بيانات وصفية للمشروع مثل رقم الإصدار والمؤلف والوصف. 
---
2- $npm i typescript -g
تنزيل لغة typescript
---
3- $npm i -D lite-server
يقوم lite-server بمعظم ما نريده في خادم تطوير سريع وخفيف الوزن للغاية. إنه يخدم المحتوى الثابت ، ويكشف التغييرات ، ويحدّث المتصفح عند تغيير html أو javascript  او CSS .
---
4- "start":"lite-server"
تصيف script جديد لتشغيل الخادم فى ملف package.json

---
5- شكل ال class  في ال typescript

class Program {
   PrintCounter() {
	///code
    }
}

const Counter =new Program();
---
دالة تنفذ تلقائيا عند تشغيل class
constructor(){
  ///code
}
---
إخفاء ما داخل ال (class) 
class Program {
   PrintCounter() {
	///code
    }
}

const Counter =new Program();
---








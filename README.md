# git-cheat-sheet-arabic

### الفهرس
* [الإنشاء](#الإنشاء)
* [التعديلات المحلية](#التعديلات-المحلية)
* [المؤشر](#المؤشر)
* [للتراجع](#للتراجع)
* [للحذف](#للحذف)
* [لنقل الملفات](#لنقل-الملفات)
* [التفاصيل التاريخية](#التفاصيل-التاريخية)
* [مستودع الشفيرة](#مستودع-الشفيرة)
* [للإختصارات والأسماء مسـتعارة](#للإختصارات-والأسماء-مسـتعارة)
* [للتنظيف](#للتنظيف)

##الإنشاء

##### :لإنشـاء مسـتودع فـارغ

```
$ git init 
```
##التعديلات المحلية

##### :لإضافة ملف

```
$ git add <file_name>
```
__:مثال على ذلك__
```
$ git add home.php
$ git add contact.php
$ git add admin.php
```
##### :لإضافة العديد من الملفات

```
$ git add .
```

##### :للتخزيـن الفعـلي للتعديـلات و حفظها

```
$ git commit -m 'reason here..'
```

##### : للتراجـع عـن العمليـات و التعديـلات التـي تقـوم بهـا

```
$ git commit --amend
```

__:commit مثال يوضح كيفية إضافة ملف بعد عمل__
```
$ git commit -m 'initial commit'
$ git add file.cpp
$ git commit --amend
```

##### : لعرض تفاصيل عن حالة الملفات 

```
$ git status
```

##### : للحصول على تقرير مختصر عن حالة الملفات 

```
$ git status --short
```

##### : للحصول على تقرير مختصر حول حالة المشروع والتعديلات الحالية

```
$ git status -s
```

##### : إلغاء كل التعديلات والعودة للنسخة التي كنت عليها قبل البدء في التعديل

```
$ git checkout -- <file_name>
```

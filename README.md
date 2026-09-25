# Phantoms AI — Day 1 Task Solution

## عن المشروع
تطبيق عملي لتاسك اليوم الأول، الهدف منه بناء برنامج قسمة تفاعلي ومحمي ضد أخطاء التشغيل (Robust Code) لتفادي انهيار البرنامج أثناء التنفيذ.

## تفاصيل الكود والحل
* **الدالة الأساسية (`divide_num`):** قامت بتجريد عملية القسمة لضمان إعادة استخدام الكود وتطبيق مبدأ DRY.
* **إدخال البيانات:** استقبال الأرقام من المستخدم وتحويلها لنوع `float` لدعم الأعداد الصحيحة والعشرية.
* **إدارة الأخطاء (`try-except`):**
  * التعامل مع `ValueError` في حال إدخال نصوص أو حروف بدلاً من أرقام.
  * التعامل مع `ZeroDivisionError` لمنع القسمة على صفر وإظهار رسالة توضيحية.

## المفاهيم التي تم تطبيقها
* `Python Functions & Return Values`
* `Data Type Casting (float)`
* `Exception Handling (try / except)`
* `Specific Exceptions Handling`

## طريقة التشغيل
1. افتح الملف `W1_D1_.ipynb` على Google Colab أو على جهازك.
2. قم بتشغيل الخلية الخاصة بالكود.
3. أدخل الرقم الأول ثم الرقم الثاني عند الطلب.

## تجربة المخرجات (Execution Cases)

### 1. حالة الإدخال الصحيح:
```text
Enter the first number: 4
Enter the second number: 2
The result is: 2.0
```

    
### 2. حالة إدخال قيم غير رقمية (Invalid Input):
```text
Enter the first number: abc
Invalid input! Please type numbers only.
```
### 3. حالة القسمة على صفر (Division by Zero):
```text
Enter the first number: 4
Enter the second number: 0         
You cannot divide by zero.
```             

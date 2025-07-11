
**انشاء نقطة بيع جديدة للفرع** 

<div dir="ltr">

# Document Information :

  -----------------------------------------------------------------------
  **Document Title**        انشاء نقطة بيع جديدة للفرع
  **Document Type**         User Manual
  **Author**                so Vision Teams
  **Creation Date**         20/05/2025
  **Document Version**      1.0
  **System Version**        Odoo 18
  **Target Audience**       IT Admins
  **Document Reference**    POS-OD18-UG
  **Document Sequence**     001
             
  -----------------------------------------------------------------------
</div>

<div dir="rtl">

# إنشاء نقطة بيع للشركة

1.  تأكد من الشركة التي تتبعها نقطة البيع الجديدة

2.  من القائمة الرئيسية، انتقلPoint of Sale 🡪 Configuration
    🡪 Point of Sale.

3.  اضغط على **إنشاء** **(Create)**.

4.  أدخل اسم نقطة البيع
    (مثلاً:BRKS-POS073-الملقا).

5.  اضغط على Setting لتحديد باقي اعدادات نقطة نقاط
    البيع

![image](media/media/image1.png)
----

**إعدادات نقطة البيع :**

1.  اختيار وضع المطعم is a Bar/Restaurant

2.  اختيار الجلسات Floor - والتي تمثل تطبيقات التوصيل
    المختلفة.

![image](media/media/image2.png)

> [* create Price List](pos_pricelist.md)

---
**تحديد طرق الدفع (Payment Methods)**

1.  في صفحة الاعداد نقطة البيع، انتقل إلى تبويب **الدفع**
    **(Payments)**.

2.  أضف طرق الدفع المناسبة (نقد، مدى، فيزا، أبل باي، الخ).

3.  بإمكانك إنشاء طريقة دفع جديدة من القائمة الجانبية عبر
    **Configuration -\> Payment Methods** .

4.  فعل اختيار Automatically Validate order ، لتأكيد
    الاورد في نقطة البيع بمجرد تأكيد عميلة الدفع

![image](media/media/image3.png)

>[* add Payment Methods](pos_payment_methods.md)

---

**تحديد الموظفين (Cashiers)، والشعار**

1.  في البداية لابد من أن يكون هناك موظف معرف خاص بكل
    كاشير.

2.  حدد الموظفين الذين سيستخدمون نقطة البيع للكاشير
    والمشرف.

3.  فعل اختيار Chane Logo لتحديد شعار مخصص لنقطة
    البيع

> اختار الصورة الخاصة بالشعار لنقطة البيع

4.  فعل اختيار Restrict Product Merge ، لفصل الإضافات على
    كل سطر في طلبيات البيع ، وطلب المطبخ

![image](media/media/image4.png)

----

**إضافة مركز التكلفة ، والترقيم**

1.  POS Analytic Tags :

> حدد مركز التكلفة التي تم انشاء من المالية لنقطة البيع ، اذا لم يكن
> هناك مركز تكلفة مناسب لنقطة البيع يجب انشاء من المالية
> أولاً.

2.  ادخل الرقم المناسب لبدء التسلسل الخاص بعمليات البيع في نقطة البيع
    والتي يتم بدء منه في كل مرة يتم فتح جلسة بيع جديدة.

![image](media/media/image5.png)

----

**تحديد فئات المنتجات المرتبطة بنقاط البيع : Product & POS
Categories**

1.  فعل الاختيار Restrict Categories 

2.  اختيار فئات المنتجات Pos Categories الخاص بالفرع والتي
    تحدد المنتجات التي سيتم بيعها في نقاط البيع

(اذا لم يتم تحديد فئة منتجات لن تظهر منتجات في نقاط البيع)

![image](media/media/image6.png)

----

**الضرائب Tax**

1.  تأكد من اعداد الضرائب والقيمة المضافة المعرفة على الشركة وتحديدها
    في نقاط البيع

2.  تأكد من يوميات البيع لنقطة البيع والمعرفة على الشركة

3.  تأكد من يوميات الفواتير المعرفة لنقاط البيع

> **ملحوظة** : اذا كانت هناك يوميات مختلفة يجب مراجعة المالية لإنشاء
> اليوميات المناسبة للفرع

![image](media/media/image7.png)

----

**قائمة الأسعار :**

1.  فعل اختيار Flexible Price List

2.  حدد قائمة الأسعار الذي سيتم التعامل معها في نقطة البيع

3.  حدد قائمة الأسعار الأساسية Default المستخدمة لنقطة
    البيع (البيع المحلي)

4.  حدد احتساب الضرائب (السعر شامل القيمة المضافة)
    Tax-included Price

![image](media/media/image8.png)

----
**اعداد الطباعة للإيصالات Bills & Receipts:**

1.  حدد اختيار Custom Header & Footer ، لإضافة نصوص تظهر
    في رأس وتزيل الفاتورة المطبوعة

2.  حدد اختيار الطباعة التلقائية Automatic Receipt Printing
    ، ذلك للطباعة التلقائية للفاتورة بمجرد تأكيد عملية الدفع   .

![image](media/media/image9.png)

-------------

**إضافة طابعة الكاشير ، وطباعة المطبخ**

1.  فعل اختيار ePos Printer لطابعة الكاشير

2.  ادخل رقم الـ ip الخاص بالطباعة مباشرة

3.  حدد اختيار طباعة إيصال المطبخ

4.  اختيار الاختيار Automatically After Validator للطباعة
    إيصال المطبخ تلقائي مع طباعة فاتورة العميل
   
5.  في تبويب Preparation : فعل اختيار  Preparation Printer

6.  يتم اختيار طابعات المطبخ المعرفة سابقا من شاشة
    > Orders🡪Preparation Printers

7.  من خانة internal notes : اختار الملاحظات الجاهزة
    المراد إظهارها في نقطة البيع

![image](media/media/image10.png)
[* Prepation Printers - اضافة طباعة مطبخ](prepation_printers.md)

-----

**تحديد المخزن المرتبط بنقطة البيع**

من التبويب inventory قم باختيار Operation Type
الخاص بنقطة البيع والمعرفة مسابقة من إدارة المخازن

![image](media/media/image11.png)

</div>

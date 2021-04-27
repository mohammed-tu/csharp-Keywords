<div dir="rtl">

# out

تستخدم لإرسال البيانات باستخدام المرجع " reference " 

- لا تشترط حفظ قيمة مسيقة للعنصر المرسل 
- لكن تشترط وجود قيمة له قبل الخروج من الدالة  

**مثال**

<div dir="ltr">
  
```
        public static void Main()
        {

            int x ;
            useout(out x);
            Console.WriteLine(x); // x = 11

        }

        static int useout(out int x)
        {

            x = 9 + 2;
            return x;
        }
```

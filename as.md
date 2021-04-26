<div dir="rtl">

# as

يستخدم لتحويل بين انواع بيانات ال reference type المتوافقه وفي حال انه لم يستطع يقوم يإرجاع القيمة null

**مثال**

<div dir="ltr">

```
            string str1 = "hi";

            object obj1 = str1;

            string str2 = obj1 as string;

            if (str2 != null)
            {
                Console.WriteLine("Successfully Cast");
            }
            Console.WriteLine(str2);
```

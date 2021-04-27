<div dir="rtl">

# foreach

تستخدم للمرور على كل عنصر من النوع المدخل اليها 

- كل حرف في النص 
- كل عنصر بالمصفوفة او القائمة


**أمثلة**

<div dir="ltr">


```

            string text = "hi Mohammed";
            foreach (var item in text)
            {
                Console.WriteLine(item);
            }
```

```
            int[] nums = { 4, 2, 7, 4, 2, 5, 6 };
            foreach (var item in nums)
            {
                Console.WriteLine(item);
            }
```

<div dir="rtl">

# enum

تستخدم لتعريف الثوابت والتعامل معها بأكثر من طريقة بشكل سهل للقراءة

**مثال**

<div dir="ltr">

```csharp
        enum Months {
        Jan,Feb,Mar,Apr,May,Jun,Jul,Aug,Sep,Oct,Nov,Dec
		}

            Months m1 = Months.May;
            Console.WriteLine(m1); // Output May
            Console.WriteLine(Months.Jan); // Jan
            Console.WriteLine((Months)3); //Apr
```

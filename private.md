<div dir="rtl">

# private

يُمكّن الوصول للبيانات أو الدوال داخل الكلاس فقط ولا يسمح الوصول لها من أي مكان اخر

**مثال**

<div dir="ltr">

```
    public class ClassA
    {
        private int num = 8;

        public void print()
        {
            Console.WriteLine(num);
        }
    }

    public class ClassB : ClassA
    {
        public void printFromB()
        {
            Console.WriteLine(num); // هنا يصدر خطأ البرنامج
        }
    }
```

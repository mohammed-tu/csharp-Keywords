<div dir="rtl">

# protected

يُمكّن الوصول للبيانات أو الدوال داخل الكلاس أو أحد أبنائه

**مثال**

<div dir="ltr">

```
    public class ClassA
    {
        protected int num = 8;

        public void print()
        {
            Console.WriteLine(num);
        }
    }
    public class ClassB : ClassA
    {
        public void printFromB()
        {
            Console.WriteLine(num);
        }
    }
```

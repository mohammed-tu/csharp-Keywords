<div dir="rtl">

# this

تستخدم للدلالة على ال object الحالي للكلاس

**مثال**

<div dir="ltr">

```csharp

    class Program
    {
        static void Main(string[] args)
        {
            ClassA s = new ClassA();
            s.print();
        }
    }

    public class ClassA
    {
        public int num = 7;

        public void print()
        {
            Console.WriteLine(this.num);
        }
    }
```

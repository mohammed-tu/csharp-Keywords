<div dir="rtl">

# public

يُمكّن الوصول للبيانات أو الدوال من أي مككان

**مثال**

<div dir="ltr">

```
public class ClassA
    {
        public int num = 8;

        public void print()
        {
            Console.WriteLine(num); // من خلال الكلاس نفس
        }
    }

    public class ClassB : ClassA
    {
        public void printFromB()
        {
            Console.WriteLine(num); // من خلال الكلاس الابن
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            ClassA a = new ClassA();

            Console.WriteLine(a.num); // من خلال الدالة الرئيسية
        }
    }
```

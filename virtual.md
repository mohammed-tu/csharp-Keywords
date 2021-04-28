<div dir="rtl">

# virtual

تستخدم مع الدوال في ال class الأب لإتاحة التعديل على محتوى الدالة في ال class الابن

**مثال**

<div dir="ltr">

```
    public class ClassA
    {
        public virtual void print() // الدالة قابلة للتعديل
        {
            Console.WriteLine("Hi from A");
        }
    }
    public class ClassB : ClassA
    {
        public override void print()
        {
            Console.WriteLine("Hi from B");
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            ClassA a = new ClassA();
            a.print();
            ClassB b = new ClassB();
            b.print();

        }
    }
```

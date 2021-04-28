<div dir="rtl">

# override

تستخدم مع الدوال لإجراء التعديلات في دوال تحمل نفس الاسم في كلاسات تمت الوراثة منها

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
        public override void print() /*الدالة تعدل على الدالة الموجودة في الكلاس الأب */
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

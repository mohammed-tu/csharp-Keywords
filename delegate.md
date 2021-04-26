<div dir="rtl">

# delegate

keyword تستخدم مع الدوال للتعامل معها كمتغيرات في البرنامج 

**مثال**

<div dir="ltr">

```
        delegate int myDel(int a, int b);

        static int add(int a, int b)
        {
            return a + b;
        }
        static int sub(int a, int b)
        {
            return a - b;
        }
        static void Main(string[] args)
        {
            myDel a = add;
            myDel s = sub;
            Console.WriteLine(a(1,4));
            Console.WriteLine(s(1, 4));

        }
```

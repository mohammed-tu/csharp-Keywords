<div dir="rtl">
  
  # ref
  
  هي keyword تستخدم لتمرير القيمة لدالة معينة بالستخدام المرجع " reference " بحيث تتغير قيمة العنصر المُرسل بعد الرجوع من الدالة 
  - يشترط نخزين قيمة للعنصر قبل ارساله للدالة 
  
  
  **مثال**
  
  </dif>
  
<div dir="ltr">
  
  
  ```
        public static void Main()
        {/*
            int x = 3;
            Console.WriteLine(x); // x = 3
            doublex(ref x);
            Console.WriteLine(x); // x = 6

        }

        static int doublex(ref int x)
        {
            x = x * 2;
            return x;
        }
  ```

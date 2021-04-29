<div dir="rtl">

# params

تستخدم لتمرير عدة مُعاملات من النوع نفسه للدالة

- لا تشترط تحديد عدد المعُاملات
- يجب أن تكون آخر من يمرر للدالة

**مثال**

<div dir="ltr">

```csharp
         static void Main(string[] args)
        {
            parm(1, 3, 4, 6, 7, 8, 4, 2, 4);
        }

        static void parm(params int[] nums)
        {
            for (int i = 0; i < nums.Length; i++)
            {
                Console.Write(nums[i]+ " " ); // 1 3 4 6 7 8 4 2 4
            }
            Console.WriteLine();
        }

```

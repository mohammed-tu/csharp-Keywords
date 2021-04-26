<div dir="rtl">

# class 

Keyword لتصنيف عدة بيانات ودوال في مكان واحد ، بحيث يكون الوصول اليها عن طريق عدة نسخ من object 
وجدت هذه ال Keyword لصنع نوع بيانات حسب الطلب 

*مثال*
هنا نريد صنع نوع بيانات من النوع car بحيث كل ما تم إنشاءه تُعرف اسم السيارة وحجمها ولونها مع إمكانية طباعة المعلومات الخصة بها 

<div dir="ltr">

```
public  class Car
    {
        public string carName;
        public string carSize;
        public string carColor;

        public Car(string name, string size, string color)
        {
            carName =name;
            carSize = size ;
            carColor= color;

        }
        public void printInfo()
        {
            Console.WriteLine("car name : {0}\ncar size : {1}\ncar color : {2}\n",carName,carSize,carColor);
        }
    }
    class Program
    {

        static void Main(string[] args)
        {
            Car c1 = new Car("Ford", "Snall", "black");
            c1.printInfo();      
        }
    }
```

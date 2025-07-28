## prec-1

namespace
shalvi.net
{ internal class Program { static void Main(string[] args) 
{ Console.WriteLine("Shalvi Aghera ");
Console.WriteLine("My course name is BCA");
}
}
}
OUTPUT:
<img width="348" height="65" alt="image" src="https://github.com/user-attachments/assets/2ad2fb65-77eb-4f96-84ac-1bbdf46df03f" />

##prec-2

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = 10;
            double f = 5.67;
            char c = 'B';
            string s = "C#";
            bool flag = true;

            Console.WriteLine(num);
            Console.WriteLine(f);
            Console.WriteLine(c);
            Console.WriteLine(s);
            Console.WriteLine(flag);
        }
    }
}
OUTPUT:<img width="213" height="157" alt="Screenshot 2025-07-28 163422" src="https://github.com/user-attachments/assets/7c2e60c3-e06a-4308-935e-5fc1602be4dc" />

##prec-3 
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net { internal class Program { static void Main(string[] args) { int num = 002;
            double result = num;
            Console.WriteLine("Integer value: " + num);
            Console.WriteLine("Double value after implicit conversion: " + result);
            Console.ReadLine();
        }
    }
}  


OUTPUT:<img width="617" height="140" alt="image" src="https://github.com/user-attachments/assets/2c644c28-c92f-4092-a4c1-a02c99545c2e" />

##prec-4
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net { internal class Program { static void Main(string[] args) 
        { int num = 002; int result = (int)num; 
            Console.WriteLine("Integer value: " + num); 
            Console.WriteLine("Int value after explicit conversion: " + result); 
            Console.ReadLine(); 
        }
    } 
}

<img width="542" height="162" alt="image" src="https://github.com/user-attachments/assets/687eb5d8-ddc5-4338-afb2-be8692d3096b" />

##prec-5
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net { 
     internal class Program { static void Main(string[] args) 
        { Console.Write("Enter marks of Subject 1: ");
            int marks1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter marks of Subject 2: "); 
            int marks2 = Convert.ToInt32(Console.ReadLine()); 
            int total = marks1 + marks2; 
            Console.WriteLine("Total Marks: " + total);
            Console.ReadLine(); 
        }
    }
}
##Prec-6
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net
{  internal class Program 
    { static void Main(string[] args) { int price1 = 100; int price2 = 200; 
            Console.WriteLine("Before Swapping"); 
            Console.WriteLine("Price1 = " + price1); 
            Console.WriteLine("Price2 = " + price2); 
            int temp = price1; price1 = price2; price2 = temp;
            Console.WriteLine("After Swapping"); 
            Console.WriteLine("Price1 = " + price1); 
            Console.WriteLine("Price2 = " + price2); 
            Console.ReadLine(); 
        } 
    }
}
OUTPUT:
<img width="232" height="207" alt="image" src="https://github.com/user-attachments/assets/d7a1c6a8-39b8-465d-95b8-a7ee015d0fb1" />

##Prec-7
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net
{ internal class Program 
    { static void Main(string[] args) 
        { Console.Write("Enter your roll number: "); 
            int rollNumber = Convert.ToInt32(Console.ReadLine()); 
            if (rollNumber % 2 == 0) { Console.WriteLine("The roll number is Even.");
            }
            else { Console.WriteLine("The roll number is Odd.");
            }
        } 
    } 
}
OUTPUT:
<img width="395" height="116" alt="image" src="https://github.com/user-attachments/assets/ebaea0aa-ada8-4e5b-9e8a-83d91f7eb1da" />

##Prec-8
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net
{ internal class Program
    { static void Main(string[] args)
        { Console.Write("Enter the side length of the square: "); 
            int side = Convert.ToInt32(Console.ReadLine());
            int area = side * side;
            Console.WriteLine("Area of the square: " + area); 
        } 
    } 
}


OUTPUT:
<img width="473" height="95" alt="image" src="https://github.com/user-attachments/assets/f20f521c-53db-4b11-9d62-f882afb89cc5" />

##Prec-9
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net
{ internal class Program 
    { static void Main(string[] args)
        { int number = 42; object boxedNumber = number; 
            Console.WriteLine("Original int value: " + number);
            Console.WriteLine("Boxed object value: " + boxedNumber);
            Console.ReadLine();
        } 
    }
}
<img width="343" height="172" alt="image" src="https://github.com/user-attachments/assets/a0a8c925-9463-4bba-8fc0-8fae5cfda2ec" />

##Prec-10
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net
{ internal class Program 
    { static void Main(string[] args)
        { object boxedValue = 100; 
            int number = (int)boxedValue; 
            Console.WriteLine("Boxed object value: " + boxedValue);
            Console.WriteLine("Unboxed int value: " + number); 
            Console.ReadLine(); 
        } 
    } 
}
OUTPUT:<img width="317" height="116" alt="image" src="https://github.com/user-attachments/assets/7df6769b-6279-4dcc-a61e-83ca17e4c5a1" />

##prec-11
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Shalvi.net
{ internal class Program
    { static void Main(string[] args) 
        { Console.Write("Enter your age: "); 
            int age = Convert.ToInt32(Console.ReadLine());
            if (age >= 18) { Console.WriteLine("You are eligible to vote."); 
            } 
            else { Console.WriteLine("You are not eligible to vote.");
            } Console.ReadLine(); 
        } 
    }
}


OUTPUT:
<img width="331" height="100" alt="image" src="https://github.com/user-attachments/assets/aa3c2e02-7d82-4a2b-8dae-ba78201b01ad" />



# multiple-inheritance
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace inheritance
{
   class student 
 {
    public void info()
{
   string name = "komal";
   string Class = "sybca";
Console.WriteLine("student name :-" +
name);
Console.WriteLine("Class :-"+ Class);
   }
}
  interface exam
{
 void mak();
  }
class result:student,exam
 {
 public void mak()
 {
string subject = "c#.net";
int marks = 28;
Console.WriteLine("subject:-" + subject);
Console.WriteLine("marks :-"+ marks);
    }
 static void Main(string[] args)
{
   result obj = new result();
obj.info();
obj.mak();
Console.ReadLine();
}
 } 
}

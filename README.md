# Creacion-de-token-de-seguridad-VisaNet-PE-C\#


```cs

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Text.RegularExpressions;

namespace Rextester
{
    public class Program
    {
        public static void Main(string[] args)
        {
            string credentials = Convert.ToBase64String(ASCIIEncoding.ASCII.GetBytes("USER" + ":" + "PASS"));
            
            //Your code goes here
            Console.WriteLine(credentials);
        }
    }
}
```

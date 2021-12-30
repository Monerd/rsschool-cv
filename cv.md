# Nemkovich Nikita
## Contact information
***Phone:*** +375 (44) 767-98-41  
***Mail:*** nemkovich.nikitka@gmail.com  
***GitHub:*** [Monerd](https://github.com/Monerd/)  
***Linkedin*** [Nemkovich Nikita](https://www.linkedin.com/in/nikita-nemkovich-805927227/)  
## About me
I am an *optimistic*, *sociable* and *responsible* person.  
I *always* strive for knowledge in order to gain experience in any field.  
I study at the Belarusian State University of Informatics and Radioelectronics.  
My goal now is to become a *software and front-end developer*.  
## Skills
- Git, GitHub  
- JavaScript  
- HTML  
- CSS  
- C#  
## Languages
- Russian (Native)  
- Belarusian (Native)  
- English (A2)  
## Code Examples
**Task:**  

> **Codewars (7 kyu) "Two to one":** Take 2 strings s1 and s2 including only letters from ato z. Return a new sorted string, the longest possible, containing distinct letters - each taken only once - coming from s1 or s2.  

**Solution:**
``` C#
using System;
using System.Linq;

public class TwoToOne 
{
  public static string Longest (string s1, string s2) 
  {
    var s3 = (s1 + s2).ToCharArray();
    Array.Sort(s3);
    return String.Join("",s3.Distinct());
  }
}
```
## Education
2019 - cur. BSUIR (Belarusian State University of Informatics and Radioelectronics)  
2021 - cur. RS School (The Rolling Scopes School)  
## Projects
[Laboratory from university](https://github.com/Monerd/Labs-Software-Design)

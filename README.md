# Text Calculator

Text calculator component for .Net
## Example

```c#
using ParsElecom.NCalc;

Expression exp = new Expression("(x+y)/z");
exp.Parameters.Add("x", 5);
exp.Parameters.Add("y", 3);
exp.Parameters.Add("z", 2);

Console.WriteLine(exp.Evaluate());
```



![](http://visit.parselecom.com/Api/Visit/16/DE4C8A)

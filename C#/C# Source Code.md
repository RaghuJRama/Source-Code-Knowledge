# C# Source Code


## Building strings with StringBuilder
### String Concatenation

```cs
var stringOne = "Hello ";
var stringTwo = "I love you ";
var stringThree = "Won't you tell me your name?";

Console.WriteLine(stringOne + stringTwo + stringThree);
```

###  String Builder

##### Example 1

```cs
var sb = new StringBuilder();
sb.Append("It was the best of times, it was the worst of times");
sb.Append("it was the age of wisdom");
sb.Append("it was the age of foolishness");
Console.WriteLine(sb.ToString());
```
##### Example 2

```cs
sb = new StringBuilder("It was the best of times, it was the worst of times");
Console.WriteLine(sb.ToString());

sb.AppendLine("it was the age of wisdom");
sb.AppendLine("it was the age of foolishness");
Console.WriteLine(sb.ToString());
```

##### Example 3

```cs
sb = new StringBuilder();
sb.AppendLine("It was the best of times, it was the worst of times");
sb.AppendLine("it was the age of wisdom");
sb.AppendLine("it was the age of foolishness");
Console.WriteLine(sb.ToString());
```

####### output
```cs
It was the best of times, it was the worst of times
it was the age of wisdom
it was the age of foolishness

```
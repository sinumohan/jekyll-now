---
layout: post
title: Hello World
---
Hello world is a simple program that, when run displays the message "Hello world", here I have collected few programming languages and simple hello world programs on them. Feel free to give feed backs.

JavaScript
{% highlight javascript %}
console.log("Hello World")
{% endhighlight %}

Python
{% highlight python %}
print "Hello World"
{% endhighlight %}

C
{% highlight c %}
#include <stdio.h>

int main()
{
	printf("Hello world");
	return 0;
}
{% endhighlight %}

C++
{% highlight c %}
#include <iostream>

int main()
{
	std::cout <<"Hello world\n";
	return 0;
}
{% endhighlight %}


go
{% highlight go %}
package main  
import "fmt"  
func main() {  
   fmt.Println("Hello, World")  
} 
{% endhighlight %}


Java
{% highlight java %}
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }
} 
{% endhighlight %}

c#
{% highlight c# %}
namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
             Console.WriteLine("Hello, world!");
        }
    }
}
{% endhighlight %}

lisp
{% highlight lisp %}
(write-line "Hello World")
{% endhighlight %}


basic
{% highlight basic %}
PRINT "Hello World";
{% endhighlight %}

pascal
{% highlight pascal %}
program Hello;
begin
  writeln ('Hello, world.');
end.
{% endhighlight %}

perl
{% highlight perl %}
#!/usr/bin/perl
use warnings;
print("Hello World\n");
{% endhighlight %}

Haskell
{% highlight Haskell %}
main = putStrLn "Hello, World!"
{% endhighlight %}


REXX
{% highlight rexx %}
/* Sample REXX Program */
SAY 'Hello world!'
{% endhighlight %}

F#
{% highlight F# %}
open System
[<EntryPoint>]
let main argv =
    printfn "Hello World from F#!"
    0 // return an integer exit code
{% endhighlight %}

Nemerle
{% highlight Nemerle %}
System.Console.WriteLine("Hello, world!");
{% endhighlight %}

Kite
{% highlight Kite %}
eval "\"hello, world!\"|print;";
{% endhighlight %}

Shell Script
{% highlight Shellscript %}
echo Hello World
{% endhighlight %}
You can use three or more backticks (or tildes) to denote code blocks.
If you want to display backticks (or tildes), use the other to start and end the code block:

```
This is a code block.
   White space gets preserved.
   
   function testCodeBlock() {
     // do something here
   }
```

Here's a code block that displays code block markup:

~~~
```
  some;
    code;
      here;
```
~~~

This is the markup for the code block above (we had to use four backticks to start and end this one):

````
~~~
```
  some;
    code;
      here;
```
~~~
````

You can also do language syntax highlighting with backtick code blocks.
Language support and abbreviations vary across platforms, but `java`, `c`, `python`,
and `go` are usually valid. Just add the language immediately after the opening ticks.
For example, <code>```go</code>:

```go
package main

import "fmt"

func main() {
	  fmt.Println("Hello, 世界")
}
```

Or <code>```java</code>:


```java
public class HelloWorld {

    public static void main(String[] args) {
        // Prints "Hello, World" to the terminal window.
        System.out.println("Hello, World");
    }

}
```

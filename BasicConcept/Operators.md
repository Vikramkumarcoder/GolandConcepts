# Arithmetic Operators
## In this section, we will learn about operators

```go
package main

import "fmt"

func main() {
    x := 10
    y := 5
    
    // Addition
    fmt.Println(x+y)
    
    // Subtraction
    fmt.Println(x-y)
    
    // Multiplication
    fmt.Println(x*y)
    
    // Division
    fmt. Println(x/y)
    
    // Modulus: result in remainder of the division
    fmt. Println(x%y)
    
    //The process of adding together strings is called string concatenation.
    p := "vikramkumar"
    q := "coder"
    fmt.Println(p + q)

}
```

# Relational Operator

- Relational operators are used to compare two values and return a bool as the result: true when the comparison condition holds, and false when it does not.

```go
package main

import "fmt"

func main() {
    x:=10
    y:=2
    
    // equal to
    fmt.Println(x == y)
    
    // not equal to
    fmt.Println(x != y)
    
    // greater than
    fmt.Println(x > y)
    
    // less than
    fmt.Println(x < y)
    
    // greater than or equal to
    fmt.Println(x >= y)
    
    // less than or equal to
    fmt.Println(x <= y)

}
```

# Logical Operators

- Logical operators are used to combine two or more conditions.

- The logical AND && operator returns true only when both conditions are true. 

- The logical OR || operator returns true when one (or both) of the conditions are true.

- The logical NOT ! operator returns true when the condition is false (basically reversing the result of the condition).

```go
package main

import "fmt"

func main() {
    x := 55
    y := 9
    
    // logical AND
    fmt.Println(x!=y && x<=y)
    
    // locial OR
    fmt.Println(x!=y || x<=y)
    
    // logical NOT
    fmt.Println(!(x>y))
    
    // Multiple Combination
    fmt.Println((x>0 && x<100) || x==55)

}
```

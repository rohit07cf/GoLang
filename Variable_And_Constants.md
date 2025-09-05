<h><b>Variables</b></h>
```go
package main

import "fmt"

func main() {
    var age int = 25
    var name string = "Rohit"
    
    fmt.Println("Name:", name)
    fmt.Println("Age:", age)
}
```
2. Short Declaration (Type Inference)

Go can automatically detect the type of the variable, so you don’t always need to explicitly declare the type.
```go
package main

import "fmt"

func main() {
    age := 25      // type inferred as int
    name := "Rohit" // type inferred as string
    
    fmt.Println(name, "is", age, "years old")
}
```

3. Multiple Variable Declaration

You can declare multiple variables in one line.
```go
package main

import "fmt"

func main() {
    var x, y, z int = 1, 2, 3
```

4. Zero Values

If you declare a variable without initializing, Go assigns a default zero value depending on the type:
```go
package main

import "fmt"

func main() {
    var number int
    var name string
    var status bool

    fmt.Println(number, name, status) // 0 "" false
}
```

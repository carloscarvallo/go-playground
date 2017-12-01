# Go Playground

### Type Inference

Data type is inferred during assignment.

The := operator tells Go to **automatically find out the data type** on the right being assigned to the **newly declared variable** on the left. This is know as **type inference**

### Manual Type Declaration
Data type is declare prior to assignment

### Slice literals
A *slice **literal** is a quick way to create slices with initial elements via type inference. We can pass elements between curly braces {}.

``` go
package main

import "fmt"

func main() {
    var langs []string{"Go", "Ruby", "Javascript"}
    fmt.Println(langs)
}
``` 
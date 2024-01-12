<h1 align="center">Profile</h1>
<h3 align="center">Simple site to group all my profiles on social networks in one place.</h3>


## About the project

This is an open source project that serves as a free alternative to the Linktree website.
- [Demo](https://u7p4l-in.github.io/Profile/)


## 👨‍💻 Quotes:
```go
package main

import "fmt"

type Person struct {
  name string
  username string
  age int
  hobbies []string
  job string
}

func main() {
  var me = new(Person)
  
  me.name     = "U7P4L 1N"
  me.username = "U7P4L-IN"
  me.age      = "20"
  me.job      = "ai developer | web developer"
  me.hobbies  = []string{"code", "anime", "music"," singing"}
  
  fmt.Println(me)
}
```

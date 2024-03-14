### Hello Traveller 👋🏻
```go
package main

import "fmt"

type Snowy struct {
    name      string
    langs     []string
    interests []string
}

func (s Snowy) Greet() { fmt.Printf("🎀 Hello, I'm %s! 🎀\n", s.name) }

func main() {
    snowy := Snowy{"Snowy",
        []string{"Go", "Python", "Java", "Kotlin", "Golang", "Dart", "JavaScript"},
        []string{"🐱 Cats", "🐾 Kittens", "💡 Tinkering for new ideas"}}

    snowy.Greet()
}
```

# 👋 Hey there, I'm Highlander Paiva! 🇧🇷

```go
package main

import "fmt"

type Developer struct {
    Name       string
    Role       string
    Country    string
    CurrentJob string
    Hobbies    []string
    Goal       string
}

func main() {
    highlander := Developer{
        Name:       "Highlander",
        Role:       "Backend Developer",
        Country:    "Brazil",
        CurrentJob: "Software Engineer SSr",
        Hobbies:    []string{"Exploring 'Go way' programming", "Building cool Go projects"},
        Goal:       "Software Architect",
    }

    for {
        code(highlander)
    }
}

func code(dev Developer) {
    fmt.Printf("%s is coding...\n", dev.Name)
}
```

<details>

<summary>Kotlin</summary>


```kotlin
data class Developer(
    val name: String,
    val role: String,
    val country: String,
    val currentJob: String,
    val hobbies: List<String>,
    val goal: String
)

fun main() {
    val highlander = Developer(
        name = "Highlander",
        role = "Backend Developer",
        country = "Brazil",
        currentJob = "Software Engineer SSr",
        hobbies = listOf("Exploring OOP programming", "Building cool Kotlin projects"),
        goal = "Software Architect"
    )

    while (true) {
        code(highlander)
    }
}

fun code(dev: Developer) {
    println("${dev.name} is coding...")
}
```

</details>

<details>

<summary>Haskell</summary>


```haskell
data Developer   = Developer
    { name       :: String
    , role       :: String
    , country    :: String
    , currentJob :: String
    , hobbies    :: [String]
    , goal       :: String
    }

code :: Developer -> IO ()
code dev = putStrLn $ name dev ++ " is coding..."

main :: IO ()
main = do
    let highlander = Developer
            { name       = "Highlander"
            , role       = "Backend Developer"
            , country    = "Brazil"
            , currentJob = "Software Engineer SSr"
            , hobbies    = ["Exploring functional programming", "Building cool Haskell projects"]
            , goal       = "Software Architect"
            }
    
    let loop = do
          code highlander
          loop
    loop
```

</details>

🚀 Backend Developer from Brazil, Software Engineer SSr at [Mercado Livre](https://www.mercadolivre.com.br/), and **_Haskell_** enthusiast on the side! I'm on the path to become a **Software Architect** and love creating **Kotlin** libs and personal projects in my spare time. 🎯

Feel free to ask me about anything, I'm happy to help! 😄

<br/><br/>

## 🎬 Fun fact
My name is based on the movie **[Highlander (1986)](https://m.imdb.com/title/tt0091203/)**. There can be only one! ⚔️

<br/><br/>

## 📫 Get in touch

- 🔗 LinkedIn: [Highlander Paiva](https://www.linkedin.com/in/hvpaiva)

<br/><br/>

## 🛠️ My toolbox

[![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)
[![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![Haskell](https://img.shields.io/badge/-Haskell-5D4F85?style=for-the-badge&logo=haskell&logoColor=white)](https://www.haskell.org/)
[![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/)

<!-- https://github.com/Ileriayo/markdown-badges -->

```go
package main

import "fmt"

func main() {
    myStack := []string{"Kotlin", "Go", "Haskell", "Java", "Spring"}
    fmt.Printf("Highlander stacks: %s\n", strings.Join(myStack, ", "))
}
```

<details>

<summary>Kotlin</summary>

```kotlin
fun main() {
    val myStack = listOf("Kotlin", "Go", "Haskell", "Java", "Spring")
    println("Highlander stacks: ${myStack.joinToString(", ")}")
}
```

</details>

<details>

<summary>Haskell</summary>

```haskell
import Data.List (intercalate)

main :: IO ()
main = do
    let myStack = ["Kotlin", "Go", "Haskell", "Java", "Spring"]
    putStrLn $ "Highlander stacks: " ++ intercalate ", " myStack
```

</details>

<br/><br/>


## 💻 Coding Activity

<br/>

<div align="center">
  <a href="https://github.com/hvpaiva">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=hvpaiva&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hvpaiva&layout=compact&langs_count=5&theme=dark&&hide=javascript,typescript,vue,html"/>
</div>

<br/>

**Keep exploring, learning, and having fun! 🌟**

# About Me


<!-- - 🔭 I’m currently working on ...  -->
- 🌱 I’m currently learning `Golang` and `Jetpack Compose`
<!-- - 👯 I’m looking to collaborate on ... -->
<!--- 🤔 I’m looking for help with ... -->
<!-- - 💬 Ask me about ... -->
- 📫 How to reach me: lv2410@gmail.com
- 😄 Pronouns: Nolions
- ⚡ Fun fact: Program, Baesball and model

```
package main

import "fmt"

type Person struct {
	Name         string
	Email        string
	Position     string
	CurrentFocus string
	Program      Program
}

type Program struct {
	Skills   []string
	Learning []string
	Tools    []string
}

func main() {
	var me Person
	me.Name = "Nolions Chen"
	me.Email = "lv2410@gmail.com"
	me.Position = "Backend Engineer"
	me.CurrentFocus = "https://github.com/Nolions/"
	me.Program = Program {
		Skills: []string{"Golang", "Kotlin", "Android", "PHP", "Laravel"},
		Learning: []string{"Blockchain", "Jetpack Compose", "Compose Multiplatform", "Golang", "Clean Code", "Design Patterns"},
		Tools: []string{"PHPStorm", "Goland", "IntelliJ Idea", "Vscode"},
	}
	
	fmt.Println(me)
}
```

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nolions&theme=dark)](https://github.com/Nolions)

[![Nolions's GitHub stats](https://github-readme-stats.vercel.app/api?username=nolions&show_icons=true&theme=radical&include_all_commits=true)](https://github.com/Nolions)

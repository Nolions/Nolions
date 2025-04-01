# About Me

### 😄 Hi I‘m Nolions. I am a Software Engineer, focus on `Backend`.


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
	me.Program = Program{
		Skills:   []string{"Go", "Java", "Kotlin", "Android", "PHP", "Laravel"},
		Learning: []string{"Go", "PHP", "Java", "Kotlin", "CICD", "Clean Code", "Design Patterns"},
		Tools:    []string{"PHPStorm", "Goland", "IntelliJ Idea", "Vscode"},
	}

	fmt.Println(me)
}

```

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nolions&theme=dark)](https://github.com/Nolions)

[![Nolions's GitHub stats](https://github-readme-stats.vercel.app/api?username=nolions&show_icons=true&theme=radical&include_all_commits=true)](https://github.com/Nolions)

[![Leetcode Stats](https://leetcard.jacoblin.cool/nolions)](https://leetcode.com/nolions/)


## Hi, I'm Godless 👋

```Go
package main

import "fmt"

type Godless struct {
	Name              string
	Languages         []string
	FavouriteLang     string
	CurrentlyLearning string
	CurrentCompany    string
	Age               int
	StudyAt           string
	Resume            string
}

func NewGodless() *Godless {
	return &Godless{
		Name:              "Godless",
		Languages:         []string{"C#", "C++", "C", "Go"},
		FavouriteLang:     "Go",
		CurrentlyLearning: "Go",
		CurrentCompany:    "Recovery Toolbox Inc.",
		Age:               21,
		StudyAt:           "HSE'27",
		Resume:            "gxdlxsss.ru",
	}
}

func (g *Godless) Welcome() {
	fmt.Printf("Hi, I'm %s. I've lost my god\n", g.Name)
}

func main() {
	me := NewGodless()
	me.Welcome()
}
```

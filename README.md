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
}

func NewGodless() *Godless {
	return &Godless{
		Name:              "Godless",
		Languages:         []string{"C#", "C++", "C", "Go"},
		FavouriteLang:     "Go",
		CurrentlyLearning: "Go",
		CurrentCompany:    "Recovery Toolbox Inc.",
		Age:               18,
		StudyAt:           "Central University'28/MIPT'28",
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

# Zhulien Zhelev

<h2 align="center">About me</h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                   I want to learn everything about programming. I love sports and walking in nature.
		"- 🌱 I’m currently learning":       C#
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  C#, 
		"- 📫 How to reach me:":              "https://github.com/Jelev123
	}
}
```

<p align="center"><img src="https://thumbs.gfycat.com/GoodnaturedFondGaur-size_restricted.gif" alt="Synthwave" height="300" width="500"></p>



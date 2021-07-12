
![image](https://user-images.githubusercontent.com/47543672/125258801-f9799f00-e2fe-11eb-9e65-f71c3f695327.png)

Hi ![image](https://user-images.githubusercontent.com/47543672/125258910-157d4080-e2ff-11eb-8ce1-8a2817447e28.png), I am Bernd Hansel


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
		"- ⚡ Quick bio:":                    ""
		"- 🔭 I’m currently working on":      "I’m currently doing a Full-Stack Web Developer",
		"- 🌱 I’m currently learning":        "Golang, MongoDB, RabbitMQ, K8s, GCP (Tech stack from my company) --- Sharpening my Front End Skills for the MERN stack (Personal goal)",
		"- 👯 I’m looking to collaborate on": "JS, React, Node.js, Typescript, SASS related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		
	}
}







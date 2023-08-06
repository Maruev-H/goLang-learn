package main

import "fmt"

type Human struct {
	Name      string
	age       uint8
	Weight    uint16
	HairColor string
}

func main() {
	me := Human{
		Name:      "Habib",
		age:       18,
		Weight:    90,
		HairColor: "Brown",
	}

	fmt.Print(me)
}

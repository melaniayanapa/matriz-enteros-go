package main

import "fmt"
func ordenarMariz(){
 	var mat[12]int
    for f :=0 ; f < 12;f++ {

            fmt.Print("Ingrese numero:")
            fmt.Scan(&mat[f])

    }
    fmt.Println("Impresión de la matriz completa")
    fmt.Println(mat)
    fmt.Println("Impresión elemento a elemento")
    for f := 0; f < 12;f++ {
            fmt.Print(mat[f], " ")
        }

tmp := 0
    for x := 0; x < 12; x++ {
        for y := 0; y < 12; y++ {
            if mat[x] < mat[y] {
                tmp = mat[x]
                mat[x] = mat[y]
                mat[y] = tmp
            }
        }
    }
    fmt.Print("\nArray ordenado: ")
    for i := 0; i < 12; i++ {
        fmt.Print("[",mat[i],"]")
    }
    fmt.Println()
}
    func rutinas(matriz[]int) {
    	tam := len(matriz)/4
    	go mat(matriz[:tam])
    	go mat(matriz[tam:tam*2])
    	go mat(matriz[tam*2:tam*3])
    	go mat(matriz[tam*3:])
    	mat(matriz)

    }



func main() {
		ordenarMariz()
    rutinas(slice)
    temp.Wait()


}

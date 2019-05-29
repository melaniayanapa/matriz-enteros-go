package main

import "fmt"
func ordenarMariz(){
 	var mat [12]int
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
func DESORDENADA(numerodesorden[]int){

 	var tempo  int
	for i := 0; i < len(numerodesorden); i++ {
	  	for j := 0; j < len(numerodesorden); j++ {
	   		if numerodesorden[i] > numerodesorden[j] {
	    		tempo = numerodesorden[i]
	    		numerodesorden[i] = numerodesorden[j]
	    		numerodesorden[j] = tempo
	   		}
	  	}
	}
	mostrar_array(numerodesordenada)
	temp.Done()
}
func rutinas(matriz[]int) {
	tam := len(matriz)/4
	go orden(matriz[:tam])
	go orden(matriz[tam:tam*2])
	go orden(matriz[tam*2:tam*3])
	go orden(matriz[tam*3:])
	orden(matriz)

}

func main() {
		ordenarMariz()
  	slice := matriz[:i]
  	rutinas(slice)
  	temp.Wait()

}

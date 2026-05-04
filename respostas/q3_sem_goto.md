## Python
j = -3
i = 0
while i < 3 and not (j > 0):         
    k = j + 2
    if k == 3 or k == 2:
        j -= 1
    elif k == 0:
        j += 2
    else:
        j = 0

    if not (j > 0):                    
        j = 3 - i
    i += 1

print(f"j = {j}, i = {i}")

# Java
public class Rewrite {
    public static void main(String[] args) {
        int j = -3;
        boolean continuar = true;

        for (int i = 0; i < 3 && continuar; i++) {
            int k = j + 2;
            if (k == 3 || k == 2) {
                j--;
            } else if (k == 0) {
                j += 2;
            } else {
                j = 0;
            }
            if (j > 0) {
                continuar = false;    // sinaliza parada sem usar break
            } else {
                j = 3 - i;
            }
        }
        System.out.println("j = " + j);
    }
}

## Go
package main

import "fmt"

func main() {
    j := -3

    for i := 0; i < 3 && j <= 0; i++ {   // condição de parada incorporada no for
        k := j + 2
        switch {
        case k == 3 || k == 2:
            j--
        case k == 0:
            j += 2
        default:
            j = 0
        }

        if j <= 0 {
            j = 3 - i
        }
    }
    fmt.Println("j =", j)
}
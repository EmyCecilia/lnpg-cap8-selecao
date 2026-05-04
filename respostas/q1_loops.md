
## Java
int j = 0;  
int k = (j+13)/27;
while (k <= 10 ){
   k= k + 1;
    i = 3 * k - 1; 
}
## Python
j = 0
k = (j+13) // 27 
    while k <=10 :
        k  = k + 1
        i = 3 * k - 1 
## Heskel
j = 0
k_inicial = (j + 13) `div` 27

loop k i =
    if k > 10
        then (k, i)
        else loop (k + 1) (3 * (k + 1) - 1)

resultado = loop k_inicial 0

## Swift
let j = 0
var i = 0
var k = (j+13)/27
while k <= 10 {
    k = k + 1 
    i = 3 * k -1
}
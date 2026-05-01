# Q4 - For em múltiplas linguagens
## Linguagem 1: [Python]
n = 100
sum = 0
j = 17

for i in range(0, 100):
    sum += i * j + 3
    j = j - 1

## Linguagem 2: [JavaScript]
let n = 100;
let sum = 0;
for (let i = 0, j = 17; i < n; i++, j--) {
   sum += i * j + 3
}
## Linguagem 3: [C++]
int i, j, n = 100;
int sum = 0;
for (i = 0, j = 17; i < n; i++, j--)
  sum += i * j + 3;

## Linguagem 4: [C#]
class Program {
  static void Main()
  {
    int i, j, n = 100;
    int sum = 0;
    for (i = 0, j = 17; i < n; i++, j--)
      sum += i * j + 3
  }
}

## Linguagem 5: [TypeScript]
let n: number = 100;
let sum: number = 0;
for (let i:number = 0, j:number = 17; i < n; i++, j--) {
   sum += i*j+ 3;
}
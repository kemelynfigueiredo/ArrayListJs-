# ArrayListJs-

Este documento explica de forma simples o funcionamento das funções map(), filter() e reduce(), que são usadas para manipulaçãode ArrayLists em JavaScript.

**map()**

  O map() cria um novo array transformando cada elemento do array original.

Como funciona:

  Ele percorre cada item do array e aplica uma função ao item, retornando um novo array com o resultado da função.

Exemplo de uso do map: 

  ```
  const numeros = [1, 2, 3, 4];

  const dobrados = numeros.map(num => num * 2);

 console.log(dobrados); // [2, 4, 6, 8]
 ```

**filter()**

O filter() cria um novo array contendo apenas os elementos que passam em uma condição.

Como funciona:

  Ele percorre todo Array e retorna uma nova lista com os elementos atendem a condição, como no exemplo abaixo.

Exemplo de uso do filter:

    const numeros = [1, 2, 3, 4, 5, 6];

    const pares = numeros.filter(num => num % 2 === 0);

**reduce()**

O reduce() reduz o array a um único valor.

Commo funciona: 

  Ele percorre todo o array, realiza uma operação, como a de soma, e retorna o resultado da operação.

  Exemplo de uso do redduce():

    const numeros = [1, 2, 3, 4];

    const soma = numeros.reduce((acumulador, valor) => acumulador + valor, 0);

    console.log(soma); // 10
    



console.log(pares); // [2, 4, 6]

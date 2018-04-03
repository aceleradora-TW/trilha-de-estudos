# Exercícios introdutórios de Javascript

## Bem-me-quer

Faça uma função chamada bemMeQuer que receba por argumento o número de pétalas da margarida e retorne 'Bem-me-quer' ou 'Mal-me-quer'. 

Exemplo:

``` javascript
bemMeQuer(4); // retorna 'Bem-me-quer'
```


## Maior texto

Faça uma função chamada maiorTexto que receba um array de strings e retorne o texto com maior número de caracteres.
Para testar:

```javascript

var batatasVariadas = ["Batata", "Batatão", "Batata-Gigante", "Batata Mega Hiper Blaster Chuck Norris"]

maiorTexto(batatasVariadas)
```

## Pirâmide Illuminatti

Escreva uma função gerarPiramide(niveis) que imprime com console.log uma pirâmide com uma quantidade de níveis informada por parâmetro, utilizando o caracter $. Ex:

``` javascript
gerarPiramide(5);
```


## Funções por parâmetro!?

Crie uma função chamada find que recebe um array e uma função por parâmetro. 

A função (passada por parâmetro) deverá informar um critério de busca de elementos dentro do array e a função find utilizará este critério para retornar todos elementos do array que encontram-se dentro dele.


## Mentor querido

Faça uma função chamada imprime que receba dois parâmetros: um array de strings e uma função.Dentro da função imprime chame a função do segundo parâmetro para cada elemento do array. Exemplo:

```javascript

imprime(
  // primeiro parâmetro: array
  
  [ 'Álvaro', 'Olimar', 'Matheus', 'Leco', 'Yasser'],
  
  // segundo parâmetro: função
  
  function(mentor) {
  
   console.log('Olá, querido mentor: ', mentor)
   
  });
```

Deve resultar em:

```
Olá, querido mentor: Álvaro

Olá, querido mentor: Olimar

Olá, querido mentor: Matheus

Olá, querido mentor: Leco

Olá, querido mentor: Yasser
```

Atenção! Faça um tratamento para evitar que a função imprime seja chamada com um segundo parâmetro que não seja uma função, por exemplo:

```
imprime(['alvaro', 'olimar', 'matheus', 'leco', 'yasser'], 3.14);
```

Deu ruim:

```
TypeError: number is not a function
```


## Soma diferentona

Escreva uma função somar que permite somar dois números através de duas chamadas diferentes (não necessariamente pra mesma função). 

Pirou? Exemplo:

```javascript
adicionar(3)(4); // 7

adicionar(5642)(8749); // 14391
```


## Fibona

Faça uma função fiboSum que calcule a soma da sequência de Fibonacci para n números informados. 

Exemplo de chamada:

``` javascript
fiboSum(7);

// 33 (soma dos 7 primeiros números da sequência: 1+1+2+3+5+8+13)
```

Dica: bom momento para aprender sobre algoritmos recursivos! ;D


## Quero café

Escreva uma função `queroCafe` que recebe dois parâmetros:

mascada: Valor numérico

precos: Lista de preços de café

A sua implementação deve retornar uma string com todos os preços que estão 
abaixo ou igual ao valor mascada ordenados de forma ascendente e separados por vírgula. 


Exemplo:

``` javascript
queroCafe(3.14, [5.16, 2.12, 1.15, 3.11, 17.5])

// '1.15,2.12,3.11'
```

## Diglett dig, trio trio trio

Escreva uma função `diglettDig()` que, utilizando console.log, imprime todos os números de 1 até 100, com duas exceções:

- Quando o número for divisível por 3, imprima 'Diglett dig' em vez do número

- Quando o número for divisível por 5 (e não por 3), imprima 'trio trio trio' em vez do número

Após ter essa lógica funcionando, altere a função para imprimir 'Diglett dig, trio trio trio' para números que são divisíveis 
tanto por 3 quanto por 5 (e que continue imprimindo 'Diglett dig' ou 'trio trio trio' para os números divisíveis apenas por 3 ou 5).

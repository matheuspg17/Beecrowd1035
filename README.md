# Resolução exercício Beecrowd1035

## Descrição do problema
Leia 4 valores inteiros A, B, C e D. A seguir, se B for maior do que C e se D for maior do que A, e a soma de C com D for maior que a soma de A e B e se C e D, ambos, forem positivos e se a variável A for par escrever a mensagem "Valores aceitos", senão escrever "Valores nao aceitos".

## Como Funciona
1. O programa lê uma linha de texto completa e a divide pelos espaços utilizando o método `.split(" ")`.
2. Os elementos obtidos são convertidos para inteiros através de `Integer.parseInt` e armazenados nas variáveis `A`, `B`, `C` e `D`.
3. Uma única estrutura condicional `if` valida todas as regras de negócio de forma combinada utilizando o operador lógico `&&` (E) e o operador de resto ` % 2 == 0` para verificar se `A` é par.
4. O programa imprime o veredito final no console de acordo com a validação.

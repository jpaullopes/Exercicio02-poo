# Exercício 02

## Questão 01
- **Tipagem Dinâmica**: O tipo da variável não precisa ser declarado quando ela será usada.
- **Tipagem Estática**: O tipo da variável precisa ser informado no momento em que ela é declarada, como `int`, `char`, `float`, etc.

## Questão 02
- Em linguagens de tipagem dinâmica, erros de tipo podem surgir durante a execução e não são detectados anteriormente, o que gera problemas difíceis de depurar.

## Questão 03
- **Exemplo de erro em Python**:
    ```python
    def somar(a, b):
        return a + b

    print(somar(5, 10))    # Funciona como esperado
    print(somar(5, "dez")) # Causa um erro em tempo de execução
    ```

## Questão 04
- Embora a linguagem C tenha tipagem estática, ela permite conversões de tipos. Por exemplo, ao trabalhar com um valor do tipo `char`, podemos somar um número inteiro com ele, pois C pode tratar o `char` como um valor `int`.

    ```c
    #include <stdio.h>

    int main() {
        char letra = 'A';     // 'A' tem o valor ASCII 65
        int offset = 5;

        // Soma o valor inteiro com o char, que será tratado como int
        char nova_letra = letra + offset; 

        printf("Letra original: %c\n", letra);           // Saída: A
        printf("Nova letra: %c\n", nova_letra);          // Saída: F
        printf("Valor ASCII da nova letra: %d\n", nova_letra); // Saída: 70

        return 0;
    }
    ```

## Questão 05
- Em TypeScript, o tipo `number` inclui valores `int` e `float` devido à especificação da linguagem JavaScript, que possui apenas um tipo numérico. TypeScript também define outros tipos de variáveis, como `boolean` e `string`, e não permite a conversão automática entre eles.

## Questão 06
- **Exemplo com `template strings` em TypeScript**:
    ```typescript
    const name: string = "Ely";
    const paymentTime: number = 120.56;
    const language: string = "TypeScript";

    console.log(`${name}
    My payment time is ${paymentTime}
    and
    my preferred language is ${language}`);
    ```

## Questão 07
*Feita*


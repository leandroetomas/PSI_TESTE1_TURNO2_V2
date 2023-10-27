# Teste de PSI 1 - Turno 2 - Versão 2

## Informação do aluno

    Nome: Leandro Sobral

Teste termina às 13:25.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    ulong uL = ulong.MaxValue;

    Console.WriteLine(uL + 1);

P1 - Resposta

    o código íra imprimir o valor 0 no console porque o máximo do tipo de dados ulong é em 1, ele volta ao valor mínimo que é 0.

### P2. Considera o seguinte código com um *bug*

    float f = double.MaxValue;

    Console.WriteLine(f);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    double f= double.maxvalue;
    console.writeline(f);            Este valor máximo do tipo de dados Double e ao atribuir o valor Double.maxvalue á variável f e em seguida imprimir o valor de F no console.


### P3. Escreve um programa que solicite ao utilizador dois números reais e apresente o resultado do segundo (base) elevado ao primeiro (expoente). Não podes usar um método da classe Math para obter o resultado

P3 - Resposta

    ```csharp
    using System;
    class Program
    {
    static void main ()
     {
     console.Writeline("digite o primeiro numero (expoente):");
     double expoente =
     convert.todouble(console.readline()); 
        console.writeline("digite o segundo numero (base):");
        double baseNumero =
        convert.todouble(console.readline());
        double resultado =
        console.writeline("o resultado é:" + resultado);
        
            }
        }

### P4. Estás na pasta raiz do teu repositório local, onde atualizaste um ficheiro de nome 'Perks.cs'. Queres enviar **apenas** esta atualização para o teu repositório remoto. Indica os comandos necessários. A mensagem de commit deve ser apropriada

P4 - Resposta


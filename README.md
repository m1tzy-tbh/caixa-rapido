Semana 17 (S17) - Funções e procedimentos – modularização I

## caixa-rapido

## Cenário prático: sistema de caixa rápido
    
Você foi contratado para iniciar o desenvolvimento do sistema de um "Caixa Rápido" de uma loja de eletrônicos. O sistema precisa         processar a venda de três produtos diferentes. Para cada produto, o operador de caixa informará o nome, o valor original e a             porcentagem de desconto a ser aplicada. O sistema deve calcular o valor final de cada item e, ao final, exibir um pequeno recibo.        Para evitar escrever a mesma fórmula matemática três vezes, você criará uma função reutilizável responsável apenas por calcular os       descontos.

## Questionário

## Aula 03

1.	Explique, com suas próprias palavras, qual foi a principal vantagem observada ao utilizar a função calcularValorFinal múltiplas vezes no algoritmo principal, em comparação com reescrever a fórmula de desconto para cada um dos três produtos.
R: Facilitou a visualização do código, deixando mais fácil de compreender o que está acontecendo.

2.	Imagine que a regra de negócio da loja mudou e agora todo desconto calculado deve incluir também uma taxa administrativa fixa de R$ 2,00. Como a estrutura modularizada, que você criou, facilita essa alteração no código?
R: facilita bastante, pq não tem q fazer uma alteração grandiosa, somente necessitando uma pequena adição no código.

3.	Qual a diferença prática de funcionamento percebida entre a função que realizou o cálculo do desconto (utilizando o comando Retorne) e o módulo exibirRecibo que formatou os dados na tela?
R: Uma calcula o desconto do produto e a outra exibe os preços dos itens após o desconto.


## Aula 04

## Checklist

[x] As variáveis globais foram declaradas corretamente, ou há variáveis "sobrando"?
[ ] A função de cálculo possui os parâmetros definidos corretamente na sua assinatura?
[ ] As operações matemáticas utilizam os parâmetros internos da função, e não as variáveis globais de fora?
[ ] O comando Retorne foi utilizado adequadamente?
[x] Os nomes das funções e das variáveis deixam claro qual é a responsabilidade delas?

## Feedback assertivo
1. utilizar listas para armazenar os produtos informados
2. criar um loop infinito para entrada de produtos

## caixa-rapido

## Cenário prático: sistema de caixa rápido
    
Você foi contratado para iniciar o desenvolvimento do sistema de um "Caixa Rápido" de uma loja de eletrônicos. O sistema precisa         processar a venda de três produtos diferentes. Para cada produto, o operador de caixa informará o nome, o valor original e a             porcentagem de desconto a ser aplicada. O sistema deve calcular o valor final de cada item e, ao final, exibir um pequeno recibo.        Para evitar escrever a mesma fórmula matemática três vezes, você criará uma função reutilizável responsável apenas por calcular os       descontos.

## Questionário

## Aula 3

1.	Explique, com suas próprias palavras, qual foi a principal vantagem observada ao utilizar a função calcularValorFinal múltiplas vezes no algoritmo principal, em comparação com reescrever a fórmula de desconto para cada um dos três produtos.
R: Facilitou a visualização do código, deixando mais fácil de compreender o que está acontecendo.

2.	Imagine que a regra de negócio da loja mudou e agora todo desconto calculado deve incluir também uma taxa administrativa fixa de R$ 2,00. Como a estrutura modularizada, que você criou, facilita essa alteração no código?
R: facilita bastante, pq não tem q fazer uma alteração grandiosa, somente necessitando uma pequena adição no código.

3.	Qual a diferença prática de funcionamento percebida entre a função que realizou o cálculo do desconto (utilizando o comando Retorne) e o módulo exibirRecibo que formatou os dados na tela?
R: Uma calcula o desconto do produto e a outra exibe os preços dos itens após o desconto.

# Tbl-sushi1
Questão 1. Desenvolvimento de um sistema de pedidos seguindo as etapas: definição, análise, projeto, implementação e testes. O sistema deve permitir informar o cliente, adicionar produtos, calcular o valor total e a forma de pagamento. Como cada etapa depende da anterior, uma mudança de requisito após a conclusão pode exigir alterações em várias fases do desenvolvimento.
Questão 1.1
Definição:
Criar um sistema para registrar pedidos, permitindo informar o cliente, adicionar produtos, calcular o valor total e escolher a forma de pagamento.
Questão 1.2
Análise:
O sistema deverá permitir cadastrar o cliente, adicionar produtos com preço e quantidade, calcular o total do pedido, informar a forma de pagamento e exibir o resumo do pedido. O cliente e os produtos são obrigatórios.
Questão 1.3
Projeto:
O sistema será desenvolvido em C# no modo Console. Ele receberá os dados do cliente e dos produtos, calculará o valor total e, no final, solicitará a forma de pagamento e exibirá as informações do pedido.
Questão 1.4
Para implementar a funcionalidade de desconto, primeiro deve-se definir a necessidade de adicionar essa nova função ao sistema. Em seguida, é necessário analisar as regras para determinar quando e como o desconto será aplicado. No projeto, deve-se definir que o desconto será calculado após o valor total do pedido e antes da apresentação do valor final. Por fim, na implementação, o código deverá receber essa nova lógica, calcular o desconto e atualizar o valor final do pedido, mantendo as demais funcionalidades do sistema.
========================================================================================================================================================================================================

Questão 2
No primeiro incremento Já existiam definição dos produtos, a possibilidade de adiciona-los ao carrinho e a visualização do carrinho. No segundo incremento foram acrescentados o calculo do total, a remoção de produtos e a escolha da forma de pagamento. A primeira versão precisou ser ampliada para armazenar tambem os preços as novas operações.
Alteração feita
A nova regra determina que os produtos acima de 500 reais recebem 10% de desconto. O sistema verificaria o preço de cada produto e caso fosse superior a 500 reais e aplicaria o desconto de acordo.

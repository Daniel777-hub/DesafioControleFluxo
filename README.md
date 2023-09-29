# DesafioControleFluxo

Este é o repositório para o DesafioControleFluxo, um desafio concluído com sucesso na plataforma Dio (Digital Innovation One).

## Descrição do Desafio

O DesafioControleFluxo é um exercício que envolve o uso de controle de fluxo em Java. O sistema deve receber dois parâmetros via terminal, que representam dois números inteiros. Com esses dois números, o programa deve realizar a seguinte tarefa:

- Calcular a diferença entre os dois números e determinar a quantidade de iterações (usando um loop for) necessárias para imprimir os números incrementados. Por exemplo, se os números fornecidos forem 12 e 30, o programa deve imprimir os números de 12 a 30, ou seja, "Imprimindo o número 12", "Imprimindo o número 13", e assim por diante, até "Imprimindo o número 30".

Além disso, o programa deve tratar a seguinte exceção:

- Se o primeiro parâmetro for MAIOR que o segundo parâmetro, o programa deve lançar uma exceção customizada chamada `ParametrosInvalidosException` com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

## Resolução

Neste repositório, você encontrará a implementação em Java que resolve o DesafioControleFluxo. O código está organizado da seguinte forma:

- A classe `Contador.java` contém a implementação principal do programa, incluindo a lógica para calcular a diferença entre os parâmetros e imprimir os números incrementados.

- A classe `ParametrosInvalidosException` representa a exceção customizada que é lançada quando os parâmetros são inválidos.

## Como Executar

Para executar este projeto localmente, siga estas etapas:

1. Clone este repositório em sua máquina local.
2. Compile o código Java usando seu IDE favorito ou o comando `javac Contador.java` no terminal.
3. Execute o programa com os dois parâmetros fornecidos via terminal, por exemplo: `java Contador 12 30`.

## Contribuições

Contribuições são bem-vindas! Se você quiser contribuir para melhorar este projeto, siga estas etapas:

1. Fork este repositório.
2. Crie uma nova branch com sua alteração: `git checkout -b minha-contribuicao`.
3. Faça as alterações desejadas e commit: `git commit -m 'Minha contribuição'`.
4. Envie suas alterações: `git push origin minha-contribuicao`.
5. Abra uma solicitação de pull neste repositório.

## Créditos

Este desafio foi concluído como parte de um projeto na plataforma [Dio (Digital Innovation One)](https://digitalinnovation.one/). Todos os direitos e créditos relacionados ao desafio pertencem à Dio.

## Licença

Este desafio é licenciado sob a [Dio (Digital Innovation One)](https://digitalinnovation.one/) © 2023 

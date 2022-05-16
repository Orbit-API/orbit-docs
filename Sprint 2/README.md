# Sprint 2 - Descrição da entrega

A segunda sprint contemplará os seguintes incrementos previamente propostos:

1º - Paginação da aplicação de cadastro: 
- Vai otimizar o desempenho da aplicação;


2º - Integração com o Grafana:
- Com isso o usuário poderá monitorar a saúde da aplicação em tempo real

3º - Adição de novas métricas:
- Uso de memória HEAP e NO-HEAP
- Uso de memória RAM no geral
- Tempo de resposta por timpo de requisição (GET e POST)
- Quantidade de requisições por segundo

4º - Correação entre as métricas:
- Analisamos várias métricas ao mesmo tempo

5º - Armazenamento dos dados no banco de dados:
- Já estamos armazenando os dados coletados no MongoDB


## Acesso aos incrementos contemplados na sprint 2:

1º - A versão mais atual do app (aplicação frontend) pode ser encontrada [clicando aqui.](https://github.com/Orbit-API/orbit-web)

2º - O nosso webservice é acesso [clicando aqui.](https://github.com/Orbit-API/orbit-webservice)

## Estrutura e Fluxo
O diagrama a seguir mostra como está funcionando a aplicação nesta Sprint 2, incluindo a organização das máquinas virtuais e o fluxo dos dados.
![draft-orbit-structure](https://user-images.githubusercontent.com/56441318/168480728-c159fdfd-d398-4e37-b236-97e93dce8496.png)


## Projeto em funcionamento

![Gif-Orbit](https://user-images.githubusercontent.com/56441318/168501973-8e5a1e5b-d5fb-4379-8076-0b2b47a94f75.gif)

A animação acima demonstra a aplicação em funcionamento, com os gráficos de monitoramento em tempo real exibindo todas as informações importantes sobre a saúde do sistema. Além disso, ele demonstra o envio do alerta via Slack caso detecte um risco de falha da aplicação.

Detalhe ao final da demonstração, quando a memória Heap tem um grande salto e logo em seguida é enviado uma mensagem de alerta no slack.

# Documentação Orbit

![background-orbit-com-slogan](https://user-images.githubusercontent.com/56441318/171164559-775dfbf2-5a23-4b91-b0fb-6318a50cebac.png)

O Orbit foi desenvolvido visando monitorar um sistema e caso haja a possibilidade de que este sistema corre risco de falhar, ele avisa ao operador para que tome uma atitude com antecedência, garantindo que a aplicação permaneça no ar sem que o usuário perceba qualquer falha. O projeto está sendo desenvolvido a partir de uma parceria com a Fatec São José dos Campos - Prof. Jessen Vidal.

## Disciplinas Integradas

- Gestão de Equipes
  - Prof. Eduardo Sakaue

- Inteligência Artificial
  - Prof. Walmir Duque

- Tópicos Especiais em Informática
  - Prof. Emanuel Mineda

- Gestão e Governança da Informação
  - Prof. Claudio Etelvino
  
- Gestão e Governança da Informação
  - Prof. Claudio Etelvino

## Time

- Luis Guilherme - PO - [LinkedIn](https://www.linkedin.com/in/luis-guibelem/)
- Jodan Galas - Scrum Master - [LinkedIn](https://www.linkedin.com/in/jodangalas/)
- Raquel Ribeiro - DEV Team - [LinkedIn](https://www.linkedin.com/in/raquel-rodrigues-ribeiro-a9537818b)
- Cristiane Rodrigues - DEV Team - [LinkedIn](https://www.linkedin.com/in/cristiane-rodrigues-20b3b61b2)
- Fabrício Cursino - DEV Team - [LinkedIn](https://www.linkedin.com/in/fcursino)
- José Danrley - DEV Team - [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-danrley-069827191)
- Washington Hentique - DEV Team - [LinkedIn](https://www.linkedin.com/in/justhenrique/)


## Objetivo

Desenvolver uma ferramenta que alerta com antecedência o risco de uma falha


## O Projeto

O projeto consiste em uma solução que tem a capacidade de monitorar uma aplicação e alerta com antecedência o operador caso haja risco de falha. Além disso ela será capaz de monitorar e exibir as informações da aplicação em tempo real.


## Projeto em funcionamento

![Gif-Orbit](https://user-images.githubusercontent.com/56441318/168501973-8e5a1e5b-d5fb-4379-8076-0b2b47a94f75.gif)

O vídeo acima demonstra a aplicação em funcionamento, com os gráficos de monitoramento em tempo real exibindo todas as informações importantes sobre a saúde do sistema. Além disso ele demonstra o envio do alerta via Slack caso detecte um risco de falha da aplicação.

Detalhe no final do vídeo onde a memória Heap tem um grande salto e logo em seguida é enviado uma mensagem de alerta no slack.


### Requisitos Funcionais

- Desenvolver um formulário de cadastro, com os campos: Nome, E-mail, Senha e Celular

- Desenvolver um formulário de consulta dos cadastros realizados

- Prever quando ocorrerá uma falha de software que causará a indisponibilidade da
aplicação


### Requisitos Não Funcionais

- O tempo de resposta do backend de cadastros deve ser abaixo de 300ms
- O tempo de resposta do backend de consulta de cadastros deve ser abaixo de 100ms

## Estrutura e Fluxo
O diagrama a seguir mostra como está funcionando a aplicação, incluindo a organização das máquinas virtuais e o fluxo dos dados.
![draft-orbit-structure@1 25x](https://user-images.githubusercontent.com/56441318/172076820-fe15b6bf-97b4-42e5-b82d-b50857cac375.png)


### Backlog do produto resumido:
![backlog_orbit_v3_Prancheta 1](https://user-images.githubusercontent.com/56441318/172073923-0d32e9fc-f5e2-450d-b960-322dbdfe48a6.png)


### Acessando as entregas

- [Sprint 1](https://github.com/Orbit-API/orbit-docs/tree/main/Sprint%201)
- [Sprint 2](https://github.com/Orbit-API/orbit-docs/tree/main/Sprint%202)
- [Sprint 3](https://github.com/Orbit-API/orbit-docs/tree/main/Sprint%203)


### Tecnologias utilizadas
- Java Spring Boot
- Vue JS
- Locust
- Prometheus
- Grafana
- SKLearn
- MongoDB

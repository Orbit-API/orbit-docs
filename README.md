# Documentação Orbit

![background-orbit_Prancheta 1](https://user-images.githubusercontent.com/56441318/160112708-193a18fe-2241-427c-8fe0-2dc23324b48a.png)
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
- 
- O tempo de resposta do backend de consulta de cadastros deve ser abaixo de 100ms


### Backlog do produto resumido:
![backlog_orbit_Prancheta 1](https://user-images.githubusercontent.com/56441318/168578693-c562f27e-9aba-4d88-84d3-2bb06b8f4888.png)


### Acessando as entregas

- [Sprint 1](https://github.com/Orbit-API/orbit-docs/tree/main/Sprint%201)
- [Sprint 2](https://github.com/Orbit-API/orbit-docs/tree/main/Sprint%202)



### Tecnologias utilizadas
- Java Spring Boot
- Vue JS
- Locust
- Prometheus
- Grafana
- SKLearn

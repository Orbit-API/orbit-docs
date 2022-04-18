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


![alert](https://user-images.githubusercontent.com/56441318/163734168-803857bf-4493-4e8d-abe8-92a007f580fa.gif)

Neste teste foram cadastrados 500 usuários em uma taxa de 900 usuários por segundo, de modo a forçar uma falha da aplicação de cadastro. Logo em seguida, é enviado uma mensagem automaticamente pelo Slack alertando o usuário sobre a falha.


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
![backlog_orbit_v2_Prancheta 1](https://user-images.githubusercontent.com/56441318/163737121-40d5586f-2130-4033-a26c-87eb2cf86f8d.png)


### Acessando as entregas

- [Sprint 1](https://github.com/Orbit-API/orbit-docs/tree/main/Sprint%201)



### Tecnologias utilizadas
- Java Spring Boot
- Vue JS
- Locust
- Prometheus


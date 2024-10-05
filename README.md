# 📨 AWS SQS: Publicando e Consumindo Mensagens com Spring Cloud AWS

Neste projeto, vamos explorar como **publicar** e **consumir** mensagens com o **AWS SQS** usando **Java** e **Spring Cloud AWS**. Vamos utilizar o **LocalStack** para simular os serviços da AWS localmente, o que facilita o desenvolvimento e os testes. 

O **SQS (Simple Queue Service)** é amplamente utilizado em arquiteturas de microserviços para promover o **desacoplamento** entre aplicações, permitindo a comunicação assíncrona entre elas por meio de um serviço de filas. 

Se você está interessado em aprender mais sobre a **nuvem AWS** e como o **ecossistema de microserviços em Java** pode ser integrado com serviços como o SQS, esse projeto é para você!

## 🚀 Tecnologias Utilizadas

- **Java** 17+
- **Spring Boot** 3.x
- **Spring Cloud AWS**
- **AWS SQS**
- **LocalStack** (para simulação local da AWS)
- **Maven** (para gerenciamento de dependências)

## 📦 Funcionalidades

- **Producer (Produtor de Mensagens)**: Publica mensagens em uma fila SQS.
- **Consumer (Consumidor de Mensagens)**: Consome mensagens de uma fila SQS e processa.
- **Simulação Local**: Usamos o **LocalStack** para rodar uma instância do SQS localmente.

## 🧩 Estrutura do Projeto


- **Consumer**: Classe que escuta mensagens da fila e as processa.
- **Producer**: Classe responsável por enviar mensagens à fila.

## 🛠️ Como Rodar o Projeto Localmente

### Pré-requisitos

- **Docker** (para rodar o LocalStack)
- **Java 17+**
- **Maven**
- **AWS CLI** (opcional, mas recomendado)

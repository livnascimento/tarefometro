# Tarefômetro

## **Descrição do Projeto**
O **Tarefômetro** é um aplicativo mobile de lista de tarefas projetado com a finalidade de aprendizagem de Spring Boot e revisão dos conceitos básicos de Java.

## **Funcionalidades Principais**
- **Adicionar Tarefas**: Permite criar novas tarefas com poucos cliques.
- **Listar Tarefas**: Exibe todas as tarefas criadas, com opção de filtrar tarefas concluídas.
- **Excluir Tarefas**: Remove tarefas não mais necessárias.
- **Gerenciamento de Usuários**: Controle básico para criar e listar usuários associados às tarefas.

---

## **Arquitetura do Projeto**
O **Tarefômetro** é baseado em uma arquitetura de microserviços composta por:

1. **Task Service**:
    - Gerencia tarefas (CRUD).
    - Utiliza um banco de dados H2 (em memória) para armazenamento.

2. **User Service**:
    - Gerencia usuários (CRUD).

3. **API Gateway**:
    - Implementado com Spring Cloud Gateway.
    - Centraliza o acesso aos microserviços, facilitando o roteamento e a comunicação entre eles.

---

## **Tecnologias Utilizadas**
- **Frontend Mobile**: Desenvolvido em Java 17.
- **Backend**:
    - **Framework**: Spring Boot.
    - **Gerenciamento de Microserviços**: Spring Cloud Gateway.
    - **Banco de Dados**: H2 Database (em memória).
- **Containerização**:
    - Docker e Docker Compose para orquestração de containers.

---

Obrigada por visitar meu repositório. 😊
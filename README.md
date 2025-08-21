# FC2 Arquitetura Hexagonal

Este projeto foi desenvolvido com o objetivo de **praticar os conceitos de Arquitetura Hexagonal (Ports and Adapters)** utilizando **Golang** e algumas bibliotecas complementares.

## 🚀 Objetivo

O foco principal deste projeto foi aprender, na prática, como aplicar os princípios da Arquitetura Hexagonal para estruturar aplicações de forma desacoplada, permitindo maior flexibilidade e testabilidade.

## 🛠️ Tecnologias Utilizadas

- **Golang** (linguagem principal)  
- **Cobra CLI** (para comandos de linha de comando)  
- **SQLite** (banco de dados local)  
- **HTTP Server com net/http** (para expor endpoints)  
- **Docker** e **Docker Compose** (para containerização)  
- **Testes unitários com Go testing**  
- **Mockgen** (para geração de mocks e testes)  

## 📂 Estrutura do Projeto

- `application/` → camada de casos de uso (regras de negócio)  
- `adapters/` → adaptadores para banco de dados, CLI e HTTP  
- `cmd/` → comandos para rodar a aplicação via CLI ou HTTP  
- `main.go` → ponto de entrada do projeto  

## ▶️ Como rodar o projeto

### Usando Docker

```bash
docker compose up -d
```

### Localmente

```bash
go run main.go
```

## 📚 Aprendizados

- Separação clara entre domínio e infraestrutura
- Criação de ports (interfaces) e adapters para integração
- Prática com testes unitários e mocks
- Uso de CLI e API HTTP como diferentes formas de entrada na aplicação

## Créditos

Este projeto foi originalmente forkado de [fc2-arquitetura-hexagonal](codeedu/fc2-arquitetura-hexagonal).  
O objetivo foi utilizá-lo como base para estudos e práticas sobre **Arquitetura Hexagonal em Golang**.

# API Inteligente: Reconhecimento de Fala com Spring Boot

## 📌 Sobre o Projeto
Este projeto demonstra a construção de uma API robusta utilizando o ecossistema **Spring**, focada no processamento de linguagem natural através de áudio. O objetivo é receber arquivos ou fluxos de voz e convertê-los em dados estruturados (texto), permitindo a automação de processos baseados em comandos de voz.

## 🛠️ Tecnologias Utilizadas
* **Java 21+**
* **Spring Boot 3.x:** Framework principal para a construção da API.
* **Spring Web:** Para a criação dos endpoints RESTful.
* **Integração com IA:** (Ex: Azure Speech Service, Google Cloud Speech-to-Text ou bibliotecas locais).
* **Maven:** Gerenciamento de dependências.

## 🚀 Funcionalidades e Arquitetura
1. **Endpoint de Áudio:** Recebimento de arquivos de áudio via requisições POST.
2. **Processamento de Fala:** Integração com serviços de IA para conversão Speech-to-Text.
3. **Dados Processáveis:** Retorno do texto extraído para integração com outros sistemas ou bancos de dados.
4. **Tratamento de Exceções:** Implementação de Global Exception Handling para garantir a resiliência da API.

## ⚙️ Como Executar
1. Clone o repositório.
2. Configure as credenciais do serviço de Speech-to-Text escolhido no `application.properties`.
3. Execute o projeto usando o Maven: `./mvnw spring-boot:run`
4. Teste o endpoint de reconhecimento enviando um arquivo de áudio.

## 💡 Diferencial Técnico
A implementação utiliza conceitos modernos de **Dependency Injection** e **Inversion of Control (IoC)** nativos do Spring, facilitando a troca do provedor de reconhecimento de fala sem afetar a lógica de negócio principal.

---
## 👩‍💻 Autora
Feito com 💛 por Bruna Guimarães

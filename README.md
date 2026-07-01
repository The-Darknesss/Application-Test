# Application Test

Este é o repositório do **projeto1**, uma aplicação desenvolvida com **Java** e **Spring Boot**.

## 🚀 Tecnologias Utilizadas

- **[Java 11](https://www.oracle.com/java/)**: Linguagem de programação principal.
- **[Spring Boot](https://spring.io/projects/spring-boot)** (v2.7.18): Framework para a construção da aplicação.
- **[Maven](https://maven.apache.org/)**: Gerenciamento de dependências e automação de builds.
- **[Lombok](https://projectlombok.org/)**: Biblioteca para reduzir a verbosidade do código Java.
- **Spring Web**: Dependência para criação de aplicações web e RESTful.

## 📋 Pré-requisitos

Antes de iniciar, você precisará ter instalado em sua máquina:
- [Java Development Kit (JDK) 11](https://adoptium.net/)
- [Apache Maven](https://maven.apache.org/) (opcional, o projeto possui o Maven Wrapper `mvnw`)

## 🛠️ Configuração e Instalação

1. **Clone o repositório e acesse a pasta do projeto:**
   ```bash
   git clone <url-do-repositorio>
   cd Application-Test/AplicationTest-main/projeto1
   ```

2. **Instale as dependências e compile o projeto:**
   Utilizando o Maven Wrapper incluído no projeto:
   ```bash
   ./mvnw clean install
   ```
   No Windows:
   ```cmd
   mvnw.cmd clean install
   ```

## ▶️ Executando a Aplicação

Para iniciar o servidor localmente:

```bash
./mvnw spring-boot:run
```
No Windows:
```cmd
mvnw.cmd spring-boot:run
```

O servidor será iniciado, por padrão, na porta `8080`.

## 📄 Estrutura Principal

- `/src/main/java` - Código-fonte principal da aplicação (Controladores, Modelos, Repositórios, etc).
- `/src/main/resources` - Arquivos de configuração (ex: `application.properties`).
- `/src/test` - Diretório reservado para testes automatizados.
- `pom.xml` - Arquivo de configuração de dependências do Maven.

## 📄 Licença

Este projeto está sob a licença ISC.

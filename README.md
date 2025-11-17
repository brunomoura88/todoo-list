# Todoo-List

Repositório simples de exemplo (Java Spring Boot) para um TODO list.

Este projeto contém a aplicação Spring Boot, configuração do Maven, e um Dockerfile para empacotar a aplicação.

## Conteúdo

- `todolist/` - código fonte do aplicativo (Java)
- `Dockerfile` - imagem Docker para rodar a aplicação

## Requisitos

- Java 11 ou superior
- Maven (o projeto inclui wrappers `mvnw` / `mvnw.cmd`)
- Docker (opcional, para rodar via container)

## Como rodar (Windows PowerShell)

1. Abrir PowerShell na pasta do projeto:

```powershell
cd C:\Users\anabr\Downloads\todolist
```

2. Executar com o wrapper do Maven:

```powershell
.\mvnw.cmd spring-boot:run
```

3. A aplicação rodará por padrão em `http://localhost:8080`.

## Testes

Executar testes com:

```powershell
.\mvnw.cmd test
```

## Docker

Construir a imagem Docker:

```powershell
docker build -t todoo-list .
```

Rodar o container:

```powershell
docker run -p 8080:8080 todoo-list
```

## Contribuição

1. Faça um fork do repositório
2. Crie uma branch com uma descrição curta da mudança
3. Abra um Pull Request

## Remoto

Este repositório foi empurrado para: https://github.com/brunomoura88/todoo-list.git

## Licença

Adicione aqui a licença desejada (ex.: MIT) ou remova essa seção.

---

Arquivo gerado automaticamente pelo assistente para documentar o projeto.

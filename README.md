# Projetando Arquiteturas Em Três Camadas

## 📝️ Escopo do Projeto

<p align="justify"> 
O projeto demonstra da aplicabilidade dos princípios do SOLID por meio de exemplos que ilustram tanto a violação quanto a solução de cada um deles: SRP (Princípio da Responsabilidade Única), OCP (Princípio do Aberto-Fechado), LSP (Princípio da Substituição de Liskov), ISP (Princípio da Segregação de Interfaces) e DIP (Princípio da Inversão de Dependências).
</p>

## 🛠️ Construído com

* [Visual Studio 2022](https://learn.microsoft.com/pt-br/visualstudio/windows/?view=vs-2022) - Ferramenta de desenvolvimento, que permite realizar todo o ciclo de desenvolvimento em um só lugar.
  
## 📚 Principais Bibliotecas, Frameworks e Comandos do NuGet Utilizados

* [net7.0](https://learn.microsoft.com/pt-br/dotnet/core/compatibility/7.0) - Versão da plataforma de desenvolvimento .NET, que é de código aberto e multiplataforma, desenvolvida pela Microsoft.

```
dotnet add package Microsoft.NET.Sdk.Web --version 7.0.0
```

* [automapper](https://automapper.org/) - Biblioteca de mapeamento de objetos facilita a conversão de dados entre objetos de tipos diferentes, evitando código repetitivo.

```
dotnet add package AutoMapper --version 12.0.1
```

* [Swashbuckle.AspNetCore](https://learn.microsoft.com/pt-br/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-8.0&tabs=visual-studio) - Biblioteca facilitar a criação de uma interface visual para testar, explorar e documentar as APIs, sem a necessidade de escrever manualmente a documentação.

```
dotnet add package Swashbuckle.AspNetCore --version 6.5.0
```

* [FluentValidation](https://docs.fluentvalidation.net/en/latest/) - Biblioteca de validação de dados para aplicações .NET que permite validar objetos.

```
dotnet add package FluentValidation --version 11.7.1
```

* [Microsoft.EntityFrameworkCore](https://learn.microsoft.com/pt-br/ef/core/get-started/overview/install) - 
ORM que permite a interação entre aplicativos .NET e bancos de dados relacionais de maneira eficiente e prática.

```
dotnet add package Microsoft.EntityFrameworkCore --version 7.0.11
```

## 🚧 Descrição da Estrutura do Projeto

A estrutura do projeto segundo a imagem abaixo é composta da seguinte forma:

![EstruturaDoProjeto](screenshots/estrutura.PNG)


## ⚠️ Atenção

Destinado exclusivamente para fins de estudo.

---
⌨️ por [Byron Doria](https://gist.github.com/lohhans) 😊

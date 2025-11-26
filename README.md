# PessoaCad – Base para Sistema de Gerenciamento de Gastos Pessoais

![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-v8.0-blue) 
![C#](https://img.shields.io/badge/C%23-Language-brightgreen) 
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-v8.0-blue) 
![Blazor](https://img.shields.io/badge/Blazor-Framework-purple) 
![Visual Studio 2022](https://img.shields.io/badge/Visual%20Studio-2022-purple) 
![License](https://img.shields.io/badge/License-MIT-blue) 

## Tecnologias Utilizadas - 
![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-v8.0-blue) - 
![C#](https://img.shields.io/badge/C%23-Programação-brightgreen) - 
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-v8.0-blue) - 
![Blazor](https://img.shields.io/badge/Blazor-Framework-purple) - 
![Newtonsoft.Json](https://img.shields.io/badge/Newtonsoft.Json-13.0.1-orange)


📌 Sobre o Projeto

Este repositório contém o projeto PessoaCad, desenvolvido pelo professor e utilizado como base obrigatória para a construção do nosso sistema final: um Gerenciador de Gastos Pessoais.
A estrutura, arquivos e funcionamento original do PessoaCad devem ser mantidos conforme orientação, servindo como modelo de CRUD (Create, Read, Update, Delete) para o desenvolvimento dos novos módulos relacionados ao controle de despesas.

Portanto:

✔ Nada será removido
✔ Apenas novos módulos, pastas e funcionalidades serão adicionados
✔ O padrão arquitetural e a estrutura fornecida serão reutilizados e expandidos

📘 Descrição do Projeto Original (PessoaCad)

O PessoaCad é uma solução completa para gerenciar o cadastro de pessoas, composta por:
Uma aplicação multi-plataforma em .NET MAUI
Uma API em ASP.NET Core
Uma interface web utilizando Blazor
Arquitetura MVVM e MVC, garantindo modularidade, organização e fácil manutenção
Esta estrutura serve como exemplo para o nosso projeto final.


🛠️ Tecnologias Utilizadas

````markdown
```plaintext
📂 Estrutura Atual do Projeto
PessoaCad/
├── apppessoa/
│   ├── Models/
│   │   ├── Endereco.cs
│   │   ├── Pessoa.cs
│   │   ├── Telefone.cs
│   ├── ViewModels/
│   ├── Views/
│   │   ├── MainPage.xaml
│   │   └── DetalhesPage.xaml
│   ├── Resources/
│   │   ├── Fonts/
│   │   └── Images/
│   ├── App.xaml
│   └── MainPage.xaml.cs
├── apipessoa/
│   ├── Controllers/
│   │   ├── PessoaController.cs
│   ├── Models/
│   │   ├── Pessoa.cs
│   │   ├── Endereco.cs
│   │   └── Telefone.cs
│   ├── Program.cs
│   ├── Startup.cs
│   └── appsettings.json
├── webpessoa/
│   ├── Controllers/
│   │   ├── HomeController.cs
│   │   └── PessoaController.cs
│   ├── Models/
│   │   ├── Endereco.cs
│   │   ├── ErrorViewModel.cs
│   │   ├── Pessoa.cs
│   │   ├── Telefone.cs
│   │   └── TelefoneTipo.cs
│   ├── Program.cs
│   ├── Properties/
│   │   └── launchSettings.json
│   ├── Services/
│   │   └── apiPessoaService.cs
│   ├── Views/
│   │   ├── Home/
│   │   │   ├── Index.cshtml
│   │   │   └── Privacy.cshtml
│   │   ├── Pessoa/
│   │   │   ├── Create.cshtml
│   │   │   ├── Delete.cshtml
│   │   │   ├── Details.cshtml
│   │   │   ├── Edit.cshtml
│   │   │   └── Index.cshtml
│   │   ├── Shared/
│   │   │   ├── Error.cshtml
│   │   │   ├── _Layout.cshtml
│   │   │   ├── _Layout.cshtml.css
│   │   │   └── _ValidationScriptsPartial.cshtml
│   │   ├── _ViewImports.cshtml
│   │   └── _ViewStart.cshtml
│   ├── appsettings.Development.json
│   ├── appsettings.json
│   ├── wwwroot/
│   │   ├── css/
│   │   │   └── site.css
│   │   ├── favicon.ico
│   │   ├── js/
│   │   │   └── site.js
│   │   └── lib/
│   │       ├── bootstrap/
│   │       │   ├── LICENSE
│   │       │   └── dist/
│   │       │       ├── css/
│   │       │       │   ├── bootstrap.min.css
│   │       │       │   └── bootstrap.min.css.map
│   │       │       └── js/
│   │       │           ├── bootstrap.bundle.min.js
│   │       │           └── bootstrap.bundle.min.js.map
│   │       ├── jquery/
│   │       │   ├── LICENSE.txt
│   │       │   └── dist/
│   │       │       ├── jquery.min.js
│   │       │       └── jquery.min.map
│   │       ├── jquery-validation/
│   │       │   ├── LICENSE.md
│   │       │   └── dist/
│   │       │       ├── jquery.validate.min.js
│   │       │       └── additional-methods.min.js
│   │       └── jquery-validation-unobtrusive/
│   │           ├── LICENSE.txt
│   │           └── dist/
│   │               ├── jquery.validate.unobtrusive.min.js
│   │               └── jquery.validate.unobtrusive.js
├── PessoaCad.sln
└── README.md
``` 
🧩 Expansões para o Sistema de Gerenciamento de Gastos Pessoais
O projeto será ampliado com novas funcionalidades, como:
Cadastro de gastos e categorias
Controle de entradas e saídas
Relatórios simples
Integração com a API já fornecida
Telas novas no app MAUI e na interface web
Esses módulos serão adicionados sem modificar ou remover o que já existe, apenas estendendo a arquitetura padrão.


🔧 Funcionamento dos Componentes Originais
App Móvel (apppessoa)
Models: Estruturas de dados
ViewModels: Regras de negócio e comunicação com a interface
Views: Telas do app
Resources: Imagens, fontes e outros assets
API REST (apipessoa)
Controllers responsáveis pelas rotas
Program.cs / Startup.cs configurando serviços e middlewares
Models estruturando os dados da API
Interface Web (webpessoa)
Páginas e views para exibir e editar informações
Uso de Blazor + ASP.NET Core MVC
Arquivos estáticos em wwwroot


▶️ Como Executar no Visual Studio 2022
1. Pré-requisitos

Visual Studio 2022 com workloads:
.NET MAUI
ASP.NET e Desenvolvimento Web
Desenvolvimento Blazor

2. Clonar o Projeto
git clone https://github.com/seuusuario/SeuRepositorio.git
cd SeuRepositorio

3. Abrir no Visual Studio
Abra o arquivo PessoaCad.sln.

4. Executar
Execute o apppessoa em um emulador ou dispositivo
Execute a API (apipessoa)
Execute o webpessoa no navegador

Feito como parte do projeto acadêmico, utilizando a base fornecida pelo professor Rodney Victor.

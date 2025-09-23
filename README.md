# 📌 NossoEvento

**NossoEvento** é um projeto de curso destinado ao aprendizado.  
O objetivo é criar um **gerenciador de eventos**, englobando todas as etapas de desenvolvimento: **backend** e **frontend**.

---

## 🚀 Tecnologias Utilizadas

- **Backend:** .NET 5.0 (WebAPI)
- **Frontend:** Angular 12.x.x
- **Runtime:** Node.js v14.20.1
- **Banco de Dados:** SQLite (com migrations via Entity Framework)

---

## ⚙️ Instalações Necessárias

### 🔹 Dependências principais

```bash
# .NET
Instalar versão 5.0.416

# Angular CLI (12.x.x)
npm install -g @angular/cli@12

# Node.js
Versão compatível: 14.20.1 (via NVM recomendado)

# Entity Framework Core CLI
dotnet tool install --global dotnet-ef --version 5.0.2

# FontAwesome
npm install --save @fortawesome/fontawesome-free


```

### 📦 Packages (via NuGet)

- Microsoft.EntityFrameworkCore --version 5.0.2
- Microsoft.EntityFrameworkCore.Design --version 5.0.2
- Microsoft.EntityFrameworkCore.Sqlite --version 5.0.2
- Microsoft.EntityFrameworkCore.Tools --version 5.0.2

#### ou, adicione as packages via CLI .NET

```bash
dotnet add package Microsoft.EntityFrameworkCore --version 5.0.2
dotnet add package Microsoft.EntityFrameworkCore.Design --version 5.0.2
dotnet add package Microsoft.EntityFrameworkCore.Sqlite --version 5.0.2
dotnet add package Microsoft.EntityFrameworkCore.Tools --version 5.0.2
```

# NossoEventoApp - ANGULAR

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.18.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

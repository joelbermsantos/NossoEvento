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

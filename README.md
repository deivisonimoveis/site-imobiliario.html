<!DOCTYPE html>[Devison-Lemos-Im-veis-main.zip](https://github.com/user-attachments/files/22259779/Devison-Lemos-Im-veis-main.zip)

<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deivison Lemos Imóveis</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Deivison Lemos Imóveis</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Início</a></li>
          <li class="nav-item"><a class="nav-link" href="#imoveis">Imóveis</a></li>
          <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Banner -->
  <section class="bg-dark text-light text-center p-5">
    <h1 class="display-5">Seu próximo imóvel começa aqui</h1>
    <p class="lead">Guarapuava · Praia · Litoral</p>
    <a href="#imoveis" class="btn btn-warning btn-lg mt-3">Ver Imóveis</a>
  </section>

  <!-- Imóveis -->
  <section id="imoveis" class="container my-5">
    <h2 class="text-center mb-4">Imóveis Disponíveis</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card shadow">
          <img src="img/casa1.jpg" class="card-img-top" alt="Casa no Centro">
          <div class="card-body">
            <h5 class="card-title">Casa no Centro</h5>
            <p class="card-text">Ampla, 3 quartos, garagem para 2 carros. Localização privilegiada.</p>
            <a href="https://wa.me/5542988368121" class="btn btn-outline-success w-100">Chamar no WhatsApp</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow">
          <img src="img/casa2.jpg" class="card-img-top" alt="Casa na Praia">
          <div class="card-body">
            <h5 class="card-title">Casa na Praia</h5>
            <p class="card-text">Vista para o mar, ideal para férias ou investimento.</p>
            <a href="https://wa.me/5542988368121" class="btn btn-outline-success w-100">Chamar no WhatsApp</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <footer id="contato" class="bg-dark text-light text-center p-4">
    <p class="mb-1">© 2025 Deivison Lemos Imóveis · CRECI-PR 51055</p>
    <a href="mailto:deivisonlemosimoveis@gmail.com" class="text-warning">deivisonlemosimoveis@gmail.com</a>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
# Welcome to your OnSpace project

## How can I edit this code?

There are several ways of editing your application.

**Use OnSpace**

Simply visit the [OnSpace Project]() and start prompting.

Changes made via OnSpace will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in OnSpace.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [OnSpace]() and click on Share -> Publish.

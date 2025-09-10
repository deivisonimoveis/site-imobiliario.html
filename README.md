
<!DOCTYPE html>
<html lang="pt-BR">![logo png](https://github.com/user-attachments/assets/3816ecf1-8037-4ba0-9267-37e4350bc20e)

<head>![perfil png](https://github.com/user-attachments/assets/1df3bd26-756e-4e9f-85e2-49a7c405a3e7)

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deivison Lemos Imóveis</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #333;
    }

    header {
      background: #5c3a1e;
      color: white;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    header img {
      height: 60px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 30px;
      background: #fff;
    }

    .hero img {
      border-radius: 50%;
      width: 180px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }

    .hero h1 {
      margin-top: 20px;
      color: #5c3a1e;
    }

    .filter {
      background: #5c3a1e;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .filter select,
    .filter input {
      padding: 10px;
      margin: 5px;
      border-radius: 5px;
      border: none;
    }

    .filter button {
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      background: #e0b200;
      cursor: pointer;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #333;
      color: white;
    }

    footer a {
      color: #e0b200;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho -->
  <header>
    <img src="img/logo.png" alt="Logo Deivison Lemos Imóveis">
    <nav>
      <a href="#">Início</a>
      <a href="#">Imóveis</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <!-- Foto + título -->
  <section class="hero">
    <img src="img/perfil.jpg" alt="Deivison Lemos">
    <h1>Deivison Lemos Imóveis</h1>
    <p>Compra e Locação • Guarapuava e Litoral</p>
  </section>

  <!-- Filtro de imóveis -->
  <section class="filter">
    <h2>Seu próximo imóvel começa aqui</h2>
    <p>Filtro rápido, encontre imóveis e entre em contato direto pelo WhatsApp.</p>
    <div>
      <select>
        <option>Compra</option>
        <option>Locação</option>
      </select>
      <select>
        <option>Casa</option>
        <option>Apartamento</option>
        <option>Terreno</option>
      </select>
      <select>
        <option>Guarapuava</option>
        <option>Praia</option>
      </select>
      <input type="text" placeholder="Procurar por nome ou detalhe">
      <button>Buscar</button>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>© 2025 Deivison Lemos Imóveis</p>
    <p><a href="https://wa.me/5542988368121" target="_blank">Fale comigo no WhatsApp</a></p>
  </footer>

</body>
</html>

[blackbox-output-code-UG5WW4TER5.txt](https://github.com/user-attachments/files/22176111/blackbox-output-code-UG5WW4TER5.txt)
# Deivison Lemos Imóveis

Site simples para venda de imóveis, desenvolvido em HTML, CSS e JavaScript puro. O site apresenta uma lista de imóveis disponíveis, seção sobre a imobiliária e formulário de contato.

## Funcionalidades

- Exibição de imóveis com fotos, descrição e preço.
- Formulário de contato com campo oculto para indicar interesse no imóvel.
- Layout responsivo para dispositivos móveis e desktop.
- Navegação simples com menu fixo.

## Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno.
2. Navegue pelas seções: Imóveis, Sobre e Contato.
3. Clique em "Quero Saber Mais" em qualquer imóvel para preencher automaticamente o formulário de contato com o imóvel selecionado.
4. Preencha o formulário e envie a mensagem (no exemplo atual, o envio é simulado).

## Como publicar

### Opção 1: GitHub Pages (gratuito)

- Crie um repositório no GitHub.
- Faça upload do arquivo `index.html`.
- Ative o GitHub Pages nas configurações do repositório.
- Configure seu domínio personalizado no GitHub Pages e no Registro.br.

### Opção 2: Hospedagem paga

- Contrate um serviço de hospedagem (ex: Hostinger, Locaweb).
- Faça upload do arquivo `index.html` para a pasta pública (ex: public_html).
- Configure o domínio para apontar para a hospedagem via DNS.

## Personalização

- Substitua as imagens dos imóveis pelos seus próprios arquivos.
- Ajuste textos e preços conforme necessário.
- Para envio real do formulário, integre com serviços como Formspree, EmailJS ou crie backend próprio.

## Contato

Para dúvidas ou suporte, entre em contato:

- Email: contato@deivisonlemosimoveis.com.br
- Telefone: (42) 98836-8121
---

© 2024 Deivison Lemos Imóveis - Todos os direitos reservados.
        [
          {
            "id":1,
            "title":"Casa no Centro",
            "description":"3 quartos, 2 banheiros, garagem para 2 carros.",
            "price":"R$ 350.000",
            "type":"casa",
            "trans":"compra",
            "city":"guarapuava",
            "image":"https://images.unsplash.com/photo-1560185127-6a1ff0b3a9c1?auto=format&fit=crop&w=800&q=60"
          },
          {
            "id":2,
            "title":"Apartamento Moderno",
            "description":"2 quartos, 1 suíte, vista panorâmica.",
            "price":"R$ 280.000",
            "type":"apartamento",
            "trans":"compra",
            "city":"praia",
            "image":"https://images.unsplash.com/photo-1570129477492-45c003edd2be?auto=format&fit=crop&w=800&q=60"
          }
          // Adicione mais imóveis aqui
        ]
        

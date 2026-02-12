Link Hub
# 🔗 Link Hub

Página de redirecionamento de links dinâmica, minimalista e de código aberto, desenvolvida para facilitar o acesso a informações acadêmicas e profissionais. 

Inspirado inicialmente na identidade visual do **CESAR School**, este projeto separa totalmente a camada de dados (links e cores) da camada de visualização (HTML/CSS), permitindo atualizações rápidas sem necessidade de refatoração de código.

## 🚀 Diferenciais Técnicos

- **Modularidade:** Configurações centralizadas em um arquivo `config.js` externo.
- **Segurança Visual:** Sistema de *Loading State* com spinner para evitar flashes de conteúdo não estilizado.
- **Ferramentas de Share:**
  - Cópia de link para área de transferência.
  - Gerador de **QR Code Dinâmico** (via QuickChart API) com validade infinita.
  - Função de **Download de QR Code** em formato .png.
  - Redirecionamento direto para WhatsApp.

## 🛠️ Como Personalizar

Para adaptar esta página à sua turma ou projeto:

1. Edite o arquivo `config.js`:
   - Altere o `tituloPrincipal` para o nome da sua disciplina (Ex: "Banco de Dados 2026.1").
   - Adicione seus links na array `meusLinks`.
   - Customize as cores hexadecimais em `cores`.

2. Certifique-se de ter os arquivos de imagem na raiz:
   - `Logo.png`: Logo principal centralizado.
   - `Share.png`: Ícone do botão de compartilhamento.

## 📦 Deploy no GitHub Pages

Este projeto foi estruturado para ser hospedado gratuitamente no GitHub Pages.

## 📄 Licença

Este projeto é **opensource**. Sinta-se livre para usar, modificar e distribuir para sua comunidade acadêmica.

---
*Organizado por Ivan Edward.*

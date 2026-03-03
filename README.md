# 📚 Frequência EBD — App Instalável

Aplicativo de controle de frequência para a Escola Bíblica Dominical 2026.  
Funciona **offline** e pode ser **instalado no Android** como um app nativo.

---

## 📱 Como instalar no celular (após publicar)

1. Acesse o link do GitHub Pages no navegador Chrome do Android
2. Toque no menu (⋮) → **"Adicionar à tela inicial"** ou **"Instalar app"**
3. Confirme e o ícone do EBD aparecerá na sua tela inicial
4. O app funciona **100% offline** após a primeira abertura

---

## 🚀 Como publicar no GitHub Pages (passo a passo)

### 1. Criar conta no GitHub
- Acesse [github.com](https://github.com) e crie uma conta gratuita

### 2. Criar o repositório
- Clique em **"New repository"** (botão verde)
- Nome sugerido: `frequencia-ebd`
- Marque como **Public**
- Clique em **"Create repository"**

### 3. Fazer upload dos arquivos
- Na página do repositório, clique em **"uploading an existing file"**
- Arraste **todos os arquivos e pastas** desta pasta para a área de upload:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - pasta `icons/` (com todos os ícones)
  - pasta `.github/` (com o workflow)
- Clique em **"Commit changes"**

### 4. Ativar GitHub Pages
- Vá em **Settings** → **Pages** (menu lateral)
- Em **Source**, selecione **"GitHub Actions"**
- Aguarde 1-2 minutos
- O link do seu app aparecerá no topo da página Settings > Pages

### 5. Acessar o app
- O link será: `https://SEU-USUARIO.github.io/frequencia-ebd/`
- Abra no Chrome do Android e instale!

---

## 💾 Sobre os dados

- Todos os dados ficam salvos **no próprio celular** (localStorage)
- Não requer internet após a instalação
- Cada celular tem seus próprios dados (não sincroniza entre dispositivos)

---

## 🔧 Estrutura dos arquivos

```
frequencia-ebd/
├── index.html          ← App principal
├── manifest.json       ← Configuração PWA (nome, ícones, cores)
├── sw.js               ← Service Worker (offline)
├── icons/              ← Ícones do app
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png    ← Ícone principal
│   ├── icon-384.png
│   └── icon-512.png    ← Ícone splash screen
└── .github/
    └── workflows/
        └── deploy.yml  ← Auto-deploy para GitHub Pages
```

---

## ✨ Funcionalidades

- ⛪ Cadastro de Igreja e Classe
- 👨‍🏫 Cadastro de Professores A e B
- 📝 Cadastro de até 100 alunos (com edição)
- 📅 Frequência 2026 — todos os domingos do ano
- ⭐ Destaque do Dia — boletim estatístico
- 👋 Registro de visitantes nominais
- 📊 Lista de frequência anual por aluno
- 📤 Exportar em PNG, WhatsApp e E-mail
- 💾 Funciona 100% offline

---

Desenvolvido com ❤️ para a Assembleia de Deus Jardim Imperial — Marituba/PA

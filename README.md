# pwa-eleicoes-2030

Contagem regressiva para o próximo ciclo eleitoral no Brasil (2030).

## 📱 Sobre o PWA

Este é um Progressive Web Application (PWA) que exibe uma contagem regressiva para as próximas eleições presidenciais no Brasil, previstas para **6 de outubro de 2030**.

## 🎯 Funcionalidades

- Contagem regressiva em dias, horas, minutos e segundos
- Tema escuro com toggle para modo claro
- Instalação como PWA no navegador (add to home screen)
- Notificação visual quando faltam poucos dias para as eleições
- Cache offline via Service Worker
- Ícones responsivos para diferentes telas

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- CSS3 com variáveis de tema
- JavaScript vanilla (ES6+)
- Service Worker para caching
- Web App Manifest

## 📁 Estrutura do Projeto

```
pwa-eleicoes-2030/
├── index.html          # Página principal com timer
├── manifest.json       # Metadados do PWA
├── service-worker.js   # Cache e instalação offline
├── styles.css          # Estilos com tema claro/escuro
├── app.js              # Lógica da contagem regressiva
├── icon-192.png        # Ícone 192x192px
├── icon-512.png        # Ícone 512x512px
└── README.md           # Este arquivo
```

## ⏰ Contagem Regressiva

A contagem é direcionada para **6 de outubro de 2030** (primeiro domingo de outubro, data das eleições presidenciais no Brasil).

## 🌓 Tema

O projeto utiliza tema cinza escuro por padrão (`#1e1e1e`), com toggle para modo claro disponível no canto superior direito. O tema é persistido no localStorage.

## 📦 Instalação como PWA

1. Acesse o site
2. Clique no botão "Instalar App" que aparece após o carregamento
3. Ou use o menu do navegador: "Adicionar à tela inicial" / "Install"

## 🚀 Deploy no Cloudflare Pages

Para fazer o deploy:

1. Conecte o repositório GitHub ao Cloudflare Pages
2. Build command: *(deixe em branco)*
3. Build output directory: `.`
4. Public directory: `./`

## 🔧 Customização

- **Data alvo**: Edite `TARGET_DATE` em `app.js`
- **Cores**: Modifique as variáveis CSS em `styles.css`
- **Ícones**: Substitua os arquivos PNG com sua identidade visual

## 👤 Autor

- [Thiago Santos](https://github.com/trcsantos)

## 📄 Licença

MIT
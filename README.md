# Spotify Interface Clone 🎧

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Uma réplica da interface do Spotify com funcionalidades de busca dinâmica e exibição de artistas, desenvolvida para praticar conceitos modernos de frontend.

---

## ✨ Funcionalidades Principais

- **Interface Fiel** reproduzindo o design do Spotify
- **Sistema de Busca** em tempo real com mock de API
- **Grid Responsivo** de playlists e categorias
- **Sidebar Interativa** com estados hover
- **Player Simulado** com efeitos visuais
- **Design Responsivo** para diferentes dispositivos
- **Transições Suaves** e animações CSS

---

## 🛠 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3 (Grid/Flexbox), JavaScript Vanilla
- **Estilização**: CSS Variables, Media Queries, Font Awesome Icons
- **Dados**: JSON Server (Mock API), Fetch API
- **Organização**: Arquitetura modular CSS

---

## 🚀 Como Executar

1. **Pré-requisitos**
   - Node.js instalado
   - Navegador moderno

2. **Instalação**

Clone o repositório
git clone https://github.com/seu-usuario/spotify-clone.git

Instale o json-server globalmente
npm install -g json-server

Inicie o servidor de dados
json-server --watch src/data/artists.json --port 3000


## 🎨 Componentes Principais
**Sidebar**

- Navegação principal

- Biblioteca de músicas

- Playlists personalizadas

- Controles de idioma

**Área Principal**
- Navegação com histórico

- Barra de pesquisa inteligente

- Grid de cards categorizados

- Exibição de resultados de artistas

**Footer**

- Chamada para upgrade premium

- Efeito de gradiente animado

## 📱 Responsividade
O layout se adapta a diferentes tamanhos de tela:

- Desktop (> 1015px): 5 colunas

- Tablet (768px): 2 colunas

- Mobile (< 480px): 1 coluna

## 💡 Melhorias Futuras
- Implementar reprodução real de áudio

- Adicionar sistema de login

- Criar drag-and-drop para playlists

- Integrar com API oficial do Spotify

- Adicionar modo escuro/diurno

## 📄 Nota
Projeto desenvolvido para fins educacionais. Não afiliado ao Spotify AB.

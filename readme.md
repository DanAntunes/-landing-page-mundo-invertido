# 🌌 Mundo Invertido - Stranger Things

![Preview do Site](./public/images/banner/logo.svg)

Um website imersivo que transporta os fãs para o universo de Stranger Things, com recursos interativos e design temático.

## 🚀 Demonstração

[![Vídeo Demo](https://img.youtube.com/vi/pWHSdQkvwgk/0.jpg)](https://www.youtube.com/watch?v=pWHSdQkvwgk)

## ✨ Funcionalidades Principais

- **Tema Dinâmico** Alternância entre mundos claro/escuro
- **Trilha Sonora Adaptativa** Música ambiente que muda com o tema
- **Galeria Interativa** Cenas marcantes da 4ª temporada
- **Formulário de Inscrição** Para o Clube de D&D de Hawkings
- **Player de Vídeo Integrado** Trailer oficial da temporada
- **Design Responsivo** Adaptado para diferentes dispositivos

## 🛠 Tecnologias Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

- **Fontes:** Archivo e JetBrains Mono (Google Fonts)
- **Semântica HTML:** Uso avançado de elementos semânticos
- **Acessibilidade:** ARIA labels e roles implementados
- **Transições CSS:** Efeitos visuais suaves

## 🎯 Objetivos do Projeto

- Praticar conceitos de desenvolvimento web front-end
- Implementar recursos de acessibilidade
- Criar uma experiência temática imersiva
- Explorar integração de mídia (áudio/vídeo)

## 📂 Estrutura de Arquivos

```
├── public/
│ ├── audio/ # Trilhas sonoras
│ ├── images/ # Assets visuais
│ │ ├── banner/ # Logo e elementos header
│ │ ├── content/ # Imagens do conteúdo
│ │ └── footer/ # Logo do desenvolvedor
├── src/
│ └── assets/
│ └── css/ # Folhas de estilo
└── index.html # Arquivo principal
```

## 🎨 Componentes Chave

### Tema Dinâmico

```javascript
function switchTheme() {
  document.body.classList.toggle('dark-theme');
  document.body.classList.toggle('light-theme');
  // Altera trilha sonora conforme o tema
}
```

## 📄 Licença

Este projeto está sob licença MIT 

Desenvolvido por Dan Antunes
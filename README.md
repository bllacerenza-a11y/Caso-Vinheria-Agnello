# 🍷 Vinheria Agnello

> **Status do Projeto:** 🚀 Finalizado / Em Desenvolvimento (E-commerce)

A **Vinheria Agnello** é um projeto de interface web desenvolvido para uma loja especializada em vinhos com mais de 15 anos de tradição em São Paulo. O objetivo do projeto é transpor a experiência técnica, consultiva e personalizada da loja física para o ambiente digital.

---

## 📑 Índice
* [Sobre o Projeto](#-sobre-o-projeto)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Estrutura do Site](#-estrutura-do-site)
* [Funcionalidades](#-funcionalidades)
* [Como Visualizar](#-como-visualizar)
* [Autores](#-autores)
* [Efeitos Visuais](#-efeitos-visuais)

---

## 📖 Sobre o Projeto
O site foi construído focando em uma identidade visual sofisticada que remete ao universo dos vinhos (tons de bordô, creme e madeira). Ele serve como um catálogo institucional e um canal de captação de novos talentos e contatos comerciais.

## 🛠 Tecnologias Utilizadas
O projeto foi desenvolvido utilizando as tecnologias fundamentais da Web:
* **HTML5:** Estruturação semântica de todas as páginas.
* **CSS3:** Estilização personalizada, layouts em Grid/Flexbox e responsividade.
* **Imagens:** Otimizadas para web nos formatos `.jpg` e `.webp`.

## 🗂 Estrutura do Site
O site é composto por 5 páginas principais:
1.  **Home (index.html):** Apresentação da marca, vídeo institucional e diferenciais.
2.  **História (historia.html):** A trajetória da família Agnello e seus valores.
3.  **Produtos (produtos.html):** Catálogo detalhado dividido por categorias (Tintos, Brancos, Reservas).
4.  **Galeria (galeria.html):** Exposição visual do ambiente e dos rótulos premium.
5.  **Contato (contato.html):** Informações de atendimento e formulário de recrutamento.

## ✨ Funcionalidades
- **Design Responsivo:** Adaptado para dispositivos móveis e desktops.
- **Navegação Semântica:** Uso de tags como `<header>`, `<main>`, `<section>` e `<footer>`.
- **Formulário de Cadastro:** Área dedicada para novos colaboradores enviarem seus dados e área de atuação.
- **Consultoria Técnica:** Seções informativas sobre *terroir*, castas e harmonização.

## 🎨 Efeitos Visuais
 
A partir do **Check-Point 02**, o projeto recebeu um arquivo dedicado de efeitos visuais (`css/efeitos.css`), importado ao final do `style.css`. Abaixo estão descritos todos os recursos implementados:
 
### 🎯 Pseudo-classes
 
| Pseudo-classe | Onde é aplicada | Efeito |
|---|---|---|
| `:hover` | Links da nav, botões, cards, imagens | Mudança de cor, escala e sombra |
| `:focus` | Inputs, textareas e selects | Borda bordô e brilho suave ao redor do campo |
| `:nth-child(odd)` | Itens de lista (`<ul> li`) | Fundo alternado levemente bordô com borda lateral |
| `:not(:last-child)` | Parágrafos | Espaçamento inferior entre parágrafos, exceto o último |
| `:checked` | Labels após checkbox/radio | Label em negrito e cor bordô quando marcado |
 
### 🖋 Pseudo-elementos
 
| Pseudo-elemento | Onde é aplicado | Efeito |
|---|---|---|
| `::before` | Títulos `<h2>` | Linha decorativa bordô de 50px antes do título |
| `::after` | Nome/logo no `<header>` | Adiciona o ícone 🍷 após o texto do cabeçalho |
| `::first-letter` | Primeiro parágrafo da seção principal | Letra inicial ampliada (2.2em) e na cor bordô |
| `::selection` | Qualquer texto selecionado | Fundo bordô com texto creme ao selecionar texto |
 
### 💫 Animações (`@keyframes`)
 
| Nome | Descrição | Onde é usada |
|---|---|---|
| `fadeSlideUp` | Fade-in com deslizamento de baixo para cima | Banner/hero do header e seções do `<main>` |
| `pulsarBotao` | Pulsar suave com brilho bordô irradiando | Botões e links de ação (CTA) |
| `girarLeve` | Rotação contínua de 360° | Disponível para uso em ícones decorativos |
 
### 🔄 Transições
 
- **Botões/CTAs:** transição suave de cor de fundo, sombra e escala ao `:hover`
- **Cards de produto:** elevação (`translateY`) e sombra ao passar o mouse
- **Imagens da galeria:** zoom (`scale`) e aumento de brilho (`brightness`)
- **Links do menu:** deslizamento leve para cima (`translateY(-3px)`)
- **Campos de formulário:** borda e brilho bordô ao receber `:focus`
### 🎢 Transformações CSS
 
| Transformação | Onde é aplicada | Efeito |
|---|---|---|
| `translateY(-6px)` | Cards de produto ao `:hover` | Efeito de elevação do card |
| `rotate(-2deg)` | Imagens da página História | Inclinação decorativa leve |
| `rotate(0deg) scale(1.04)` | Imagens da História ao `:hover` | Endireita e amplia levemente |
| `scale(1.08)` | Imagens da galeria ao `:hover` | Zoom suave na imagem |
| `scale(1.12)` | Imagens de contato ao `:hover` | Destaque ao interagir |
| `scale(1.05)` | Botões ao `:hover` | Leve aumento para feedback visual |
| `translateY(-3px)` | Itens do menu de navegação ao `:hover` | Levitação sutil |
 
## 🚀 Como Visualizar
Para rodar o projeto localmente: https://bllacerenza-a11y.github.io/Caso-Vinheria-Agnello
1. Faça o clone do repositório:
   ```bash
   git clone [https://github.com/bllacerenza-a11y/Caso-Vinheria-Agnello.git](https://github.com/bllacerenza-a11y/Caso-Vinheria-Agnello.git)
2. Navegue até a pasta do projeto.
3. Abra o arquivo index.html em qualquer navegador moderno.
👤 Autores
Desenvolvido por Pedro Oliveira, Bruno Bastos e Arthur Sgarbi como parte do estudo de desenvolvimento Web Front-end.

Este projeto foi criado para fins educacionais e de portfólio.

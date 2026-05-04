# 🍷 Vinheria Agnello - E-commerce Project

## 📋 Sobre o Projeto
Este projeto foi desenvolvido como parte do **Check-point de Front-End Design** do curso de Engenharia de Software. O objetivo é a criação de um portal de e-commerce para a **Vinheria Agnello**, uma tradicional loja de vinhos de São Paulo com mais de 15 anos de história.

### O Caso Vinheria Agnello
Gerenciada pelo Sr. Giulio e sua filha Bianca, a vinheria enfrenta o desafio de migrar para o ambiente digital sem perder seu principal diferencial: o **atendimento personalizado e consultivo**. O site foi projetado para oferecer uma experiência próxima à da loja física, auxiliando clientes (especialmente iniciantes) na escolha e harmonização de rótulos nacionais e internacionais.

---

## 🏗️ Estrutura do Projeto
O site é composto por **5 páginas HTML**, utilizando práticas de SEO, acessibilidade e design responsivo:

1.  **Home (`index.html`):** Apresentação da marca, destaques da loja e proposta de valor.
2.  **História (`historia.html`):** Apresentação da história e valores.
3.  **Produtos (`produtos.html`):** Catálogo de rótulos com descrições detalhadas de uvas e regiões.
4.  **Harmonização (`harmonizacao.html`):** Espaço consultivo para guiar o usuário na escolha do vinho ideal para cada refeição.
5.  **Pedidos (`pedido.html`):** Formulário para realizar um pedido.
6.  **Equipe (`equipe.html`):** Apresentação dos especialistas e sommeliers, humanizando a experiência digital (inclui **Tabela HTML** de cargos).
7.  **Contato (`contato.html`):** Canal direto com o cliente contendo formulário de mensagem e um **vídeo (iframe)** de apresentação da adega.

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica (`header`, `main`, `section`, `footer`).
* **CSS3:** Estilização personalizada, uso de variáveis `:root` para identidade visual (Vinho e Dourado) e Layout Responsivo.
* **SEO:** Implementação de Meta Tags (`description`, `keywords`) para otimização em motores de busca.

---

## ✨ Efeitos Visuais (CP2)

Para esta etapa, o projeto recebeu uma camada de interatividade e dinamismo utilizando apenas CSS puro. Os novos estilos estão centralizados no arquivo `efeitos.css`, importado globalmente.

### 🎯 Tecnologias e Conceitos Aplicados

#### 1. Pseudo-classes
Utilizadas para reagir às ações do usuário e estados dos elementos:
*   `:hover`: Feedback visual em botões, links e cards.
*   `:first-child`: Estilização diferenciada para o primeiro item do menu.
*   `:valid` e `:invalid`: Validação visual em tempo real nos campos de formulário (verde para sucesso, vermelho para erro).

#### 2. Pseudo-elementos
Adição de elementos decorativos sem poluir o HTML:
*   `::before`: Linha decorativa dourada abaixo dos títulos principais (`h2`).
*   `::first-letter`: Estilo *drop cap* (capitular) no início dos parágrafos, melhorando a estética editorial.
*   `::selection`: Personalização da cor de destaque quando o usuário seleciona um texto.

#### 3. Animações e Transições
*   **Animação de Entrada (`@keyframes`):** O efeito `aparecer` faz com que os cards surjam com um leve movimento de baixo para cima e transição de opacidade ao carregar a página.
*   **Transições Suaves:** Aplicadas em todos os elementos interativos para garantir que mudanças de cor, sombra e escala ocorram de forma fluida (0.3s).

#### 4. Transformações CSS
Uso de manipulação espacial para dar profundidade ao layout:
*   `scale()`: Aumento sutil de botões e links ao passar o mouse.
*   `translateY()`: Efeito de "levitação" nos cards de produtos.
*   `rotate()`: Leve inclinação em imagens para um visual moderno.
*   `skewY()`: Inclinação de seção (diagonal) para quebrar a monotonia do layout horizontal.

---

## 🔧 Como os arquivos foram organizados

1.  Os novos efeitos foram isolados no arquivo `css/efeitos.css`.
2.  A integração foi feita através da importação no arquivo principal:
    ```css
    /* style.css */
    @import url("efeitos.css");

## 👥 Integrantes do Grupo
* [Guilherme Pereira Ruiz da Silva] - RM: [573360]
* [Gustavo Bidin Marto] - RM: [570272]
* [Gustavo Leal] - RM: [569361]
* [Matheus Mandu de Lima] - RM: [571348]

---

## 🚀 Link do Projeto (GitHub Pages)
O site pode ser visualizado online através do link abaixo:
🔗 [Clique aqui para acessar o site](https://gprsilva.github.io/VinhariaAgnello/)

---

*Projeto acadêmico desenvolvido para a disciplina de Front-End Design - 2026(Turma-1ESPQ)*

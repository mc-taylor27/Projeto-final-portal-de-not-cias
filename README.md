# 📰 Profeta Diário - Projeto de Notícias
### Desenvolvido por Maria Clara Taylor Pavoni Pereira durante o curso de Desenvolvimento de Sistema-SENAI

## 🎯 Objetivo da Sprint 3

O foco desta Sprint foi aprimorar a **Experiência do Usuário (UX)** e a **Responsividade**, implementando recursos avançados de CSS e garantindo a adaptação correta do layout em todos os dispositivos.

## ✨ Destaques Técnicos Implementados

### 1. Responsividade Completa e Menu Hambúrguer

* **Menu Responsivo:** Implementado o padrão **Menu Hambúrguer (CSS-Only)**, utilizando `<input type="checkbox">` e o seletor `~` (irmão subsequente) para alternar a visibilidade da navegação em telas móveis (`< 768px`).
* **Layout Adaptativo:** Utilização de `media queries` para adaptar o layout de 3 colunas (página "Mundo") para uma única coluna em dispositivos móveis.
* **Header Fixo:** A navegação principal permanece sempre visível com `position: fixed`.

### 2. Layout da Home Page (Flexbox e Grid)

* **Listas Lado a Lado:** A seção de Categorias e Notícias Mais Lidas foi agrupada em uma `div` e utiliza **Flexbox** para dividir o espaço horizontalmente.
* **Vídeo Centralizado:** O bloco de vídeo fica na linha de baixo (separado do Flexbox das listas) e utiliza `text-align: center` para garantir a centralização na página.

### 3. Efeitos CSS Avançados

* **Pseudo-classes:** Uso de `:hover` (para links e cards), `:focus` (para campos de formulário) e `:nth-child` (para "zebra-striping" nas tabelas).
* **Transições e Transformações:** Utilização de `transition` para suavizar interações visuais e `transform: scale(1.02)` no botão de envio para feedback de clique.

### 4. Validação e Boas Práticas

* **Conformidade W3C:** Remoção de todos os atributos de estilo HTML obsoletos (como `border="1"` nas tabelas), garantindo que a estrutura passe na validação.

## ⚙️ Como Executar o Projeto

Basta abrir o arquivo `index.html` em qualquer navegador moderno.
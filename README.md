#  Projeto Google Glass - Interface Interativa

Este projeto foi desenvolvido como parte de um estudo aprofundado em **HTML5**, **CSS3** e **JavaScript**, focado em criar uma interface rica, informativa e interativa sobre o dispositivo de realidade aumentada do Google.

O site simula uma revista digital ou portal de tecnologia, utilizando diversas técnicas de manipulação de elementos e multimídia.

---

##  Funcionalidades e Conceitos Técnicos

Para alcançar interatividade foram aplicadas as seguintes tecnologias:

### 1. Menu Dinâmico com Troca de Ícones
* **Termo Técnico:** `DOM Manipulation` e `Hover Listeners`.
* **Como funciona:** Ao passar o mouse sobre as opções do menu (Home, Fotos, etc.), o ícone principal da lateral direita é alterado. Isso foi feito utilizando JavaScript para monitorar o evento de mouse e trocar o atributo `src` da imagem dinamicamente.

### 2. Imagem Mapeada (Raio-X)
* **Termo Técnico:** `HTML Image Maps` (`<map>` e `<area>`).
* **Como funciona:** Na aba **Especificações**, utilizei um mapeamento de coordenadas sobre um desenho do Google Glass. Isso permite que áreas específicas (os pontos vermelhos) se tornem links ou gatilhos de informação, detalhando cada componente do óculos.

### 3. Galeria com Efeito Zoom
* **Termo Técnico:** `CSS Transitions` e `Pseudo-classes (:hover)`.
* **Como funciona:** Na aba **Fotos**, as imagens possuem um efeito de ampliação suave. Quando o usuário posiciona o cursor, a imagem aumenta de tamanho e ganha destaque através da propriedade `transform: scale()`.

### 4. Multimídia e Estilização Retro
* **Termo Técnico:** `HTML5 Audio & Video API`.
* **Como funciona:**
    * **Vídeo:** Inserido dentro de uma moldura de televisão antiga para um visual nostálgico.
    * **Áudio:** Um rádio antigo funcional que permite ao usuário ouvir uma demonstração sonora, utilizando as tags nativas `<audio>` e `<video>`.

### 5. Formulário de Encomenda Inteligente
* **Termo Técnico:** `Form Validation` e `Input Types`.
* **Como funciona:** A página de **Contato** utiliza novos tipos de campos do HTML5 (como `date`, `number` e `range`) e scripts para calcular o valor total da encomenda em tempo real conforme a quantidade é alterada.

---

##  Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e mapeamento de imagens.
* **CSS3:** Design responsivo, posicionamento (`relative/absolute`) e animações de transição.
* **JavaScript:** Lógica de interatividade do menu e cálculos do formulário.

---

##  Como rodar o projeto

1. Faça o download ou clone este repositório.
2. Certifique-se de que todas as pastas de imagens e vídeos estão no mesmo diretório.
3. Abra o arquivo `index.html` em seu navegador de preferência.

---
Desenvolvido por **Isadora Franzon** durante estudos de Front-end.

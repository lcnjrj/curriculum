# curriculum
https://lcnjrj.github.io/curriculum/



## Currículo Online Com HTML e GitHub Pages


### Referências:

W3C: https://www.w3schools.com/howto/howto_website_create_resume.asp

Lembre-se de incluir comentários no seu código para facilitar a compreensão e a manutenção futura do projeto. Boa sorte!

As correções abaixo focam em transformar as tags HTML em blocos de código para que o navegador não as interprete erroneamente, além de organizar a hierarquia de títulos e listas para facilitar a leitura.

---

## CONCEITOS UTILIZADOS

### HTML
Algumas das principais tags e conceitos que utilizamos para o desenvolvimento desse projeto foram:

* `<!DOCTYPE html>`: Declaração que define o tipo de documento como HTML5.
* `<html>`: Tag raiz que contém todo o conteúdo da página.
* `<head>`: Onde as informações de cabeçalho são colocadas (título, meta, links).
* `<meta charset="UTF-8">`: Define a codificação de caracteres como UTF-8.
* `<title>`: Define o título da página exibido na guia do navegador.
* `<link>`: Usado para importar arquivos de estilo externos e fontes.
* `<body>`: Onde fica todo o conteúdo visível da página.
* `<nav>`: Define uma seção de navegação, como um menu.
* `<div>`: Tag genérica usada para agrupar elementos e criar contêineres.
* `<h2>`: Define um cabeçalho de segundo nível.
* `<p>`: Define um parágrafo de texto.
* `<i>`: Define um elemento de texto em itálico.
* `<hr>`: Define uma linha horizontal.
* `<b>`: Define um texto em negrito.
* `id`: Atributo que define um identificador exclusivo para um elemento.
* `<br>`: Define uma quebra de linha.
* `<span>`: Define um pequeno trecho de texto em linha.
* `fa`: Classe de ícones do **Font Awesome**.
* `w3`: Classe de estilo do framework **W3.CSS**.
* `style.css`: Nome do arquivo CSS externo.
* `<footer>`: Define a seção de rodapé da página.

---

### CSS

#### Classes W3.CSS e Font Awesome:
* **w3-twothird**: Define a largura de dois terços do contêiner pai.
* **w3-container**: Adiciona preenchimento e centralização horizontal.
* **w3-center**: Centraliza o conteúdo horizontalmente.
* **w3-card**: Cria uma sombra que assemelha o elemento a um cartão.
* **fa**: Aplica os estilos básicos aos ícones.

#### Propriedades CSS utilizadas:
* **color**: Define a cor do texto.
* **background-color**: Define a cor de fundo.
* **font-size**: Define o tamanho da fonte.
* **padding**: Define o preenchimento interno.
* **margin**: Define a margem externa.
* **text-align**: Define o alinhamento horizontal do texto.
* **box-shadow**: Cria uma sombra ao redor do elemento.
* **display**: Define o comportamento de exibição (ex: `block`, `flex`).
* **border-radius**: Define o arredondamento dos cantos.

#### Conceitos Fundamentais:
* **Seletores ID e Class**: O ID usa `#` e deve ser único; a Classe usa `.` e pode ser repetida em vários elementos.
* **Font Awesome**: Biblioteca de ícones vetoriais personalizáveis.
* **Box Model**: Modelo de caixa que engloba conteúdo, preenchimento (padding), borda e margem.
* **Responsividade**: Adaptação do layout a diferentes tamanhos de tela.

---

### DICIONÁRIO FRONT-END (RESUMO)

* `<img>`: Define uma imagem a ser exibida.
* `<button>`: Cria um botão clicável.
* **GitHub Pages**: Serviço de hospedagem gratuita do GitHub para sites estáticos.
* **Jekyll**: Gerador de sites estáticos integrado ao GitHub Pages.

---

Aqui estão as explicações detalhadas para esses dois conceitos fundamentais, formatadas para facilitar a leitura e o aprendizado.

---

## 📦 Box Model (Modelo de Caixa)

O **Box Model** é a base do design e layout na web. No CSS, praticamente tudo é tratado como uma caixa retangular. Compreender como essas camadas se somam é essencial para controlar o tamanho real dos elementos na tela.

### Componentes do Box Model:

1.  **Content (Conteúdo):** É o centro da caixa, onde o texto ou as imagens aparecem.
2.  **Padding (Preenchimento):** O espaço transparente entre o conteúdo e a borda. Ele empurra a borda para fora do conteúdo.
3.  **Border (Borda):** A linha que envolve o preenchimento e o conteúdo.
4.  **Margin (Margem):** O espaço transparente fora da borda. Ele separa o elemento de outros elementos ao seu redor.



### Cálculo de Tamanho:
Por padrão, quando você define `width: 200px`, você está definindo apenas o **conteúdo**. O tamanho total ocupado pelo elemento será:
> **Total** = Conteúdo + Padding + Border + Margin.

---

## 🧪 Jekyll

O **Jekyll** é um gerador de sites estáticos (Static Site Generator - SSG). Ele foi criado para transformar arquivos de texto simples em sites e blogs prontos para serem publicados.

### Como ele funciona:
* **Transformação:** Ele pega arquivos escritos em **Markdown** (texto puro) e processa através de templates (usando uma linguagem chamada **Liquid**).
* **Resultado Final:** O Jekyll gera uma pasta com arquivos puros de HTML, CSS e JS. Não há banco de dados envolvido na visualização final.
* **Integração com GitHub:** É o "motor" por trás do **GitHub Pages**. Quando você envia seus arquivos para o GitHub, ele roda o Jekyll automaticamente para construir seu site.

### Principais vantagens:
* **Velocidade:** Sites estáticos carregam muito rápido, pois o servidor não precisa processar dados a cada clique.
* **Segurança:** Sem banco de dados ou PHP, as chances de invasão são drasticamente reduzidas.
* **Custo Zero:** Pode ser hospedado gratuitamente no GitHub ou GitLab.



---

### Exemplo de Front Matter no Jekyll:
No topo de cada arquivo Markdown no Jekyll, usamos um bloco chamado **Front Matter** para definir variáveis como o título e o layout:

```markdown
---
layout: post
title: "Meu Primeiro Artigo"
date: 2026-04-21
---
Aqui começa o conteúdo do meu post...
```

### Saiba mais:
* **Emojis**: [W3Schools Emoji Reference](https://www.w3schools.com/charsets/ref_emoji.asp)

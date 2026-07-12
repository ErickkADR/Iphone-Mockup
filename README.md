# iPhone Mockup — Redes Sociais

Mockup interativo de iPhone, feito em **HTML e CSS**, onde a "tela" do celular é um `<iframe>` que troca de conteúdo ao clicar nos ícones de rede social ao lado — como se fosse abrir um app de verdade dentro do aparelho.

🔗 **Demo:** [erickkadr.github.io/Iphone-Mockup](https://erickkadr.github.io/Iphone-Mockup/)

<div align="center">
  <img width="100%" src="https://user-images.githubusercontent.com/99443921/213888375-a3d9a5fb-9306-41ee-9789-1f74e7e543ca.gif"/>
</div>

<div align="center">
<br>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

## Print

<div align="center">
  <img src="docs/screenshot.png" alt="Mockup de iPhone com tela inicial e ícones de redes sociais" width="600" />
</div>

## Sobre o projeto

Um mockup de iPhone 100% em CSS (bordas, notch, botões), com uma "tela inicial" falsa cheia de ícones de app, e uma barra lateral com atalhos (Home, YouTube, GitHub, Instagram, Twitter, Facebook). Cada atalho troca o conteúdo do `<iframe>` interno — o mockup nunca recarrega, só o "app" de dentro muda.

## Motivação

Explorar até onde dava pra chegar usando **só HTML e CSS** para simular algo que normalmente pareceria coisa de app/JS framework — a navegação entre "telas" sem nenhuma linha de JavaScript, usando o atributo `target` de um iframe nomeado.

## Funcionalidades

- Mockup de iPhone desenhado em CSS (moldura, notch, botão home)
- Navegação entre 6 "telas" (Home, YouTube, GitHub, Instagram, Twitter, Facebook) via iframe, sem recarregar a página
- Tela inicial com grade de ícones de apps, dock e status bar simulados
- Barra lateral de atalhos com os ícones de cada rede

## Tecnologias

- **HTML5** (`<iframe>` nomeado + `target` para navegação sem JS)
- **CSS3** (posicionamento absoluto, grid, moldura do aparelho)

## Como rodar localmente

Sem build, sem dependência — abra `index.html` no navegador ou sirva a pasta:

```bash
npx serve .
```

---

### Made with ♥ by Erick Dantas | [Contato](https://www.linkedin.com/in/erickkadr/)

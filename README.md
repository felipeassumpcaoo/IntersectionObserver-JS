#  Scroll Reveal com JavaScript Puro usando IntersectionObserver

Este projeto demonstra como criar **animações suaves** em um site apenas com **HTML, CSS e JavaScript puro** — sem precisar de bibliotecas externas como AOS.js ou ScrollMagic.

---

## Analogia

Imagine que o site tem um **vigia invisível**. Ele fica observando tudo que acontece na tela.

Quando você rola a página e uma parte do conteúdo aparece, o vigia diz:  
> “Ei, esse elemento entrou na tela! Hora de mostrar ele com estilo!”

E aí entra a mágica ✨: o elemento aparece suavemente com transições de opacidade e movimento.

---

##  Como funciona

- Utilizamos a API nativa `IntersectionObserver` para monitorar quando elementos entram na área visível da tela.
- As seções começam escondidas com a classe `.hidden`.
- Quando entram na tela, o JS troca para `.show`, ativando a animação via CSS.

---

##  Tecnologias usadas

- HTML5
- CSS3 (transitions + transform)
- JavaScript Puro (ES6)
- API IntersectionObserver

---




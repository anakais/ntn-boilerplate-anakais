---
createdAt: 2021-03-01
title: Aprenda a editar o conteúdo desse blog!
description: E saiba um pouco mais sobre um CMS baseado em repositório GIT
---
É muito fácil escrever conteúdo em **markdown**, exatamente como este que você está lendo. Com suporte para imagens e até mesmo trechos de código.

![Placeholder Coffee](https://media.istockphoto.com/photos/close-up-of-steaming-cup-of-coffee-or-tea-on-vintage-table-early-on-picture-id1137365972?k=6&m=1137365972&s=612x612&w=0&h=m61gLuI0gAOh0IRbBxYzfyWgRbXUUTuZHf5sisVArK4=)

Veja esse código:

```css
@font-face {
  font-family: 'DM Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url('~assets/fonts/DMSans-Regular.ttf') format('truetype');
}
```

> Escrever em markdown é tão simples como formatar um texto no whatsapp, insira alguns \*\* ou alguns ## e você terá um **negrito**, *itálico* ou um título.

### Passos para editar e criar novos conteúdos:

1. **Vá para admin:** Você pode navegar para a página de admin digitando `https://mystifying-brahmagupta-cac4b8.netlify.app/admin` na caixa de endereço de seu navegador acima.
2. **Navegue até Blog:** Em blog, você pode editar postagens existentes como esta, removê-las ou criar novas. Isso criará uma branch (ramo) dentro do projeto, que será mesclada quando for salva na próxima etapa.
3. **Salve suas alterações:** Depois de editar o conteúdo do site, você precisa salvá-lo. Isso irá acionar o Netlify CMS para mesclar o conteúdo (branch) ao projeto principal.
4. **Pegue um café:** Depois de salvar, você tem que esperar o Netlify construir sua branch principal (o que provavelmente leva de 2 a 5 minutos, dependendo de sua configuração). Se você quiser mais controle, faça login no Netlify para assistir a execução de sua compilação e ver quando ela é publicada. Lá você também pode publicar commits (versões) mais antigos.
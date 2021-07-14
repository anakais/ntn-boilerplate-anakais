---
createdAt: 2021-03-01
title: Como editar o conteúdo
description: E o que esperar ao executar um CMS baseado em repo
---
It is easy to write **markdown**-*enabled* content like this placeholder text, with support for images and even code snippets.

If you are in local development-mode (`npm run dev`) you can double-click here to edit and save this page quickly.

```javascript
formatDate(dateString) {
  const date = new Date(dateString)
  return date.toLocaleDateString(process.env.lang) || ''
}
```

![Placeholder Kitten](https://media.istockphoto.com/photos/close-up-of-steaming-cup-of-coffee-or-tea-on-vintage-table-early-on-picture-id1137365972?k=6&m=1137365972&s=612x612&w=0&h=m61gLuI0gAOh0IRbBxYzfyWgRbXUUTuZHf5sisVArK4=)

### Steps to take:

1. **Go to admin:** You can navigate to the admin-page by typing in `/admin` after the URL your browser’s omnibox above.
2. **Navigate to Blog:** In blog you can edit existing blog posts like this one, remove it, or create new ones. They’ll be added to a pull request by Netlify CMS that you merge in the next step by saving.
3. **Save your changes:** After you have edited the content on the site, you need to save. This will trigger Netlify CMS to merge the PR to the main branch (it will show up in your git log).
4. **Grab a coffee:** After saving, you have to wait for Netlify to build your main branch (which probably takes 2-5 minutes, depending on your setup). If you’re a control-freak, login to Netlify to watch your build run and see when it is published. You can also publish older commits from there."
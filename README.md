# Curso de Verão em Bioinformática da Universidade Federal de Minas Gerais

![](static/cvbioinfoufmg-twitter-banner.png)

As inscrições estão abertas entre agora em nosso site <> e preencha o formulário de inscrição! 


Para saber das novidades acompanhe nossa página no Instagram: <https://www.instagram.com/bioinfo_ufmg/>

---

To build and develop locally

```bash
git clone --recurse-submodules https://github.com/cvbioinfoufmg/cvbioinfoufmg.github.io.git

cd cvbioinfoufmg.github.io

hugo serve -D --disableFastRender
```

if theme assets need to be changed run `npm run build` to build the minified version

To update, pull, edit, and push back to GitHub.

## Edit data

You can edit

* general information about the site into the `config.toml` file.
* some data into `data/*.yml` files, like header or footer information
* some content into `content/**` files.
* some static assets like images into the `static/*` folder

---

This website is build with [Hugo](https://gohugo.io/) using the [devfest](https://github.com/GDGToulouse/devfest-theme).

This repo is set to use [GitHub Actions](https://github.com/peaceiris/actions-gh-pages) to build and deploy the website to GitHub Pages.

---

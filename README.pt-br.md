![HostCorps](/img/HostCorps.png)

# HostCorps

Site de uma empresa fictícia de hospedagem. Construído com HTML5, CSS3 e JavaScript puro. A webApp pode ser acessada [aqui](https://nothingnothings.github.io/HostCorps).

Esta versão do aplicativo foi feita sem Webpack; a versão com Webpack, que possui um fluxo de trabalho de implantação com GitHub Actions, pode ser encontrada [aqui](https://github.com/nothingnothings/HostCorpsWebpackVersion).

![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/nothingnothings/HostCorps/master?style=flat-square)
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/nothingnothings/HostCorps)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/nothingnothings/HostCorps/blob/master/README.pt-br.md)



## Tecnologias

Algumas das linguagens e bibliotecas empregadas:

- HTML5
- CSS3 (animações, Flexbox, media queries)
- JavaScript puro (sem frameworks JavaScript; uso de `var`, funções normais e eventListeners comuns)
- Lógica de validação de formulários (validação básica de entrada, lógica para adicionar e remover estilos de "foco" e "inválido", etc.)
- Design responsivo para dispositivos móveis (barra lateral, Flexbox, media queries)

## Estrutura de Diretórios do Projeto


Conforme estrutura dos ramos `master` e `gh-pages`:

```
.\
│
├── customers\
│   ├── customers.css
│   └── index.html
│
├── fonts\
│   ├── UniSansHeavyCAPS.woff
│   ├── UniSansHeavyCAPS.woff2
│   ├── anonymousPro-Bold.ttf
│   └── anonymousPro-Regular.ttf
│
├── img\
│   ├── HostCorps.png
│   ├── HostCorps.svg
│   ├── customer-1.jpg
│   ├── customer-2.jpg
│   ├── customer-3.jpg
│   └── freedom.jpg
│
├── packages\
│   │
│   ├── images\
│   │   └── plan.jpg
│   │
│   ├── index.html
│   └── packages.css
│
├── start-hosting\
│   ├── index.html
│   ├── start-hosting.css
│   └── start-hosting.js
│
├── .gitignore
├── README.md
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── apple-touch-icon.png
├── browserconfig.xml
├── favicon-16x16.png
├── favicon-32x32.png
├── favicon.ico
├── index.html
├── mstile-150x150.png
├── safari-pinned-tab.svg
├── shared.css
├── shared.js
├── site.webmanifest
└── style.css
```


## Configuração

Para usar este projeto, clone-o usando o Git:

1. Execute `git clone` para clonar o projeto em seu repositório local do Git.
2. Sirva os arquivos com a ajuda de um provedor de hospedagem (apenas frontend).

## Funcionalidades

- Múltiplas páginas (diferentes páginas HTML, servidor de páginas normal)
- Lógica de validação de formulários na página "Start Hosting"
- Design responsivo (móvel e desktop) criado com Flexbox e media queries
- Adição/removal de classes CSS (animação "slide-in") implementada com JavaScript
- Uso de GitHub Actions para, por meio do comando `git push`, transferir o conteúdo do ramo `master` para o ramo `gh-pages`, que então realiza o deploy em https://nothingnothings.github.io/HostCorps
- Favicon personalizado, compatível com vários dispositivos

## Inspiração

Inspired by the "JavaScript - The Complete Guide" course by Maximilian Schwarzmüller.

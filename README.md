# PROSYS Sites — Estrutura Profissional

Pacote pronto para GitHub Pages, com URLs profissionais sem `.html` nas páginas principais.

## Estrutura

```txt
index.html
barbearia/
  index.html
  app.html
salao/
  index.html
  app.html
estetica/
  index.html
  app.html
README.md
```

## Links esperados

```txt
https://prosys-web.github.io/prosys-sites/
https://prosys-web.github.io/prosys-sites/barbearia/
https://prosys-web.github.io/prosys-sites/barbearia/app.html
https://prosys-web.github.io/prosys-sites/salao/
https://prosys-web.github.io/prosys-sites/salao/app.html
https://prosys-web.github.io/prosys-sites/estetica/
https://prosys-web.github.io/prosys-sites/estetica/app.html
```

Suba o conteúdo extraído na raiz do repositório `prosys-sites`.


## Planos comerciais

- `index.html` em cada nicho = Plano Essencial
- `app.html` em cada nicho = Plano Profissional com Agenda Inteligente
- `premium.html` em cada nicho = cópia/atalho da versão premium

A versão premium mantém o mesmo visual, fontes, cores, imagens, preview e contexto da página essencial, substituindo a agenda simples por uma agenda inteligente estilo app/sistema.


## Fix final mobile imagens

A galeria foi convertida de background-image para imagens reais <img>, para evitar falha de renderizacao no Android/mobile.
Nao foram alterados previews OG, links, WhatsApp, textos ou valores.

<p align="center">
  <a href="http://garotasenxaqueca.com">
    <img src="static/images/logo/ge-logo.png" alt="Garotas Enxaqueca Logo">
  </a>

  <h3 align="center">Web Site Garotas Enxaqueca</h3>

  <p align="center">
    Em Construção ⌛
  </p>
</p>

## Requisitos:

Para rodar o projeto localmente você primeiramente deve ter na sua máquina o Hugo:

- [x] Hugo

Para instalar:

- [ ] macOS: `$ brew install hugo`
- [ ] windows: `$ choco install hugo -confirm`
- [ ] linux: `$ sudo apt-get install hugo`

Para mais detalhes, conferir no [site oficial do Hugo](https://gohugo.io).

### Rodar Projeto

Para rodar o projeto localmente:

`hugo serve -D`

Acessar [http://localhost:1313/](http://localhost:1313/)

### Novos Posts

:zap: Em verificação :zap:

Para criar novos posts

`hugo new blog/<nome-do-post>.md`

**Observação:** Para os posts serem publicados o campo **draft** precisa estar como *false*.

## Avisos

1. Não alterar nada da pasta **theme**, pois ela contém todo o código fonte do tema, o certo é recriar a pasta e o arquivo na raiz do projeto, pois assim o tema entende que estamos sobrescrever e personalizando o site.

[ ![Codeship Status for tableless/tableless-static](https://app.codeship.com/projects/552ac1e0-ffa1-0134-e51e-2e94cfed1b0b/status?branch=master)](https://app.codeship.com/projects/212354)

# Tableless estático baseado em Hugo
Este é o site do Tableless estático. Nada de Wordpress, nem qualquer outro CMS back-end. Os artigos são escritos em Markdown, com um frontmatter em yaml fácil de entender.

## Rodando o projeto
Para rodar o projeto você vai precisar do [Hugo](https://gohugo.io/) instalado na sua máquina. O CSS está usando SASS como pré-processador, para tanto, você precisa ter [SASS instalado na máquina](http://sass-lang.com/install). Uma vez instalado, você pode rodar o comando:

```
cd themes/tableless/static/css/
sass --watch style.sass:style.css --style compressed
```

As vezes quando tento rodar o server do Hugo, acontece de dar um erro no terminal assim: `ERROR 2017/09/03 08:56:44 Error: listen tcp 127.0.0.1:1313: socket: too many open files in system`

Consegui resolver, eu acho, usando as dicas desse link: [https://blog.dekstroza.io/ulimit-shenanigans-on-osx-el-capitan/](https://blog.dekstroza.io/ulimit-shenanigans-on-osx-el-capitan/)

## Hugo
O gerador que estamos usando agora é o [Hugo](https://gohugo.io/)... um gerador de arquivos estáticos escrito em Go.

Se você quiser contribuir, por favor, clone o projeto e submeta um Pull Request. Mais do que nunca vamos precisar de ajuda agora.
Para rodar o projeto, leia o [Quick Start do guia do Hugo](https://gohugo.io/overview/quickstart/). É super rápido e não precisa de tanto setup como outros geradores de conteúdo estático.

## Submetendo artigos
Se você quer ser um autor, leia nesta [página as instruções](http://tableless.com.br/seja-um-autor/) e submeta seus artigos.


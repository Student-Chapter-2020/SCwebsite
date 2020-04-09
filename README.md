# Instruções para os membros atualizarem o website do capítulo estudantil:

Este website é um site estático. Sites estáticos são comumente utilizados para apresentação de um projeto, publicação de artigos, atividades em grupo na forma escrita. 

O site do capítulo foi concebido como um site monocoluna que utiliza o tema Air do [Hugo](http://gohugo.io/). O projeto original pode ser acessado em [syui](https://github.com/syui/hugo-theme-air). O usuário membro deste website deverá ter como pré-requisito uma conta no git-hub e ser membro do projeto do capítulo estudantil. Uma vez tendo esses pré-requisitos atendidos o membro deverá abrir o terminal e digitar os seguintes comandos. 


```bash
$ git clone https://github.com/Student-Chapter-2020/SCwebsite.git

$ cd SCwebsite

$ cd content/post/

```
## Atualizando o Site:

A parte textual do website é toda escrita em **Markdown**. Basta o membro acessar o arquivo a ser editado e adicionar o novo conteúdo. Com o novo conteúdo salvo abra o terminal na pasta aonde está localizado o arquivo e digite.


```bash
$ git add arquivo.md

$ git commit -m " DIGA O QUE VOCÊ MODIFICOU"

$ git pull

```

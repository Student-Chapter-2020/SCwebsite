# Instruções para os membros atualizarem o website do capítulo estudantil:

Este website é um site estático. Sites estáticos são comumente utilizados para apresentação de um projeto, publicação de artigos, atividades em grupo na forma escrita. 

O site do capítulo foi concebido como um site monocoluna que utiliza o tema Air do [Hugo](http://gohugo.io/). O projeto original pode ser acessado em [syui](https://github.com/syui/hugo-theme-air). O usuário membro deste website deverá ter como pré-requisito uma conta no git-hub e ser membro do projeto do capítulo estudantil. 


## O primeiro acesso:

Uma vez tendo esses pré-requisitos atendidos o membro deverá abrir o terminal e digitar os seguintes comandos, no seu primeiro acesso. 


```bash
$ git clone https://github.com/Student-Chapter-2020/SCwebsite.git

$ cd SCwebsite

$ cd content/post/

```
## Atualizando o Site:

A parte textual do website é toda escrita em **Markdown**.Basta o membro acessar o arquivo a ser editado e adicionar o novo conteúdo. Com o novo conteúdo salvo abra o terminal na pasta aonde está localizado o arquivo e digite.


```bash

$ git add arquivo.md

$ git commit -m " DIGA O QUE VOCÊ MODIFICOU"

$ git pull

```

## Segundo e demais acessos:

Uma vez que o membro do capítulo tenha logrado êxito em seu primeiro *push* ele deverá sempre atualizar para o seu repositório local as últimas atualizações, modificar o arquivo desejado com as últimas informações e atualizar o repositório global. Para tanto este deverá seguir a seguinte lógica de trabalho, em três etapas. 


1- Atualizar o repositório local para a última versão. 

'''bash

$ git pull

'''

2- Modificar o arquivo alvo com as últimas informações através do editor de texto de sua preferência.

3- Atualizar o repositório global para atualizar o website na rede

```bash

$ git add arquivo.md

$ git commit -m " DIGA O QUE VOCÊ MODIFICOU"

$ git pull

```

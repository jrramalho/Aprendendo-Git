# Aprendendo Git

##Configurações iniciais

```shell

$ git config --global user.name "Ramalho Junior"
$ git config --global user.email "jrramalho@hotmail.com" 

```

## Inicializar um repositório

```shell

$ mkdir aprendendo-git #criar pasta
$ cd aprendendo-git #entra na pasta
$ git init #cria um novo repositório

```
## git-status

```shell

$ git status #mostra o status do repositório

```

##Realizando um Commit

```shell

$ git add README.md
$ git commit -m, "Mensagem de Commit"

```


##Visualizando os logs

```shell

$ git log

```

##Visualizando as diferenças

```shell

$ git diff README.md #mostra a diferença desse arquivo para o último commit

```

##Descartando as mudanças 

```shell

# $ git checkout -- README.md #descarta as mudanças do arquivo no último commit

```
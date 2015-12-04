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
$ git log --full-diff -p README.md
```

##Visualizando as diferenças

```shell
$ git diff README.md #mostra a diferença desse arquivo para o último commit
```

##Descartando as mudanças

```shell
$ git checkout -- README.md #descarta as mudanças do arquivo no último commit
```

##Retornando para versão anterior

```shell
git checkout (cola rash) #retornar para ultimo rash
```

##Retornando para documento original

```shell
git checkout master #retornar documento original
```

##Trabalhando com Branch


```shell
$ git branch							#listando todas as branchs
$ git checkout -b <nome da branch>		#cria e troca para nova branch
$ git checkout <hash ou branch-name> 	#troca de branch
```

##Realizando Merge

```shell

1. ir para branch na qual receberá mudança ```git checkout master```

2. Digite comando ```git merge develop```

3. Inserir atributo nome


```

```shell
$ git clone <repositorio a ser contribuido>
```

```shell

$ git clone + URL do repositório

```

##ADCIONAR MUDANÇAS COM VARIOS ARQUIVOS

```shell

$ git add . ```Comando para preparar vários arquivos para serem comitados```

```



##PULL

```shell

$ git pull ```Baixa copia de um arquivo para ser avaliado e ajustar as mudanças para posteriormente lançar no rapositório```

```


##PULL

```shell

$ git rebase --continue ```Cria uma especie de MERGE```

##CHECKOUT REMOTO

```

$ git checkout -t origin/branchName . ```Busca do repositório amarrando com a branch local```


```


auhauhauahuhauahuuahuhaua
haheuaehuaheuaheuahueahueha
Solrac





## Repositório contendo scripts de estudo GO

Repositório com os códigos para estudo da linguagem GO
 
 - [Go lang brasil](http://www.golangbr.org)

# Teste do projeto

Para testar o projeto você precisa configurar a variável de ambiente GOPATH

```
mkdir $HOME/go
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
``` 

# Instalção do projeto

Para instalar o projeto Olá mundo você precisa executar:

```
cd $GOPATH/src/github.com/michaeldouglas/ola
go install
```

# Teste do programa

Para realizar o teste do programa então você precisa executar o comando:

```
ola
```
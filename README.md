# Golang

## 1

* Uma pasta go deve ser criada dentro da pasta do usuário no linux
* Dentro dessa pasta go devem ser criadas as pastas bin, pkg, src
* Dentro da pasta sorce crie outra pasta para seu programa, por exemplo, a pasta hello e dentro dela o arquivo hello.go
    * Sim crie as pastas vazias e depois de compilar voce vai ver que as pastas serão usadas automaticamente pela linguagem
```
pasta-do-usuario/
└── go
    ├── bin
    ├── pkg
    └── src
        └── hello
           └── hello.go
```

```
go run hello.go    // compila e roda
go build hello.go  // compila
./hello            // executa arquivo binário

```

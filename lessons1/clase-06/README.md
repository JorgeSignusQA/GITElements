# Clase 06 - Git Desarollo Colaborativo

## Git alias
Comandos que me permiten usar  agile y rapidamente comandos mas largos de git

### Crear un alias en git


```sh
git config --global alias.l "log --oneline"
git config --global alias.ll "log --oneline --decorate -all --graph"

git config --global alias.c "commit -m" # git c "mensaje"
git config --global alias.s "status --short" # gits | git


````

### Eliminar un alias

```sh
git config --global --unset alias.<nombre-alias>
git config --global --unset alias.s
```

## Ver specificamentelos alieas que tengo

```sh
git config --global --get-repexp alias
```


### Distintos ambitos en GIT(scopes)

1.- --system alto -> a todo el sostema operativo usuarios y repo
2.- --global -> aplica a todos los repos del usuario actual
3.- --local  bajo ->Al repo especifico en el que estoy trabajando.


````sh
git config --<scope>
git config --system
git config --global
git config --local
```


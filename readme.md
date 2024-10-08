# GIT RAMAS (BRANCHES)

## Crear un repositorio

    ``` sh
    git init
    ```

## ver el estado de los archivos

``` sh
git  status
```

## GIT alias

```sh
git config --global alias.st "status --short"
git config --global alias.a "add"
git config --global alias.c "commit -m"
git config --global alias..l "log --oneline
```

## ver las diferencias entre el WD y LR

```sh
git show (numero-hash)
```

## crear una rama

```sh
git branch (nombre-rama) # crea una rama y nos deja en la rama actual
git switch -c (nombre-rama) # crea una rama y nos mueve a la rama que se creo
```

## me muevo entre ramas

```sh
git switch (nombre-ramas)
git switch (feature/ramas) #ejemplo
```

# Got
Alternativa a git clone, sin necesidad de tener instalado git

## Requisitos
Linux basado en debian 

Ser usuario root

## Instalacion

```bash
cd /usr/bin && wget https://raw.githubusercontent.com/zsh4k/got/main/got && chmod +x got && cd
```

## Verificar instalacion

```bash
got
```
output:

ERROR: No se ha proporcionado un directorio para descargar el repo.

Al ver esto ya tenemos Got instalado 

## Ejemplo de Uso

```bash
got https://github.com/git/git
```

Asi bajamos git desde github sin tener git 
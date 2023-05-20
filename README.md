# Got
Alternativa a git clone, sin necesidad de tener instalado git

## Requisitos
Linux basado en debian 

Ser usuario root

## Instalacion
Copia el siguiente codigo en tu terminal y tendras got instalado
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

## Desinstalar got
No tengo idea de por que querrias desinstalar esta maravilla pero aun asi...

```bash
rm -rf /usr/bin/got
```

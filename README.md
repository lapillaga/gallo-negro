# El Gallo Negro Principal Repository

## Descripción
Stack tecnologico el gallo negro

## Organización del repositorio
### - Aplicación móvil [gallon-app](https://github.com/lapillaga/gallon-app)
### - Backend [gallon](https://github.com/lapillaga/gallon)
### - Admin [gallon-admin](https://github.com/lapillaga/gallon-admin)
### - SPA [gallon-frontend](https://github.com/lapillaga/gallon-frontend)
### - Landing Page [gallon-landing](https://github.com/lapillaga/gallon-landing)
### - Proxy Traefik [gallon-traefik](https://github.com/lapillaga/gallon-traefik)

## Pasos para descargar el repositorio
1. Crear una llave ssh en la máquina de desarrollo y conectar con github (Recomendado).
2. Descargar el repositorio usando ssh o https. 
```
git clone --recursive git@github.com:lapillaga/gallo-negro.git
git clone --recursive https://github.com/lapillaga/gallo-negro.git
```
> Si no pueden acceder a uno de estos, es porque aún no son colaboradores.
---
Otra forma de descargar el proyecto cuando no se ha ingresado --recursive es ingresar
al repositorio principal y escribir los siguientes comandos
```
cd/NOMBRE_SUBREPOSITORIO
git submodule init
git submodule update 
```
## Manejo de commits
### Mensajes
- IMP: Descripción de la implementacion que se esta iniciando
- FIX: Descripción de la corrección de un error
- ADD: Descripción con la nueva funcionalidad que se esta implementando
- TEMP: Descripción de los cambios que no son estables
- WIP: Descripción del trabajo en proceso
- DEL: Descripción con lo que se quitó
- REVERT: Regresar a un commit anterior
### Ramas 
autor_feature_##########
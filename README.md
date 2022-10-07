# CursoDeWebpack
Desarrollo del curso de Webpack

## Instalación de Webpack

Para esto corremos en la terminal el siguiente comando, que instalara
las dependencias de webpack y webpack-cli para trabajar con comandos
desde la terminal como dependencias de desarrollo.

```npm
npm install webpack webpack-cli -D
```

Como no las instalamos de manera global, usamos npx para poder usarlo
como un comando, esto preparará el proyecto.

```npm
npx webpack
```

Podemos cambiar entre modos con el siguiente comando, recordemos los modos

- development (Añade particularidades para debug entre otras.)
- production
- (penidente)

```npm
npx webpack --mode nameMode
```

Para efectos practicos creamos una función suma que podemos
importar, al cambiar entre modos veremos que una de las cosas
que hace Webpack es optimizar nuestro codigo, cambiando cosas que 
pueden no ser muy necesarias.

## Continuación

Para ver la continuación de este repo revisar [js-portfolio](https://github.com/dan33pro/Webpack-portafolio-JS)
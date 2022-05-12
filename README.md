# Creación de una app

1. Crea una aplicación de react en el directorio en curso:

Ejemplo:

```bash
npx create-react-app . my-app --template typescript
```

Donde:

- npx create-react-app: nos ayuda a crear la app
- .: Especifica que se creará en el directorio en curso
- my-app: es el nombre de la aplicación
- --template: nos dice qué vamos a utilizar un template
- typescript: es el tamplate que se utilizará

> Boilerplate => App base con dependencias ya instaladas

Comando para crear la app:

```
npx create-react-app . cra-market-webapp --template typescript
```

# Dependencias iniciales

1. [] SASS: Theme (colores, tipos de letra, variables)
2. [] Autenticación/Sesión: Middleware, Local Storage, JWT, Redux
3. [] Form: ¿qué librería?
4. [] Validaciones de formulario: ¿qué librería?
5. [] Botones = UI: librería para UI
6. [] Inputs = UI: librería para UI
7. [] Select = UI: librería para UI
8. [] Checkbox = UI: librería para UI
9. [] Navegación: Router y Rutas protegidas

## Traducción de dependencias a librerías

1. [SASS](https://create-react-app.dev/docs/adding-a-sass-stylesheet/)
2. [Redux](https://react-redux.js.org/introduction/getting-started)
3. [React Hook Form](https://react-hook-form.com/)
4. [Yup](https://www.npmjs.com/package/yup)
5. [Mantine](https://mantine.dev/)
6. [React Router](https://reactrouter.com/)

## Theme

Es necesario iniciar una app con un theme ya definido. Con theme me refiero colores, tipografía, espaciados (opcional), tamaños de letra, todo lo que tenga que ver con lo visual y que SASS/UI nos pueda ayudar

# vue-lifecycle

## Lifecycle

Etapas por las que pasa una instancia de Vue de inicio a fin (destruccion)

```sh
beforeCreate(): //Se ejecuta antes de que se inicie la instancia.
```
```sh
created(): //La instancia ha sido creada. Aquí se pueden acceder a datos observables y eventos.
```
```sh
beforeMount(): //Se llama justo antes de que la instancia se monte en el DOM.
```
```sh
mounted(): //La instancia se ha montado en el DOM. Aquí es seguro acceder al DOM.
```
```sh
beforeUpdate(): //Se llama antes de que los datos de la instancia se actualicen.
```
```sh
updated(): //Se llama después de que los datos de la instancia se han actualizado.
```
```sh
beforeDestroy(): //Se llama justo antes de que la instancia sea destruida.
```
```sh
destroyed(): //La instancia ha sido destruida y todos los eventos y observadores han sido eliminados.
```
## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

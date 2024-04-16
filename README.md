# vue-lifecycle

## Lifecycle

Etapas por las que pasa una instancia de Vue de inicio a fin (destruccion)
Ciclo de vida documentacion oficial Vue.JS
https://vuejs.org/assets/lifecycle.MuZLBFAS.png

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
Ejemplo agregando los Hooks
![image](https://github.com/fredinfu/vue-lifecycle-hooks/assets/23424560/abc74a65-a609-4818-aae3-cdac86251733)

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

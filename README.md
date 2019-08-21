# Estrutura e breve explicação do framework Vue 

Aqui estão diversas estruturas usando o Framework Vue, também tem uma breve explicação do uso do Framework 

## (Detalhe Importante um)
No Layout do Vue é necessário ter essa estrutura:

```html
<template>
  aqui vai html dos componentes 
</template>

<script>
//aqui vai scripts
</script>

<style>
/*aqui vai estilo*/
</style>
```
## (Detalhe importante dois)

Para que tenha vários componentes na tag template é necessário colocar uma div como o exemplo abaixo:

```html
<template>
 <div>
  <h1>Uma lista</h1>
  <ul>
    <li><a href="">Link</a></li>
  <ul>
 </div>
</template>

<script>
//aqui vai scripts
</script>
<style>
/*aqui vai estilo*/
</style>
```
## (Detalhe importante três)

Para que seu CSS possa ficar isolado em um determinado componente do Vue é necessário adicionar: (scoped), dessa forma o estilo irá ficar somente no determinado componente 

```html
<template>
 <div class="componente_azul">
  <h1>Uma lista</h1>
  <ul>
    <li><a href="">Link</a></li>
  <ul>
 </div>
</template>

<script>
//aqui vai scripts
</script>
<style scoped>
.componente_azul{
    background-color: blue;
}
</style>
```

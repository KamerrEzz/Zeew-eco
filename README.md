![Zeew Api](https://i.imgur.com/MP2bABn.png "Lo Mejor de Zeew y del C&P")

# Zeew Eco!

  - Economía Fácil y sencilla
  - Tienda Fácil sin limite


Crea Una economía fácil y sencilla de usar para tu bot.

> Muchos se complican demasiado para hacer una economía fácil
> ¿Por qué no ayudarles un poco?

## Informacion

* **Constructores**
  * [Economía](#economia)
  * [Tienda](#Tienda)
  * [Trabajos](#Trabajos)
* **Estructura json**
  * [Economía](#json-eco)
  * [Tienda](#json-td)
* **Zeew**
  * [Staff](#Staff)
  * [Proyectos](#Proyectos)

 
No olvides que si tienes un error o propuestas para mejorar este NPM
Solo tienes que unirte a este servidor de [discord]( https://discord.gg/HWwBD6F).

Gracias por Escoger este NPM
## instalación

```js
npm i zeew-eco
```

### Economia

```js
const zeco = require('zeew-eco')
const eco = new zeco.economia()
```

| Métodos | Descripción |
| ------ | ------ |
| [mostrar](#Eco-mostrar) | Muestra el dinero del usuario
| [agregar](#Eco-Agregar) | Agrega dinero aun usuario|
| [quitar](#Eco-quitar) | Elimina el dinero de un usuario|
| [comprar](#Eco-comprar) | Comprar En la tienda|

#### Eco-mostrar
```js
eco.mostrar(clave)
```
* clave - ID del servidor
```js
const eco = new zeco.economia()
eco.mostrar(message.guild.id)
```
```js
```
#### Eco-Agregar
```js
eco.agregar(clave, id, cantidad)
```
* clave - ID del servidor
* id - ID del usuario
* cantidad - Dinero que quieras agregarle

```js
const eco = new zeco.economia()
eco.agregar(message.guild.id, miembro.id, 1500)
```
```js
```
#### Eco-quitar
```js
eco.quitar(clave, id, cantidad)
```
* clave -ID del servidor
* id - ID del usuario
* cantidad - Dinero que quieras agregarle
```js
const eco = new zeco.economia()
eco.quitar(message.guild.id, miembro.id, 1500)
```

```js
```
#### Eco-comprar

```js
ecocomprar(clave, id, item)
```
* clave - ID del servidor
* id - ID del usuario
* item - numero de item
```js
const eco = new zeco.economia()
eco.comrar(message.guild.id, miembro.id, 1)
```
```js
```
### Tienda

```js
const zeco = require('zeew-eco')
const td = new zeco.tienda()
```

| Metodos | Descripcion |
| ------ | ------ |
| [agregar](#TD-agregar) | Agrega Items a la tienda|
| [agregar](#TD-agregar) | Agrega Items a la tienda|
| [quitar](#TD-quitar) | Quita Items de la tienda|


#### TD-mostrar
```js
eco.mostrar(clave)
```
* clave - ID del servidor
```js
const eco = new zeco.economia()
eco.mostrar(message.guild.id)
```
```js
```
#### TD-agregar
```js
eco.agregar(clave, nombre, desc, precio)
```
* clave - ID del servidor
* nombre - Nombre del Item
* desc - La descripcion del item
* precio - el precio del item
```js
const td = new zeco.tienda()
eco.agregar(message.guild.id, "Canal Propio", "Con esto podrás obtener un canal privado para ti", 20000)
```
```js
```
#### TD-quitar
```js
eco.eliminar(clave, id)
```
* clave -ID del servidor
* id - Numero del Item de la tienda
```js
const eco = new zeco.tienda()
eco.quitar(message.guild.id, 1)
```
el numero del ítem aumento dependiendo cuantos tengas
```json
{
  "nombre": {
   "item1": "Articulo 1",
   "item2": "Articulo 1",
   "item3": "Articulo 1"
}
```
```js
```
### JSON
#### json-eco
```json
{
 "ID-servidor": {
  "nombre": {
   "item1": "articulo 1",
  },
  "descripcion": {
   "item1": "Descripcion 1"
  },
  "precio": {
   "item1": 1500
  }
 }
}
```
```
```
#### json-td
```json
{
 "ID-servidor": {
  "ID-usuario": {
   "dinero": 3100
  }
 }
}
```
```
```
---
## Zeew
#### Staff
 * @KamerrOficial
  ```
    * ROL: Owner
    * ID Discord: 403695999941345280
    * Clan: ZeaterNight
    * Redes Sociales: @KamerrOficial
    * Portafolio: behance.net/kamerroficial
  ```
 * @ValerynR  
```
  * ROL: Co-Owner
  * ID Discord: 393603334847856650
```
#### Proyectos

| proyecto | descripcion |
| --- | --- |
| Zeew | Descubre nuestra API Reset de Imágenes y manipulación
#### Donaciones
* [Kamerr Ko-fi](https://ko-fi.com/kamerroficial)
Las Donaciones las uso crear más proyectos y mejorar la calidad,
cierta cantidad está totalmente para **zeew** para su único uso.

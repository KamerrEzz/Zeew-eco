![Zeew Api](https://i.imgur.com/MP2bABn.png "Lo Mejor de Zeew y del C&P")

# Zeew Eco!

  - Economía Fácil y sencilla
  - Tienda Fácil sin limite


Crea Una economía fácil y sencilla de usar para tu bot.

> Muchos se complican demasiado hacer algo como esto,
> ¿Por qué no ayudarles un poco?.

## Informacion

* **Constructores**
  * [Economía](#economia)
  * [Tienda](#tienda)
  * [Trabajos](#trabajos)
* **Estructura json**
  * [Economía](#json-eco)
  * [Tienda](#json-td)
* **Zeew**
  * [Staff](#staff)
  * [Proyectos](#proyectos)

 
No olvides que si tienes un error o propuestas para mejorar este NPM
Solo tienes que unirte a este servidor de [discord]( https://discord.gg/HWwBD6F).

Gracias por Escoger este NPM
## instalación

```js
npm i zeew-eco
```
<a name="economia" />

### Economia

```js
const zeco = require('zeew-eco')
const eco = new zeco.economia()
```

| Métodos | Descripción |
| ------ | ------ |
| [mostrar](#Eco-mostrar) | Muestra el dinero del usuario
| [agregar](#Eco-agregar) | Agrega dinero aun usuario|
| [quitar](#Eco-quitar) | Elimina el dinero de un usuario|
| [comprar](#Eco-comprar) | Comprar En la tienda|

<a name="Eco-mostrar" />

#### Economia: Comprar

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
<a name="Eco-agregar" />

#### Economia: Agregar

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
<a name="Eco-quitar" />

#### Economia: Quitar

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

<a name="Eco-comprar" />

#### Economia: Comprar

```js
eco.comprar(clave, id, item)
```
* clave - ID del servidor
* id - ID del usuario
* item - numero de item / ID
```js
const eco = new zeco.economia()
eco.comprar(message.guild.id, miembro.id, 1)
```
```js
```
<a name="tienda" />

### Tienda

```js
const zeco = require('zeew-eco')
const td = new zeco.tienda()
```

| Metodos | Descripcion |
| ------ | ------ |
| [Mostrar](#TD-mostrar) | Muestra Items a la tienda|
| [Agregar](#TD-agregar) | Agrega Items a la tienda|
| [Eliminar](#TD-quitar) | Elimina Items de la tienda|

<a name="TD-mostrar" />

#### Tienda: Mostrar

```js
eco.mostrar(clave)
```
* clave - ID del servidor
```js
const td = new zeco.tienda()
eco.mostrar(message.guild.id)
```
```js
```
<a name="TD-agregar" />

#### Tienda: Agregar

```js
eco.agregar(clave, nombre, desc, precio)
```
* clave - ID del servidor
* nombre - Nombre del Item
* desc - La descripcion del item
* precio - el precio del item
```js
const td = new zeco.tienda()
td.agregar(message.guild.id, "Canal Propio", "Con esto podrás obtener un canal privado para ti", 20000)
```
```js
```
<a name="TD-quitar" />

#### Tienda: Eliminar

```js
td.eliminar(clave, id)
```
* clave -ID del servidor
* id - Numero del Item de la tienda
```js
const td = new zeco.tienda()
td.eliminar(message.guild.id, 1)
```
```js
```
### JSON

<a name="json-eco" />

#### json: Economia

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
<a name="json-td" />

#### json: Tienda

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

<a name="staff" />

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
<a name="proyectos" />

#### Proyectos

| proyecto | descripcion |
| --- | --- |
| [Zeew](https://www.npmjs.com/package/zeew) | Descubre nuestra API Reset de Imágenes y manipulación
#### Donaciones
* [Kamerr Ko-fi](https://ko-fi.com/kamerroficial)
Las Donaciones las uso crear más proyectos y mejorar la calidad,
cierta cantidad está totalmente para **zeew** para su único uso.

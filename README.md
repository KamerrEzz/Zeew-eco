# Zeew-Eco


![Zeew Api](https://i.imgur.com/MP2bABn.png "Título alternativo")

# Zeew Eco!

  - Economia Facil y cencilla
  - Tienda Facil sin limite


Crea Una economia facil y cencilla de usar para tu bot.

> Muchos se complican demaciado para hacer una economia facil
> ¿Por que no ayudarles un poco?

## Contructores

A qui te presento los contructores para iniciar esta economia.

* [Economia](#economia)
* [Tienda](#Tienda)
* [Trabajos](#Trabajos)

No Olvides que si tienes algun error o propuesta para mejorar este NPM, solo tienes que unirte a nuestro servidor de [discord]( https://discord.gg/HWwBD6F).

## instalación

```js
npm i zeew-eco
```

### Economia

```js
const zeco = require('zeew-eco')
const eco = new zeco.economia()
```

| Metodos | Descripcion |
| ------ | ------ |
| [agregar](#Eco-Agregar) | Agrega dinero aun usuario|
| [quitar](#Eco-quitar) | Elimina el dinero de un usuario|
| [comprar](#Eco-comprar) | Comprar En la tienda|

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
| [quitar](#TD-quitar) | Quita Items de la tienda|
* [JSON](#Json)

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
eco.agregar(message.guild.id, "Canal Propio", "Con esto podras optener un canal privado para ti", 20000)
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
el numero del item aumento dependiendo cuantos tengas
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
#### JSON
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
---
## Creador NPM:
  ### @KamerrOficial
  
  ```
    * ROL: Owner
    * ID Discord: 403695999941345280
    * Clan: ZeaterNight
    * Redes Sociales: @KamerrOficial
    * Portafolio: behance.net/kamerroficial
  ```
## Zeew Staff
 ### @ValerynR  
 
```
  * ROL: Co-Owner
  * ID Discord: 393603334847856650
```

#### Donaciones


* [Kamerr Ko-fi](https://ko-fi.com/kamerroficial)

![Zeew Api](https://i.imgur.com/MP2bABn.png "Lo Mejor de Zeew y del C&P")

# Zeew Economia!


Ahora te enseñare las respuesta y como podrias personalizarlas

> Con Mucha Creatividad puedes hacer mensajes personalizados
> **Nota:** Algunas respuetas no se pueden personalizar



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
eco.comprar(clave, id, item)
```
* clave - ID del servidor
* id - ID del usuario
* item - numero de item
```js
const eco = new zeco.economia()
eco.coprar(message.guild.id, miembro.id, 1)
```
```js
```

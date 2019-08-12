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
**Esta Te Devuelve:**
• **Si el usuario no tiene dinero**
`"No tienes dinero"`
• **Si el Usuario tiene dinero**
Si el usuario tiene 1500, esta regresa los `1500`
```js
let dinero = new zeco.mostrar(message.guild.id, usuario.id)
message.channel.send("tu Dinero es " + dinero)
```
> con mas creatividad puedes hacerlo mejor
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
**Esta Te Devuelve:**
• **Mensaje de agregar**
Esta regresa el dinero actual del usuario
ejemplo 1: el usuario no tiene dinero y le agregar 500, esta regresa `500`
ejemplo 2: si el usuario tiene 500 y le agregas 500 , esta regresa `1000`

```js
let dinero = 1500
let agregar = new zeco.agregar(servidor.id, usuario.id)
message.channel.send("Se te agrego "+ dinero + ", Ahora tienes: " + agregar)
```
> con mas creatividad puedes hacerlo mejor

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

**Esta Te Devuelve:**
• **Si el Usuario no existe en la db:** 
`"No tienes dinero"`
• **Si el usuario tiene cero de dinero:** 
`"Tu dinero es 0, no puedes quitarle mas."`
• **Mensaje de quitar**
 El dinero actual del usuario, si el usuario tiene 1500 de dinero
 y le quitas 500, esta regresara el dinero actual del usuario `1000`
 ```js
let dinero = 1500
let agregar = new zeco.agregar(servidor.id, usuario.id)
if(agregar == "No tienes dinero") {
message.channel.send("Eres muy pobre no te puedo quitar dinero que no tienes")
}
if(agregar == "Tu dinero es 0, no puedes quitarle mas."){
    message.channel.send("Ya Te quitaron todo el dinero que tenias")
}
message.channel.send("Se te quito "+ dinero + ", Ahora tienes: " + agregar)
```

> con mas creatividad puedes hacerlo mejor
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
eco.comprar(message.guild.id, miembro.id, 1)
```
_**Esta Te Devuelve:**_

• **Si no hay tienda en el servidor:** 

`"No hay Una Tienda en el servidor"`

• **Si el dinero del usuario es menor al precio del item:**

`"No Tienes el dinero suficiente"`

• **Si El Item no existe**

`"No Existe Ese Item En la tienda"`

• **Mensaje de compra**

`"Compra Realizada:`

`Item: articulo1`

`Descripcion: descripcion 1`

`Precion: 1500"`

> `Esto no es muy personalizable`


> para que entiendas el mensaje que regresa, te muestro el db de la tienda, lo unico que revuelve la informacion del item comprado

> el numero del item es el `item#` si compras el item 2, seria `item2`
```json
{
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
```
```js
```

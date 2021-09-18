VARIABLES: es una forma de almacenar el valor de algo para poder usarlo mas tarde.

Pensemos en una caja de calzado: en ésta puedo guardar calzado de cualquier marca, de cualquier estilo (pueden ser borcegos, zapatillas deportivas, zapatos de etiqueta, pantuflas, chancletas, etc) 

Para utilizar una variable debemos crearla, ponerle un nombre y asignarle un valor. En JavaScript esto se denomina "declarar una variable". Existen varias formas de hacer esto. 

Si la caja -variable- puede guardar solo un par de calzado determinado como zapatillas Adidas, se considera una constante. Una vez que ingresan las zapatillas Adidas, solo contendrá esas zapatillas.

const caja-calzado = zapatillas-adidas;

En cambio, podemos tener una caja que puede guardar cualquier clase de calzado, según lo que queramos guardar. 

var caja-calzado2 = cualquier-zapatilla;

STRINGS

Son tipos de datos que pueden ir en las cajas de variables. Éstos son cadenas o bloques de texto que se escribe entre comillas dobles o simples.

Un ejemplo sería:
var nombre = "tu nombre";

FUNCIONES
Ahora pensemos que tenemos muchas cajas de calzado y queremos saber cuántos pares tenemos, las funciones nos ayudan a saber esto.
Las funciones son "Objetos invocables", es decir, podemos definir una función y llamarla (invocarla) para que haga lo que se supone que debe hacer; en este caso, calcular cuanto calzado tenemos.

Para escribir una función debemos usar la palabra clave "function":

function nombre-de-mi-funcion () {
         lo que quiero que haga la función
         return ()     }

Para nuestro ejemplo hacemos:
function cantidad-de-pares() {
         var cant-par-nike = 2;
         var cant-par-adidas = 2;
         var cant-par-pantuflas = 1;
         return suma = cant-par-nike + cant-par-adidas +cant-par-pantuflas}

Importante, si queremos que la funcion nos devuelva un resultado, debemos usar return.

A las funciones le podemos pasar datos que se llaman argumentos.

Si analizamos la función cantidad-de-pares, dentro de la función, en su cuerpo definimos de ante mano los valores de las variables. Pero si nos equivocamos y en vez de 2 pares de Nike eran 3? O 1?
Para evitar esto, hacemos así:


function cantidad-de-pares(cant-par-nike, cant-par-adidas, cant-par-pantuflas) {
         return suma = cant-par-nike + cant-par-adidas +cant-par-pantuflas; }
         
Ahora, podemos pasarle a la funcion los valores que querramos.

function cantidad-de-pares (3, 2, 1)
Y la función nos devolverá que tenemos 6 pares.

DECLARACIONES if

if es una estructura de control de flujo, es decir, lo usamos para tomar desiciones. Cuando evaluamos una condición, ésta tomará un solo valor de verdad. La condición es verdadera o es falsa.
Por ejemplo, queremos saber si tenemos más de 3 pares de zapatillas Adidas:

function masDe3? (cant-par-adidas){
	if (cant-par-adidas >= 3) {
	return true;}
	return false;
	} 
         
VALORES BOOLEANOS

Son valores que devuelven verdadero (true) o falso (false).
         
         

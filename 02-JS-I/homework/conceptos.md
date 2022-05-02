
## Conceptos JavaScript I

1. variables 

    * Una variable es como un almacen para que tu puedas guardar un valor. Como numerico, texto, o algun resultado de una operacion que necesitaras mas adelante. En pocas palabras es una caja para que guardes un solo valor.

2. Strings

    * Una String es una cadena de caracteres que son destacados en JavaScript por estas comillas ('', ""). Al ser leido por JavaScript, lo interpretara como un texto comun y corriente. Por ejemplo tu nombre y tu cumpleaños; "Chayanne Emilio que tiene 53 años". O otro tipos de caracteres; "2 + 2 = 5", "O Algo muy especifico que tu decidas colocar aqui". 
    Va ser un texto simpre en cuando este dentro de las comillas "", ''.

3. Funciones (argumentos, return)

    * La function es para asignar procedimientos en tu codigo, y poder organizar el procedimiento como tu quieras quieres. Pero para esto tienes que recibir un argumento y darle un valor o una condicion que tu desees que suceda dentro de la function, para al final poder retornar tu nuevo argumento. 

         function nombreDeTuFunction (argumentoQueRecibes) {

             //dentro de esta seccion vas a poder colocar todo los parametros que desees que hagan tu function.
             var ArgumentoQueRecibes = 'procedimientoDeAlgo' + 'queTuQuieras' + 'QueSuceda' + 'conElArgumento' + 'queRecibes';

             //aqui debes devolver los parametros y se termine el proceso de tu function
             return ArgumentoQueRecibes;
         };

         nombreDeTuFunction (elArgumentoQueQuieras);

    al final debes hacer llamado a tu function para que se pueda ejecutar tu codigo creado dentro la fucntion. Y sea vicible tu nuevo valor.

4. Declaraciones (`if`)  

    * Las declaraciones funcionan para dar a conocer desde donde va comenzar existir esa variable: 

         var                       Chayanne                   =              'es cantante favorito de las mamas'
       variable          la declaracion de la variable        =                    valor de tu declaracion     

    * Las declaraciones en `if` es para poder dar una condicion, si se llega ejecutar algo de acuerdo a la condicion que habiamos declaramos se pueda acceder al codigo y se ejecute. Es como si se ramificara el codigo de acuerdo a lo que llegue a suceder, por ejemplo:

     if (si llueve me ajecutas esta condicion){
         alert('deberias abrir el paraguas y si no te vas a mojar');
     }else if (si no llueve ejecuatame este codigo){
         alert('se salvo de andar oliendo a perro todo el dia por que no llovio'); 
     }

     si en la condicion se recibe un true se ejecutara el codigo. O si no seguira con la siguiente condicion hasta que encuentre un true o se termine el codigo o sea sacado 

5. Valores Booleanos (`true`, `false`) 

    * Los valores Booleanos son una expresion de si es es verdadero y falso. Son operadores logicos que son utilizados para confirmar. Ejemplo en la vida cuando un asesino va jucio intentan comprobar si es culpable (true) o no es culpable (false). Y si no es ninguna de las dos, sabra dios por que termino en juicio de ese estilo, te retornara algo que no esta definido (undifine).
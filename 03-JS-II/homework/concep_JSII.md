# conceptos JavaScript II

1. ciclo `for`

    * El ciclo for se emplea para leer un mismo codigo una catidad de veces predeterminada. Imagenemos una noria, tu pagas una cantidad de dinero para que te puedas subir y te den cierta cantidad de vueltas en un mismo punto, mientras aprecias el paisaje. El ciclo for funciona casi igual, asignas un numero de veces que desees dar vueltas en el codigo. ejemplo:

        el punto de partida de donde va empezar a dar vueltas la noria ;      el numero de vueltas que va dar la noria;       cada vez que de una vuelta le vas a sumar 1 vuelta dada
    for (                     var i = 0;                                                         i < 8;                                            i++){
        alert('que hermoso paisaje');
    }; 

    Entonces cada vez que des una vuelta este operador i++ (i + 1), le va sumar 1 a la variable i (var i = 0). Cuando se complete el numero de vueltas que establecimos (i < 8) en este caso. Se detendra el peseo en tu noria y tendras 8 veces la alerta que agregamos dentro de esta iteracion; "que hermoso paisaje".

2. Operadores logicos `&&`, `||`, `!`

    * Los operadores logicos son tablas de verdad que nos ayudan a determinar si es verdadero o falso, comparando estas dos expresiones. Es como si compararas un objetos con otro objeto como por ejemplo; si comparas un celular con un computador de mesa lo mas obvio es que no sean iguales y esto te retornara que es falso. Pero si nosotros queremos pensar de una forma mas generalisada; Los dos son electronicos y necesitan energia para funcionar, serian lo mismo y esto te retornaria que es verdadero. Entonces los operadores logicos tiene varias formas para que tu puedas manipular esa verdad que va retornar cuando comparas, si tu resultado puede ser falso o verdadero o invertir los valores al contrario.

    * El operador logico `&&` (AND) el te ayuda a comparar las verdades y segun su tabla te retorna un valor entre falso y verdad. Con su parametro, si ambas expresiones son verdaderas (true) te retorna que es verdad; de lo contrario si alguna expresion contiene que es falso (false) siempre sera falso al retornar:

        * True  && True  = True                                 
        * True  && False = False 
        * False && True  = False
        * False && False = False 

    * El operador logico `||` (OR) este operador es lo contrario al operador `&&` (AND). Con su parametro, si ambas expresiones son falsas (false) te retornara que es falso; de lo contrario si alguna contiene que es verdadero (true) siempre sera verdad al retornar: 

        * True  || True  = True 
        * True  || False = True 
        * False || True  = True 
        * False || False = False 
    
    * El operador logico `!` (NOT) este operador es muy particular por que voltea los dos operadore logicos anteriores (`&&`, `||`) por que es una negacion de los valores. Lo que hace es negar el valor recibido, si el operando es verdadero (true) su valor en negacion es falso (false) `true != false`. Y asi mismo en su contrario, si el operando es falso (false) su valor enn negacion es verdadero (true).

        * True != False 
        * False != True 

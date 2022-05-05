
## conceptos JS III

1. Arrays 
 
    * imaginemos que los Arrays son como una carcel, cuando entra un nuevo pricionero o en super villano, le vas a tener que asignar un numero para que tu los puedas identificar y saber donde esta ubicado este pricionero:

        var superVillanos = ["loki", "Elguason", "Octopus", "Tanos"];
                      key =    0          1           2        3

    Entonces cada villano de pelicula esta en su celda y ya tiene su numero, pero cuando debes sacarlo de su celda para interrogarlo debes saber cual pricionero es y en que pabellon esta este prisonero. En este caso esta encerrado en el pabellon de superVillanos y es el prisionero numero 1. Ten encuenta que los prisioneros siempre van estar enumerados desde el numero `0`:

        superVillanos[1] //return: "Elguason"

    Lo que va hacer es buscar en el pabellon de super villanos y va sacar al prisionero numero `1`, para que puedas interrogarlo. Pero recuerda la ruta que tienes que hacer para poder llegar a este prisionero y que siempre van a estar enumerados desde el numero `0`

    * JavaScript es algo magico con los Arrays, ya que JavaScript no tiene tantas reglas para el manejo de sus datos. Los Arrays tienen la libertad de poder almacenar todo tipo de datos ya sea "string", `numerico`, variables, funciones, Booleanos y hasta no tendria problema en almacenar otros arrays en un mismo array. Es como si guardaras una caja dentro de otra caja. 

        Los Arrays ya que guardan todo tipo de datos que desees, puede ser confuso el manejode sus datos a las hora que desees eliminar o agregar otros elemetos, por eso uno tiene que saber controlar sus datos. Y los Arrays tienen palabras claves para que tu puedas obtener informacion y tengas un mayor control a la hora de borrar o agregar elementos dentro de tu carcel; Existen palabras como ".push", ".pop", ".unshift", ".shift" y muchas otras acciones con las cuales puedes modificar, cambiar o trasladar.

2. Palabras claves para los arrays 

    * .push - Esta palabra clave te servira cuando quieras agregar un super villano a tu lista, pero este te lo agregara al final de tu lista de super villanos. 

        var superVillanos = ["loki", "Elguason", "Octopus", "Tano"];

    entoces cuando quieras agregar otro supuesto super villano a tu lista deberas usar el nombre de la lista y el .push("") para que lo puedas agregar

        superVillanos.push("la señora que no le quiso pagar la pizza a spiderman");

    lo que hara el .push("") sera agregarlo, pero sera en lo ultimo de tu lista de super villanos.

    * .pop - Esta palabra clave lo que hara, sera eliminar de tu lista al ultimo elemento que agregaste. Que en este caso fue la señora de la pizza de Spiderman. Y lo que debes hacer es usar el nombre de la lista de super villanos y eliminar a la super villana usando .pop para que sea elimanada de tu lista:

        var superVillanos = ["loki", "Elguason", "Octopus", "la señora que no le quiso pagar la pizza a spiderman"];

        superVillanos.pop(); //en este no le agregas argumento por que .pop lo que siempre va hacer es iliminar al ultimo de tu lista que esta en tu caja.

   quedaria tal como:

        var superVillanos = ["loki", "Elguason", "Octopus"]; 

    Estas dos palabras claves siempre tendran su uso, siempre encuando quieras agregar o eliminar a lo ultimo de la lista.

    * .unshift - .shift - estasdos palabras clave hacen exasctamente lo mismo que .push y .pop pero las acciones la haran al inicio de la lista.

    * .unshift - Esta palabra clave agregara otro super villano pero al inicio de tu lista, ya que crees que es el mas peligroso. Es igual a .push pero al inicio de la lista pero al inicio de la lista funcionara .unshift 

        var superVillanos = ["loki", "Elguason", "Octopus"]; // asi quedo nuestra lista la ultima vez que eliminamos a la señora de la pizza 

        superVillanos.unshift("Tanos"); // de esta forma agregas a "Tanos" de primeras por que crees que es el mas peligroso. 

    De esta forma agregas elementos al inicio de tu lista. Colocando el nombre de la lista mas .unshift y asi agregas elemenetos al inicio de tu lista.

    * .shift - Funciona igual que .pop pero este hara su trabajo eliminando al inicio de la lista.

        var superVillanos = ["Tanos", "loki", "Elguason", "Octopus"] // asi quedo la ultima vez que agregamos a "Tanos" al inicio de la lista.
    
        superVillanos.shift(); // asi podremos eliminar a "Tanos" de lista 

    con .shift podras eliminar el primer elemento de tu lista y no habra retorno de lo que ya eliminaste 

        var superVillanos = ["loki", "Elguason", "Octopus"];




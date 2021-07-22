# ¿Qué es JavaScript?
    Es un lenguaje interpretado, multiparadigma, débilmente tipadoy dinámico.

# Multipiparadigma
   * Programación interpretativa: SE escriben las instruccionespaso a paso para generar la solución del problema.

    *Programación fucional: Usando funcionesunidades hasta seguirel resultado esperado.

    * Programación orientada a objetos: Se usan objetos que encasulan variables y métodos, para inteteractuar con otros objetos, para obtenerel resultado correcto.

# Interpretado
    El navegador lee línea por línea el código el cuál indica lo que tiene que hacer, sin la necesidad de compilar


    let número;
 
    numero = 4 + "7";
    console.log(numero);

    numero = 4 * "7"; //28
    console.log(numero);
    numero = 2 + true; //3
    console.log(numero);
    numero = false - 3; //-3
    console.log(numero);

# Débilente tipado
    Se puede hacer operaciones entre tipos distintos de datos (enteros con strings, booleanos con enteros, etc,.) Example:

# Dinámico
    Corre directamente con la etapa de Rutime sin una etapa de compilación previa. Esto permite probar nuestro código inmediatamente; pero también es lo que hace que los errores se muestren hasta que se ejecute el programa.

# Datos primitivos
     Son datos que no son un objeto y no tienen métodos; son 6 datos de primitados.

    * Undefined: Variable que solo ha sido declarada.

    let numero;
    console.log(numero);

    * String: Secuencia de caracteres usado para representar el texto

    let nombre = "Mileidy";
    console.log(nombre);

    * Number: Es un tipo de datos númericos.

    let edad = 30;
    console.log(edad);

    * Booleano: Es un dato lógico que solo puede tener los valores true o false.

    let info = true;
    console.log(info);
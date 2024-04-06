Condicionales

Práctica Integradora

Objetivo
Al ingresar a una aplicación, el usuario podrá tomar diferentes rumbos dentro de ella
dependiendo de los datos.
Por ejemplo: cuando un usuario ingresa a un sitio web, se evalúa si está o no registrado y
en base a ello tendrá o no acceso a ciertos recursos que el sitio ofrece.
Otro ejemplo puede ser la diferencia entre aplicar a los productos un descuento o un
recargo.
Para poder tener control sobre la ejecución de nuestro programa existen las estructuras
condicionales. En el desarrollo de esta ejercitación las pondremos en práctica.

1

Recordemos cómo funcionan las estructuras
condicionales...

Pensemos, por ejemplo, si quisiéramos restringir según la mayoría de edad el acceso a un
tobogán de agua extremo. En ese caso, tendríamos que saber si la persona es mayor o
menor de edad. Esto lo podríamos resolver con una condición muy sencilla.

let edad= 20;
if(edad >= 18) {
console.log('Puede ingresar')
}else{
console.log('No puede ingresar')
}

¡Ahora pongamos esto en práctica!

2

Micro desafío 1:
Instrucciones
1. Crea una carpeta de trabajo y dentro de ella un archivo JavaScript (.js).
2. Desarrolla un programa que le indique al usuario - en base a su perfil o
responsabilidades - qué puede hacer o no en el sistema. Para eso debes crear una
variable llamada: “perfil” y asignarle alguno de estos valores:
a. administrador
b. asistente
c. invitado.
Es importante tener en cuenta que se debe mostrar un único mensaje, utilizando el
console.log():
A. Si se le asigna un espacio en blanco a la variable perfil, debe mostrar el
mensaje: “Debe especificar el perfil del usuario”.
B. Si es un perfil “administrador - ADMINISTRADOR - Administrador”, la
consola debe mostrar este mensaje: “Usted tiene todos los privilegios de
uso del sistema”.
C. Si es un perfil “asistente - ASISTENTE - Asistente”, la consola debe mostrar
este mensaje: “Usted sólo tiene permisos de registrar, modificar y
consultar datos”.
D. Si es un perfil “invitado - INVITADO - Invitado”, la consola debe mostrar este
mensaje: “Usted sólo tiene permisos de consultar datos”.
E. Si se especifica un valor diferente a la variable perfil entonces se debe mostrar
este mensaje: “Debe especificar un perfil válido”.

Una vez creado el programa, ejecutalo. ¿Recuerdas cómo?
Para probar las diferentes respuestas asigna diferentes valores a la variable “perfil” creada.

3

Micro desafío 2:

Instrucciones
1. En la carpeta ya creada crea un nuevo archivo JavaScript (.js).
2. Desarrolla el programa Ajuste tarifario de energía eléctrica. Utilizando el operador
condicional ternario, queremos determinar cuánto va a pagar un hogar según su
consumo. Veamos los pasos a seguir...
a. Crear una variable “pagoMes” y asignarle un pago actual de energía
eléctrica por mes.
b. Crear otra variable “consumoKWH” y asignarle un consumo mensual de
Kilovatios hora de consumo mensual por el hogar.
c. Si en el hogar se consumen más de 300 kwh por mes, entonces al pago actual
se le incrementará un 20%.
d. En el caso contrario se le mantendrá el subsidio, es decir que no tendrá ningún
aumento..

3. Una vez obtenido el monto del pago por consumo mostrar al usuario este mensaje:

“Debido a que su hogar tuvo un consumo de 450kwh, en base al ajuste tarifario
(hogares con consumo mayor a 300kwh por mes tendrán un aumento del 20%),
cumplimos con informarle que se ha ajustado el total a pagar, que será de $14400”

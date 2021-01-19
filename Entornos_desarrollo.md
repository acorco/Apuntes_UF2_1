# Entornos desarrollo

### OBJETIVOS DE LAS PRUEBAS

Los objetivos de las pruebas en definitiva son comprobar que nuestro programa hace exactamente  
lo que queríamos que hiciera desde un inicio, ni más ni menos. Para llevar a cabo estas pruebas usamos los denominados  
"frameworks".  

#### FRAMEWORK

"Framework", en español marco de trabajo se compone por las mejores prácticas, unas herramientas y unas bibliotecas.  
En definitiva es un esquema o patrón.


### PRUEBAS

#### FORMA DE LAS PRUEBAS

Hay dos formas de pruebas. Las pruebas dinámicas y las estáticas.  
En las **pruebas dinámicas** se necesita ejecutar la aplicación entera.  
Por contrapartida, las **pruebas estáticas** no necesitas la ejecución de la aplicación  
porque se examina directamente el código fuente.

#### ESTRATEGIA DE PRUEBA

Hay dos tipos de estrategias.  
La estrategia de **caja negra**. Como el nombre indica, es una caja negra metafórica  
así que no se analiza el código si no que se analiza el resultado que la aplicación da.  
En cambio, en la estrategia de **caja blanca**, se examina todo el código (eficiencia, estructura, etc)  
y también el resultado, lógicamente.

#### TIPOS DE PRUEBAS

Hay dos tipos de pruebas. Las funcionales y las no funcionales.  
En las **funcionales**, se evalua el cumplimiento de requisitos lo cuál significa es que no se evalua  
de qué forma se ha llegado al resultado sino el resultado.  
En cambio en las **no funcionales** se evalua el rendimiento, la seguridad, estructura, etc. Con lo cual,  
no sirve con que el resultado que de la aplicación esté bien sino que se evalua también de qué forma se  
ha obtenido tal resultado.

##### PRUEBAS FUNCIONALES

- Pruebas unitarias
- Pruebas de regresión
- Pruebas de integración
- Pruebas de humo
- Pruebs del sistema
- Pruebas alfa y bea
- Pruebas de aceptación

A pesar de que hay todas esas, solo estudiaremos las pruebas unitarias a fondo.

#### PRUEBAS NO FUNCIONALES

- Pruebas de usabilidad
- Pruebas de rendimienot
- Pruebas de stress
- Pruebas de seguridad
- Pruebas de compatibilidad
- Pruebas de portabilidad

#### MECANISMOS DE PRUEBA
Hay dos principales mecanismos de pruebas. Los manuales y los automáticos.  
En los **manuales** se requiere de una persona que vaya introduciendo manualmente los datos para  
realizar dichas pruebas.  
En los **mecanismos automáticos** se ejecuta un software ya desarrollado y este  
ejecuta nuestro código de forma automatizada y compara el resultado que da la aplicación  
con los resultados que se esperaban en un principio.

#### SOPORTE DEL DEPURADOR

Cuando depuramos lo que hacemos es marcar un punto de ruptura (punto donde comenzará a depurar)  
y vamos avanzando línea por línea nuestro código analizando el valor de cada variables en el punto  
que nos encontramos.

### INTEGRACIÓN 

#### FORMAS DE INTEGRACIÓN

Existen 4 diferentes formas de integración pero no vamos a profundizar  
en ellas.  
Las formas son las siguientes:

- Integración Big bang
- Integración Descendente
- Integración Ascendente
- Integración Cotinua

#### SERVIDORES DE INTEGRACIÓN CONTINUA

- Jenkins
- Bamboo
- TravisCI
- CircleCI

#### COBERTURA DEL CÓDIGO

La cobertura del código se refiere al porcentaje del código fuente  
del que se han hecho pruebas de una aplicación.  
Por tanto, cuanto más cobertura de código haya tenido una aplicación  
quiere decir que ha sido probado más y tiene menos probabilidad  
de que hayan errores (aunque pueden haberlos, lógicamente).

### CALIDAD DEL CÓDIGO

#### CONTROL DE CALIDAD

El control de calidad se lleva a cabo para saber cómo  
de bueno es una aplicación. Para llevar a cabo dicho control  
se hace mediante pruebas, que determinaran si el código es mejor o peor.

#### CALIDAD DEL PROCESO/PRODUCTO

- QA (Quality Assurance) es, en breves palabras, asegurar el  
correcto funcionamiento de la aplicación que se está o se ha desarrollado.  

- QC (Quality Control) incluye las actividades necesarias para  
asegurar que nuestro producto (en este caso una aplicación)  
cumple con unos requisitos mínimos de calidad.

#### FACTORES DE CALIDAD (I)

El modelo de calidad de McCall define 11 factores de calidad. Los factores se   agrupan en 3 ámbitos:

**Operación del producto**:
**Revisión del producto**:
**Transición del producto**:

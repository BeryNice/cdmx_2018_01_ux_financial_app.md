# Aplicación financiera "Tus Finanzas"


## Diagnóstico

Entre los problemas de experiencia dentro de la etapa 1 y 2 del funnel de conversión se detectaron:
* Tráfico poco adecuado al perfil de usuario planteado
* Los ads atraen público pero no son en su mayoría las user personas que se desea
* Elementos de interacción que confunden al usuario
* Diseño visual y jerarquía de algunos elementos
* Poca claridad respecto al SO de los dispositivos móviles

![preview app de finanzas](https://lh3.googleusercontent.com/WyfUPurRuoXyyeZScQtdLhk063ZozToVlujoljul3TDwJW5KZy3Om_LvuB-TB9IcG2r_BCSpoXtXL-bZjIeGBFxQmL4GYEM2QXnQovq6EvixYaO_Z5-gFMvljM9jye7bVofendMteBI)

El primer obstáculo al que se enfrenta el usuario y el negocio es en facebook ads que no ofrece mucha información sobre la app o el SO móvil para el que fué desarrollada y no filtran el tráfico de usuarios a la landing page, ya que posiblemente no se hayan segmentado los intereses del público al que se dirigen tomando en cuenta las características técnicas de la app “Tus Finanzas” como el sistema operativo o dispositivos.

El mayor número de visitas provienen de **dispositivos móviles con 11,101,856** usuarios, seguido por **computadoras de escritorio con 3,774,631** y por último **tablets con 70,410** usuarios.

Gracias a los recursos invertidos en facebook ads para generar tráfico hacia la landing page, se obtuvo un número de **visitas de entre el 1.82 % y el 4.48 %** respecto al total de impresiones mensuales, pero la conversión no se lleva a cabo ya que el mayor número de visitas son de usuarios Android. Cabe destacar que este grupo de   usuarios sí se interesan por la app “Tus Finanzas” pero al no indicar en ninguna parte del landing page que la app es sólo para iOS, se quedan en esta etapa del embudo ya que la aplicación no está desarrollada para este SO móvil y no pueden continuar el proceso de descarga. 

![porcentajes funnel de conversión](images/porcentajesfunnel.png)

Respecto a los usuarios que sí cuentan con iOS se puede observar que pasan mayor tiempo dentro del landing page a diferencia de los usuarios android pues al ser una app desarrollada para ellos muestran mayor interés y ven más detenidamente la información que ahí se proporciona sobre la app.

* 9,866,962 Android
* 806040 iOS
* 428,854 Otros

Durante el testing del prototipo, algunos usuarios indicaron que les parecía confuso el hecho de que en los botones el CTA dijera “Descárgala ahora” y al dar clic los desplace a un formulario en el que entendían que al registrar sus datos recibirían un correo con el link de descarga, sin embargo esto no sucedía y sólo recibían un mensaje de agradecimiento que los dirigía finalmente al App Store.

## Evaluación del desempeño del landig page y la aplicación 

### Análisis de app en el AppStore antes de instalar

La App tiene un rating muy bajo 2.64
Es la número 7 en finanzas, pero no indica si en latinoamérica como lo dice en la landing page
La edad que muestra es para 9+, aunque en realidad es una app para adultos lo que haría pensar que puede ser para niños

### Análisis de app ya instalada

La primer pantalla muestra un icono como de partenón con una frase que dice,” el banco contigo a donde vayas”, sin embargo no es propiamente la aplicación del banco, sino una aplicación financiera para control de gastos y metas de ahorro, es decir, no ofrece todas las funcionalidades de una App bancaria que permita tener el acceso al banco desde donde estés

#### Proceso regístrate

La pantalla inicial 1/5 de registro muestra el icono de una persona del sexo masculino con corbata en tonos grises y verdes
Al registrarse solicita número de cuenta y número de celular, se llenan los campos y el botón continuar se activa
pantalla 2/5 inmediatamente se muestra una viso en el que indican que han enviado un código por SMS para completar el registro
Se pone el código recibido y el botón de continuar se activa
pantalla 3/5 solicita el correo electrónico y la contraseña
una vez llenados estos dos campos se activa el botón continuar
Pantalla 4/5 muestra un ícono de una persona vestida casual con un signo de + que indica que agregue una fotografía de perfil  y un texto de hacerlo más tarde
pantalla 5/5 si se dá clic en “hacerlo más tarde” muestra una pantalla que dice “Toca para registrar tu huella” pero no indica en dónde debe tocar exactamente
Si se da clic en el texto toca para registrar 

### OBSERVACIONES
La aplicación sólo puede ser utilizada por cuentahabientes del banco y no por público en general pero nunca se indica

#### Proceso inicia sesión

Si un usuario ya se ha registrado previamente puede dar clic en Iniciar sesión que lo llevará a una pantalla que le indica poner su huella en el botón home para iniciar. Una vez colocada la huella el sistema la reconoce  envía un mensaje de huella verificada acceso confirmado y envía a la pantalla inicial.

### OBSERVACIONES
A pesar que en el registro se pidió un correo electrónico y contraseña, en el   momento de iniciar sesión solo permite el inicio con huella, así que no permite otra alternativa al usuario y se convierte en un dato que se requirió inicialmente y nunca se vuelve a usar.

### 1.Inicio en la App

Pantalla de bienvenida app muestra nombre de usuario y  cuenta vinculada con el saldo disponible
el menú principal se encuentra desplegado, se conforma por Movimientos, Ahorros y Gastos
Muestra 2 iconos en la parte superior, izq menú hamburguesa con el perfil del usuario que despliega nombre y fecha y hora de última conexión, lado derecho icono de alertas pero no está activo

### 2.Movimientos 

La transición entre pantalla es rápida aunque es poco común ya que parece que se va a minimizar pero sólo cambia de tamaño y se desliza de derecha a izquierda para avanzar, para ir atrás se desliza en sentido contrario
A pesar de que es la sección de movimientos no hay un título que muestre al usuario en qué sección está
En la sección Movimientos muestra un primer módulo en verde que abarca una tercera parte de la pantalla con título de Saldo Disponible y un pequeño icono de buscador al lado superior derecho que no tiene función activada
Ubicado del lado superior izquierdo se encuentra el botón para regresar a la pantalla anterior junto al título
Para poder ver los movimientos existe un input de lista de selección que permite mostrar los movimientos por mes organizados de más recientes a anteriores
Despliega un listado de movimientos con tìtulo y fecha de operación marcando en rojo y con símbolo negativo los gastos y en verde y símbolo positivo los ingresos mostrando primero los movimientos más recientes
En el prototipo el menú circular no se mantiene fijo en esta pantalla y se desliza al momento de dar scroll a la lista

#### 2.1 Detalle de movimiento ingresos
La transición es simple cambio de pantalla sin ningún tipo de efecto
Muestra un módulo principal al igual que la sección anterior en verde, contiene el título detalle operaciones, el nombre del movimiento yingreso  el monto epositn positivo. ocupa alrededor de una cuarta parte de la pantalla
ubicado del lado superior izquierdo se encuentra el botón para regresar a la pantalla anterior 
La información de detalle del movimiento tiene subtítulos en inglés y español “Given Operation” con fecha y hora del movimiento y “Descripción” que muestra que el pago se realizó con tarjeta de débito (número de tarjeta #5642 que supongo es ta terminación) el nombre del establecimiento y ubicación registrada
Al final muestra nuevamente el menú que al dar clic muestra las opciones de Movimientos, Ahorros y Gastos 
Desaparece el icono de buscar
#### 2.2 Detalle de movimiento  gastos
Muestra un módulo principal al igual que la sección anterior pero esta vez en fondo rojo porque es un gasto, contiene el título detalle operaciones, el nombre del gasto y el monto en negativo. ocupa alrededor de una cuarta parte de la pantalla
La información de detalle del movimiento tiene subtítulos en inglés y español “Given Operation” con fecha y hora del movimiento y “Descripción” que muestra que el pago se realizó con tarjeta de débito (número de tarjeta #5642 que supongo es ta terminación) el nombre del establecimiento y ubicación registrada
Al final muestra nuevamente el menú que al dar clic muestra las opciones de Movimientos, Ahorros y Gastos 
Desaparece el icono de buscar

### 3. Ahorros

Muestra un módulo que cubre el 30% de la pantalla contiene el botón para regresar, el título Ahorros y el ícono de búsqueda

El listado de ahorros es muy simple y permite visualizar el nombre de la meta, el monto y el porcentaje de avance sin embargo el botón para crear una nueva meta de ahorro parece no pertenecer a ningún menú y estar flotando libremente, el texto que acompaña este botón no se relaciona con la creación de meta de ahorro. Una vez que el usuario da clic en ese botón se percata de que es para crear una meta de ahorro  a través de un formulario breve y puntual con el nombre de la meta, el monto y la fecha, automáticamente el sistema divide el monto total entre el lapso de tiempo y asigna el monto que se sumará semana tras semana.

### 4. Gastos

Esta sección muestra una consistencia en cuanto al despliegue de la información, utilizando un fondo rojo que hace clara referencia a gastos muestra todos los gastos clasificados por categorías y la suma total de cada categoría lo que permite ver de una manera más sencilla en qué categorías gastas más permitiendo al usuario tomar medidas al respecto, sin embargo no permite crear nuevas categorías.

## Propuesta de optimización del producto
... 

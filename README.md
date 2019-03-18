## I. Decisiones

Antes de comenzar, nos propusimos realizar un Benchmark para tener en consideración cómo trabajan otras aplicaciones ya que en las entrevistas a los usuarios uno de los puntos que conversamos fue que ellos habían probado aplicaciones que los ayuden a organizarse financieramente pero que terminaban eliminándolas porque no era automatizada y eso terminaba por desanimarlos a seguir usándola. Es aquí que tomamos la decisión de darle un giro a la aplicación actual y crear un lazo más fuerte entre nuestro cliente y la usuaria. Así, cada cambio realizado se pensó teniendo en cuenta las conclusiones de las entrevistas y los testeos. Otro punto importante a aclarar es que priorizamos mantener el diseño de la aplicación para dispositivos iOS por el hecho de fidelizar en primer lugar a los clientes que ya estaban familiarizados con la aplicación y una vez logrado este objetivo, como un plan de futura mejora tenemos la tarea de dirigirnos a usuarios con dispositivos Android.

Ahora nos enfocaremos en mencionar los siguientes cambios que permitirán mejorar la experiencia de uso, hacerla dinámica y, sobre todo, acercarnos más a los usuarios:

### 1. Vista general

Hemos mantenido la tipografía, paleta de colores brindada por el cliente y guardado la esencia de la estructura para que el usuario no pierda la conexión con el banco.

### 2. Inicio de sesión

Dejamos abierta la opción a que el inicio de sesión sea con huella o de forma tradicional, esto debido a que no necesariamente todos los usuarios tienen activada la opción de digitar su huella.

<p align="center">
 <https://i.ibb.co/BySz5Rj/Inicio-de-sesi-n.png">
</p>

### 3. Home

Como primera impresión para la usuaria, el saldo disponible, monto de gastos y ahorros se encuentra oculto dado que por una razón de seguridad la usuaria puede revisar sus montos de forma privada en cualquier lugar. A través de un botón switch puede realizar la acción de mostrar. Y como un cambio radical, descartamos la idea de considerar la tarjeta como un elemento en el diseño, esto porque lo veía innecesario y una vez más, aquí prima la seguridad para no exponer su número de tarjeta.

<p align="center">
 <img src="https://i.ibb.co/cyWng23/Home.png">
</p>

Cuenta con dos secciones de gastos y ahorros que la llevan a revisar el detalle de los mismos. Al momento de mostrar los montos, colocamos unos íconos en ambas secciones que hacen referencia a si actualmente está gastando o ahorrando más. 

<p align="center">
 <img src="https://i.ibb.co/HTL6fBC/Home-1.png">
</p>

Modificamos el menu bar dándole un estilo totalmente distinto y aunque disruptivo, apostamos a que la usuaria se sienta cómoda al interactuar. 

<p align="center">
 <img src="https://i.ibb.co/FJZSxZB/Men.png">
</p>

### 4. Movimientos

Decidimos organizar los movimientos por fechas para tener una mejor vista de los mismos y dar a la usuaria los datos ordenados y de fácil ubicación. (FOTO)
También puede acceder al detalle de cada movimiento clickeando al que desee. Al entrar, podrá conocer la hora, fecha y lugar exacto y el número de tarjeta con la que hizo el pago. 

<p align="center">
 <img src="https://i.ibb.co/nMRPDQN/Movimientos.png">
</p>

### 5. Gastos

Agregamos un bar chart horizontal con la finalidad de que se visualice no solo las categorías con el monto gastado en cada una sino que el usuario pueda detectar en cuál categoría gasta más y poder tener más control sobre ella. Las categorías están diferenciadas por color para su fácil identificación. 

<p align="center">
 <img src="https://i.ibb.co/HNSV0B6/Gastos.png">
</p>

### 6. Ahorros

Lo primero que hicimos fue reubicar el botón “crear cuenta” ya que los usuarios entrevistados no lograron identificar tan fácilmente. 
Siguiendo la línea del Home, agregamos un botón que pueda ocultar-mostrar el monto ahorrado que tiene la usuaria para evitar que sea expuesto.
Adicionalmente dada la observación de los usuarios, agregamos el monto del avance de cada meta en lugar que solo se muestre el progreso en porcentaje. 

<p align="center">
 <img src="https://i.ibb.co/7Jkj3bw/Ahorros.png">
</p>
La pantalla que aparece al darle click en “Crea tu meta de ahorro”, cuenta con una comunicación que logra más cercanía del Banco con la usuaria rompiendo esa seriedad que caracteriza a un banco convencional cuando quiere comunicarse con sus clientes. 

<p align="center">
 <img src="https://i.ibb.co/GQsn0Qn/Crear-ahorro.png">
</p>

Al confirmar su nueva meta de ahorro, hay un mensaje felicitando al usuario para darle una motivación extra para que empiece con su ahorro.

<p align="center">
 <img src="https://i.ibb.co/XVKwL1y/Mensaje-felicitaciones.png">
</p>

### 7. Valor agregado

Considerando las observaciones de los usuarios y como una manera de incentivo, añadimos un sistema de notificaciones: Una de ellas se trata de recordar el progreso de su meta y de alentarlos a seguir con su enfoque; en este caso, por efectos de practicidad, el usuario ya no tendría que entrar directamente a la aplicación. La otra, es avisarles que cumplieron con su meta de ahorro e invitarlos a que vayan por una nueva meta, así también fomentamos el uso de la aplicación con frecuencia. 

<p align="center">
 <img src="https://i.ibb.co/DGWHtvG/Valor-agregado-1-0.png">
</p>

Mediante un mensaje pop up pensamos en sugerirle a los usuarios si se están excediendo en alguna categoría de gastos, así puede llevar un mejor control si se compara con un mes previo; además, podría priorizar sus ahorros para futura fecha.

Si los usuarios quisieran retirar su monto ahorrado, ideamos una opción en la que el Banco les sugiere darle ese dinero que necesitan con una comunicación que de primera impresión no les insinúe que es un préstamo sino todo lo contrario, quieren generar un vínculo mucho más fuerte dándole esta facilidad en un formato más sutil. 

<p align="center">
 <https://i.ibb.co/dtcNFnP/Valor-agregado.png">
</p>

## II. Recomendaciones

Proponemos los próximos desarrollos:

### 1. A nivel de Landing Page

Como cambio primordial, tenemos que rediseñar la landing page. Uno de los puntos clave es darle un giro a la comunicación; es decir, que el objetivo principal del uso de la aplicación se entienda y sea transmitido en este site. 
Para complementar el punto anterior, el CTA de descargar la aplicación va a cambiar y se mostrará de forma más puntual y sencilla: 1) Será reubicado, ya no estará ubicado en la parte inferior sino en un lugar más visible. 2) En lugar de solicitar que el usuario se registre antes de descargarse la aplicación, va a ser dirigido automáticamente al Appstore en el caso de iOS.
Dada la oportunidad de potenciar la aplicación, un reto a largo plazo es dirigir los esfuerzos para diseñar y desarrollar la aplicación para sistema operativo Android; ya que, al analizar la data brindada por el cliente, el 93% de los usuarios poseen este sistema operativo.
Por último y no menos importante, es el contraste de color y la jerarquía en los textos: Muchos no son de fácil lectura porque el color de fondo usado lleva a que se pierda el contenido y sobre la jerarquía, no es entendible a cuáles textos hay que prestarle más atención que a otros.

### 2. A nivel de la App

Implementar un chatbot que permita justamente: generar una conversación cercana entre los usuarios y el banco, resolver dudas frecuentes, obtener información específica y recomendaciones de algún producto del banco según el perfil de los usuarios.
De acuerdo al monto disponible en la cuenta, la aplicación (banco) sugerirá al usuario cuánto podrá ahorrar si es que no tiene una meta de ahorro.
Asimismo, otra modalidad sería plantearle a los usuarios una meta de ahorro automática la cual se basa en que ellos no tienen un objetivo en específico de ahorro sino donde tendrán la posibilidad de elegir el porcentaje a debitar de su monto disponible y al finalizar el periodo elegido podrán usarlo según su fines.

### 3. A nivel de publicidad

Realizamos las siguientes sugerencias al equipo de marketing:

Analizar la posibilidad que cierto porcentaje de la inversión en publicidad que actualmente realizan en Facebook sea redirigido a Instagram ya que es la red social que con más frecuencia visitan los usuarios. 
Dicho esto, para lograr mayor engagement, sería muy interesante trabajar activamente con influencers/bloggers porque consigue captar mucho más rápido la atención de los usuarios.
Una manera interesante de alcanzar a más personas es trabajar en los Referal Programs. Significa que a los usuarios que disfrutan de la aplicación, la recomiendan a su entorno cercano o amigos, logrando algún tipo de compensación si  se llega a captar nuevos clientes, estos serían: efectivo, descuentos, puntos canjeables o cupones.
Emplear SEO (Search Engine Optimization) para mejorar el posicionamiento de la web, su difusión o para dar a conocer la aplicación.

## III. Entregables

1. Prototipo

[Sketching](https://drive.google.com/drive/u/0/folders/10QuG4I2BmnyhGdPJBNL7pSVIatKbsjOT)

2. Prototipado MVP 

Para revisar la documentación:

- [Prototipo de alta fidelidad en Figma](https://www.figma.com/file/EhZpSrAt5Pfgj2UAre8yZ3/Financia-app-1.1?node-id=0%3A1)

- [Prototipo navegable en Marvel](https://marvelapp.com/4fg23d7/screen/54261302)

- [Marvel Userflow](https://userflows.marvelapp.com/4fg23d7?utm_campaign=prototype-player&utm_source=other&utm_medium=web-app&utm_term=player&utm_content=userflows)

3. Marvel hands-off o Zeplin (LINK)

4. Video LOOM (LINK)

5. [Documentación en Google Drive](https://drive.google.com/drive/u/0/folders/1yvmGdRE_iiquHitLbAVpo44RCbbhuIi0)

6. [Herramienta de planificación en Github](https://github.com/sandramelisa/lim008-ux-financial-app/projects/1)

<p align="center">
 <img src="https://i.ibb.co/T2P7C9V/Github.png">
</p>

## IV. ¿Cómo realizamos nuestro proceso de trabajo? 

Encuentra aquí el detalle de todas las entrevistas y herramientas que utilizamos.

### 1. Testing inicial con Maze 
 
La primera herramienta que utilizamos para testear el prototipo inicial fue [Maze.design](https://maze.design/projects/2503519/mazes/2503555), la cual nos permitió obtener los primeros problemas y así poder idear primeras posibles soluciones. 

Al analizar los resultados, obtuvimos que de 25 usuarios testeados, 14 completaron la tareas asignadas y 11 abandonaron o rebotaron. La mayoría de usuarios, tuvo dificultades al momento del registro; claramente es el flujo con mayor relevancia para los usuarios ya que se llevan una mala impresión por lo tedioso que puede ser para ellos y de eso depende la conexión y uso de la aplicación a largo plazo. Entonces, desde ese punto y otras observaciones recopiladas en el testeo, pudimos accionar con algunos cambios. 
<p align="center">
 <img src="https://i.ibb.co/X7HMKD5/Maze-1.png">
</p>

### 2. User testing inicial 
Los usuarios coinciden en que el registro es muy similar a otras aplicaciones que han usado.
La mayoría de usuarios testeados indicó que la foto personal no debería ser requisito al momento del registro. Básicamente por cuestiones de seguridad prefieren no tenerla porque no les genera ningún valor, todo lo contrario, sienten temor de que alguien sepa su identidad; además, no están familiarizados con ese feature ya que las aplicaciones de banco que han usado no cuentan con algo similar.
Los usuarios no se sentían cómodos al interactuar con el menú flotante.
La estructura de la categoría gastos les parece comprensible e interesante la forma en que los gastos se agrupan en categorías. Hay dos features que les gustaría ver: a) Contar con barras estadísticas para que tenga conocimiento en dónde están gastando más y b) En cada categoría esperan encontrar el detalle de los gastos.
Al ingresar al detalle de cada movimiento, les parecería más completo si se agrega la dirección del establecimiento donde hizo algún consumo y que figure exactamente a dónde se dirigió el monto pagado.
Al ubicarse en la sección ahorros, no entendían por qué existe un botón que dice “crear cuenta”, piensan que es para aperturar una cuenta del banco. Además, la ubicación del botón no están tan fácilmente de ubicar, prefieren en un lugar más visible y con un nombre cercano para mejor identificación.
Al revisar las metas de ahorro, les sería más utilidad que aparezca el monto de avance y no solo el porcentaje.
Además de que la aplicación les permite ver sus gastos, movimientos y ahorros, les motivaría a sostener sus metas ahorro contar con notificaciones cada vez que logren cumplir una y también cuando logren avanzar.
En ninguna parte de la aplicación encuentran una opción para volver al home o a cualquiera de las secciones.

### 3. User persona primario 

<p align="center">
 <img src="https://i.ibb.co/3B5WBpT/User-persona.png">
</p>

### 4. Benchmark

Decidimos tomar como referencias a las siguientes aplicaciones en primer lugar porque los usuarios entrevistados mencionaron algunas de ellas por haberlas usado en alguna oportunidad y llamaron su atención por las funciones que tenían y en segundo lugar, porque nos permitió contar con un panorama más amplio y claro al considerar a plataformas del extranjero: EE.UU y Europa.

Casi todas, tenían el atributo de fomentar el ahorro, de mostrar un reporte de gastos mensual no tan digerible pero pocas brindaban la función del envío de recordatorios, entre otras. En nuestro caso, luego de las entrevistas, testeo y benchmarketing como valor agregado (vista general) le brindamos a los usuarios la posibilidad de:
Ubicar de forma más precisa en dónde gasta más, 
Vistas automatizadas, es decir, no tendrían que ingresar manualmente los gastos como otras aplicaciones del mercado,
Contar con notificaciones al momento de: completar una meta y estado de cumplimiento de cada una.

<p align="center">
 <img src="https://i.ibb.co/Cm50472/Benchmark.png">
</p>

# Final

## Sesion 1: Que es un Proyecto
Un proyecto es una combinacion de recursos aplicados durante un lapso con la finalidad de obtener un producto o servicio.

Normalmente se divide en 4 etapas: Factibilidad, Planeacion, Ejecucion y Cierre.

Las 3 variables mas importantes durante el desarollo de un proyecto son: el alcance, el costo y el tiempo. Estas 3 variables se relacionan en un triangulo. Modificar alguna de las 3 tiene repercuciones en las otras 2.

## Sesion 2: Admin de Alcance, Estructura del Proeycto, Matriz de Responsabilidades

El alcance del proyecto debe cubrir:

* Que esta incluido?
* Que NO esta incluida
* Metas intermedias
* Productos Finales

Los pasos para definir el alcance son:

1. Recopilar requisitos: documentar las necesidades de los stakeholders
2. Definir el alcance: Desarrolar una descripcion detallada del proyecto junto con una matriz de responsabilidades
3. Crear la Estrucutra Desgolsada de Trabajo: Dividir las tareas en partes mas faciles de manejar
4. Verificar el alcance: Formalizar los criterios de aceptacion de las tareas
5. Controlar el alcance: Seguir procesos de monitoreo dealcance para gestionar cambios requeridos.

### Proyect Charter
Para especificar los detalles generales del proyecto se utiliza un Proyect Charter. Autorizando el charter se da un banderazo del comienzo del proyecto.

### EDT - WBS
Es la division jerarquica de los entrgables del proyecto. El primer nivel es el proyecto y los ultimos hijos son paquetes de trabajo, la carga de trabajo que facilita la medicion de una tarea.

El paquete de trabajo debe responder estas preguntas:

1. Que?
2. Quien?
3. Como?
4. Presupuesto?
5. Cuando
6. Con quien?
7. Con que calidad?

El WBS tiene que contener el 100% del proyecto. Se debe desglosar en porcentaje cada jerarquia del proyecto hasta que la suma de todos los hijos entregue el total.

### Matriz de Responsabilidades (RACI)
La matriz dicta quien se va a encargar de ejecutar los paquetes de trabajo del EDT. RACI es uno de los estandares mas comunes y especifica quien es Responsible, Accountable, Consulted, Informed.

## Sesion 3: Gestion del Cronograma

Hay 5 pasos para gestionar chingon el cronograma del proyecto:

0. Establecer Politicas del cronograma
1. Definir actividades
2. Secuenciar actividades
3. Estimar duraciones
4. Desarollar el Cronograma
5. Controlar el cronograma

### Secuenciar actividades
La secuencia es la identificacion de la relaciones logicas entre tareas. Se utiliza el metodo de Activity on node (AON) para hacer un mapa de actividades y sus dependencias con flechas. Hay 4 tipos de dependencias

* Finish to Start
* Finish to Finish
* Start to Start
* Start to Finish

La mas comun es Finish to Start

Cuando se define todo el mapa, la ruta mas larga es la ruta critica. Y a partir de ese mapa se puede avanzar con la definicion del cronograma. El cual define los tiempos de comienzo y fin de las actividades. 

Se puede usar el Crirical Path Method (CPM) para hacer 2 pasadas al mapa y sacar tiempos tempranos y tardios asi como holguras y margenes de demora de las actividades con la finalidad de obtener la duracion del proeycto o ruta critica.

![Grafica Ciclo de Vida](/Users/humberto/Desktop/Screen Shot 2017-11-26 at 8.16.10 PM.png)

* ES: Early Start
* EF: Early Finish
* LS: Late Start
* LF: Late Finish
* SL: Slack

* La **primer pasada** se suma el start con la duracion y en merges se selecciona el mas grande.
* La **segunda pasada** se resta el finish menos duracion y en bifurcaciones se selecciona el mas chico.
* Luego ya nomas se calcula **Slack**

Hay 2 tipos de slack: Holgura total, es la cantidad de tiempo que se deja pasar sin joder el proyecto. 

Holgura libre es la cantidad que se puede dejar pasar sin joder la siguiente actividad. Esta solo la pueden tener tarea antes de un merge.

Para reducir el tiempo en caso de que la ruta critica este muy pendeja. Se puede hacer Crashing: reducir la duracion de las tareas. O fast-tracking: cambair las relaciones de las tareas por otras que ahorren tiempo.

## Sesion 4: Recursos y Costos

### Recursos
Los recursos son personas, materiales, equipo, etc que son necesarios para ejectuar el proyecto. Se dividen en consumibles (no se pueden reasignar) o no consumibles (representan trabajo)

Al momento de hcaer las estimaciones de tareas siempre se asume que los recursos son infinitos y siempre estan disponibles. Esto sin embargo rara vez es el caso y se deben solucionar 2 posibles problemas de recursos: Problema de restriccion de Recursos o Problema de nivelacion de recursos.

Se asignan los recursos con el metodo ABRA que es asignar recursos basado en cada actividad y respondiendo las preguntas:

* Que recursos se necesitan
* Unidades de medida
* Cantidades requeridad
* Disponibilidad de los recursos.

Esto sirve como base para la estimacion de costos. Ya definidos todos los recursos se puede hacer un mappeo de la cantidad de recursos a lo largo del proyecto y se procede a resolver uno de los 2 problemas anteriores.

La **nivelacion** se resuelve moviendo actividades no creiticas para que quede mas balanceado el uso de recursos en el tiempo.

Para el problema de **REstriccion** hay varias formas segun al heuristica. Puede ser moviendo aquellos con mas holgura o alguno de estos metodos:

* Fondahl:	Se	da	prioridad	a	las	actividades con	menor	Tiempo	Tardío	de	Inicio	(LS)	(respetando	precedencias	
* Shafer:	En	caso	de	conflicto	se	escoge la actividad	con	menor	Tiempo	temprano	de	Terminación	(EF)	
* SPART	(Schedulling	Program	for	Allocationof	Resources):	El	 criterio	es	la	holgura	de	la	actividad.	Este	método	se	le	conoce	también	con	el	nombre	de	su	autor	(Wiest).	

### Costos
Definir los costos de un proyecto es de las tareas mas dificiles pero de las mas importantes del proyecto. Igual que con los recursos se puede hacer una estimacion de costos partiendo del EDT. Pero hay 2 formas de hacerlo:

* Arriba hacia abajo: Se basa en el expertiz de los involucrados. Se asignan costos a las tareas mas grandes del proyecto y se reparten hacia los hijos.
* Abajo hacia arriba: Se toma en cuenta la opinion de las personas que ejecutan los paquetes de trabajo. Se asigna a todos los paquetes y se suma hacia arriba. Es mucho mas exacto pero el pedo es que esto es mucho mas lento de hacer.

Ademas el costo unitrio del proyecto, es decir el total. Se divide entre los costos directos e indirectos. Los costos directos son aquellos directamente relacionados a la ejecucion de tareas. Los indirectos estan mas relacionados a la duracion del proyecto y se reducen con la reduccion de la duracion.

Con estos 2 costos se hace un diagrama coqueto:
![](/Users/humberto/Desktop/Screen Shot 2017-11-26 at 9.59.02 PM.png)

### Acortamiento de redes
Si se hace fast tracking se hace overlap de las tareas. El riesgo es que se super desbalancea la asignacion de recursos o hace que los recursos no esten disponibles.

Si se hace crashing se tiene que hacer todo un proceso de ir reduciendo por etapas para llegar al costo optimo del proyecto porque:
![](/Users/humberto/Desktop/Screen Shot 2017-11-26 at 10.00.57 PM.png)

Al reducir tareas se debe calcular el costo marginal que es:
![](/Users/humberto/Desktop/Screen Shot 2017-11-26 at 10.02.21 PM.png)

Por cada etapa se seleccionan las tareas a reducir y se calcula de vuelta el costo directo e indirecto para sacar el total. Se van reduciendo dias hasta encontrar el minimo en el costo total.

## Sesion 5
Liderazgo D:

## Sesion 6: Stakeholders y negociacion
los **Stakeholders** son individuos, grupos u organizaciones que se ven directamente afectados por el desarollo de unproyecto.

Pueden estar participando activamente en el desarollo del proyecto o incluso pueden solo verse afectados por el mismo de manera indirecta y por lo tanto se deben tomar en cuenta tambien. Ejemplo, la raza de un rancho donde se va a construir un puente o algo asi.

Pueden influir sobre el proyecto y sus entregables.

## Sesion 7: Riesgo
**Riesgo** y **Problema** no son la misma cosa. Un problema es algo malo que ya esta sucediendo mientras que un riesgo se puede prevenir antes de que suceda.

Tambien hay riesgos que pueden tener resutlados positivos. Se les conoce mejor como **oportunidades**

Segun la posicion ante un riesgo se puedena doptar diferentes actitudes o conductas.

Una persona que reconoce el riesgo como una amenaza toma una actitud de **Aversion**. Sin embargo alguien que considera que el riesgo es una oportunidad obtiene una actitud de **"Tomadora de Riesgo"**. Tambien hay personas que ven ambas caras de la moneda y tiene una actitud de **Neutralidad**

Para clasificar los riesgos se puede usar un **Risk Brakdown Structure (RBS)** que es similar al WBS pero agrupa en jerarquia el tipo de riesgos que pueden impactar el proyecto.

### Manejo de Riesgo

Para riesgos negativos:

* Evitar
* Transferir
* Mitigar

Para oportunidades

* Explotar
* Compartir
* Mejorar

![](/Users/humberto/Desktop/Screen Shot 2017-11-27 at 4.48.46 PM.png)

## Sesion 8: Estrategias de Control
### Control de Proyectos

1. Establecer el plan del proyecto (programa y presupuesto)
2. Inicial ejecucion del proyecto
3. Recopiar informacion sobre desempeño real
4. Comparar la situacion actual con el plan
5. Preguntarse si se necesitan acciones correctivas?
6. Identificar acciones correctibas e incluir cambios relacionados
7. actualizar el proyecto
8. Esperar hasta el proximo periodo de presentacion
9. go to 3

**Agenda de reunion de control**

1. Compromisos anteriores
2. Puntos de la reunion
3. Acciones a tomar

**Minuta**

1. Compromiso
2. Quien lo va a hacer
3. Cuando lo va a hacer

### Indicadores de control

* Checklist
* Lista con fechas
* Indicador % de avance (Puede ser turbo falso o turbo verdadero)

4 formas para calcular el **% de avance**

* **Tiempo transcurrido:** tiempo transcurrido / tiempo planeado
* **Horas de trabajo**: horas asignadas/ horas planeadas
* **Costo**: Gasto / Presupuesto
* **Unidades**: unidades logradas/ unidades planeadas

### Reportar el avance

* Identificar qué reportar y a quién.
* Definir la periodicidad de los reportes.
* Elaborar formatos estándar.
* Identificar el medio de distribución.

**¿Qué reportar? (Mínimo)**

* Fecha del reporte y período.
* Breve descripción del estado del proyecto (Tipo ISO).
* Actividades relevantes.
* Aspectos críticos y acciones a tomar.
* Actividades del próximo período.
* Gráficas y/o tablas de avance.

## Sesion 9: Control con EVM
![](/Users/humberto/Desktop/Screen Shot 2017-11-27 at 4.20.27 PM.png)

![](/Users/humberto/Desktop/Screen Shot 2017-11-27 at 4.20.37 PM.png)

![](/Users/humberto/Desktop/Screen Shot 2017-11-27 at 4.23.51 PM.png)

![](/Users/humberto/Desktop/Screen Shot 2017-11-27 at 4.20.03 PM.png)

## Sesion 10: Cierre
Principales actividades dentro del cierre del proyecto:

* Evaluar si el proyecto cubre los beneficios esperados de los stakeholders
* Evaluar qué salió bien y que salió mal durante el proyecto
* Identificar oportunidades para mejorar en futuros proyectos


**Cierre de Proyecto**
Implementar cierre:

* Obtener aceptación del cliente
* Liberar recursos del proyecto
* Reasignar miembros del equipo de proyecto
* Cerrar y pagar cuentas
* Evaluar el equipo de proyecto, gerente de proyecto. Incluir sugerencias para siguientes proyectos
* Documentar mejores prácticas y lecciones aprendidas


* Lecciones aprendidas
* Análisis que se lleva a cabo al terminar el proyecto, se registran las enseñanzas positivas y negativas.
* Se usarán en siguientes proyectos
* Se busca evitar caer en los mismos errores


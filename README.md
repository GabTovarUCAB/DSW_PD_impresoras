# DSW_PD_impresoras
Actividad donde se aplican los conocimientos de Patrones de Diseños, Diagrama de Clases y Diagrama de Secuencias para la materia Desarrollo de Software, Sep-Ene 2019.


## Enunciado

### Contexto
En un sistema en funcionamiento disponemos de una clase IMPRESORA capaz de gestionar una impresora. Entre las características de esta clase, se encuentran las siguientes operaciones:

obtenerTrabajosEnCola: obtiene la cantidad de trabajos (número entero positivo) encolados que deben ser impresos
pausarImpresion: obtiene un estado (booleano) de encendido o apagado
estaImprimiendo: permite conocer si se esta imprimiendo un trabajo, que anteriormente haya estado encolado.
obtenerTrabajoParaImprimir: obtiene el trabajo proximo a ser impreso.
Se desea entonces, elaborar un Sistema de Impresion capaz de permitir que 1 o mas Impresoras puedan unirse, permitiendo procesar de forma ordenada la cola de impresión definida en cada Impresora hasta haber procesado la totalidad de trabajos. En el preciso instante que el sistema comience a procesar la impresion de cada trabajo, el resto de las impresoras deben pausar su trabajo, para evitar un colapso en las bandejas de impresion a donde se envia cada trabajo impreso en papel. 

### Requerimientos
Implementar una solución que adopte 1 o mas patrones de diseño para cumplir con las funcionalidades del sistema mencionado arriba. Indicar el o los patrones adoptados.
Modelar en un diagrama de clases y de secuencia los componentes necesarios para dar soporte al punto 1.
Presentar la implementacion, en el lenguaje de su preferencia, la implementación para el diseño expuesto en los puntos 1 y 2.
 

### Método de Entrega:
URL del repositorio con los artefactos mencionados en la seccion de Requerimientos.
Adjuntar los diagramas de clases y secuencia en el repositorio.
La tarea debe ser entregada en equipos de maximo 3 personas, equipos de proyectos por facilidad.

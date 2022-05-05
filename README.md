# MÓDULO INFERENCIA FILOGENÉTICA

<p align="center">
  <img src="https://scx2.b-cdn.net/gfx/news/hires/2015/treeoflifefo.jpg" width="330" height="300" />
</p>

Figura tomada de: _https://scx2.b-cdn.net/gfx/news/hires/2015/treeoflifefo.jpg_

## Objetivos

1. Aprender las bases metodológicas de los principales métodos de inferencia filogenética a partir de matrices de caracteres homólogos y evaluar críticamente los supuestos, virtudes y desventajas de estos métodos.

2. Conocer los principios estadísticos para medición de la confianza de las hipótesis filogenéticas.  

3. Adquirir destrezas computacionales básicas para llevar a cabo análisis de inferencia filogenética a partir de matrices de caracteres.

## Competencias

1. Habilidad de inferir e interpretar críticamente hipótesis de relaciones filogenéticas en cualquier grupo de organismos generadas bajo distintas metodologías a partir de matrices de caracteres.

2. Capacidad para interpretar fundamentos de la biología evolutiva en un árbol filogenético generado a partir de matrices de caracteres empíricas.

3. Entendimiento de la importancia de la inferencia filogenética para abordar problemas biológicos en un contexto evolutivo.

## Estructura general del módulo

### Preparación

Este módulo ha sido diseñado para estudiantes del curso de pregrado "Sistemática Biológica" del programa de Biología de la Universidad Nacional de Colombia. Los estudiantes inscritos en este curso ya debieron haber tomado clases previas sobre temas introductorios de evolución y sistemática filogenética para poder seguir con los contenidos de este módulo.

#### Requerimientos y materiales básicos

Se recomienda a los estudiantes que puedan y tengan acceso a computadores propios bajar los siguientes programas:

- Editor de texto (recomendados notepad++ para Windows y Atom o BBEdit para Mac).
- [MEGA X](https://www.megasoftware.net/). Útil para muchas tareas asociadas a análisis filogenéticos usando secuencias de ADN.
- [Mesquite](https://www.mesquiteproject.org/). Útil para construir y/o visualizar matrices de caracteres.
- R y R Studio (bajar los paquetes: Ape, Claddis, Phangorn, Phytools).
- [TNT](http://www.lillo.org.ar/phylogeny/tnt/). GUI solo para Windows. Para análisis de Máxima Parsimonia.
- [jmodelTest](https://github.com/ddarriba/jmodeltest2). Para selección de modelos evolutivos de secuencias de nucleótidos.
- [RAxML-GUI](https://antonellilab.github.io/raxmlGUI/). Para análisis de Máxima Verosimilitud.
- [BEAST2](https://www.beast2.org/). Para análisis de Inferencia Bayesiana (y muchas cosas más). 
- [FigTree](https://github.com/rambaut/figtree/releases). Para visualización y edición de árboles filogenéticos.
- [Tracer](https://github.com/beast-dev/tracer/releases/tag/v1.7.1). Para visualizar resultados de MCMC.

**Nota:** Todos los programas de inferencia filogenética vienen acompañados con sus respectivos tutoriales. Se sugiere seguirlos en su tiempo libre si quieren adquirir destrezas más avanzadas; no se limiten únicamente a los ejercicios de la clase.  

#### Evaluación

La nota del módulo será dividida de la siguiente manera: talleres, quizes y tareas (60%), proyecto del módulo (40%).

## Contenido

#

**[Clase 1](/clase_2/Clase_1_2022_1.pdf). Estructura de un estudio de inferencia filogenética y construcción de matrices.** 

**1. Estructura de un estudio de inferencia filogenética.** Exploración del esqueleto de un estudio de inferencia filogenética (bajar la presentación [aquí](/clase_2/Clase_1_2022_1.pdf)). 

**2. Explicación del proyecto del módulo** (ver las instruciones del proyecto [aquí](/clase_3/proyecto.md)).

**3. Matrices de caracteres para inferencia filogenética.** En esta parte práctica sentaremos las bases de la construcción de matrices de datos para inferir hipótesis filogenéticas. Hablaremos sobre homología primaria y codificación de matrices y haremos un taller de construcción de matrices morfológicas y de secuencias de ADN. En este último ejercicio aprenderán las bases para descargar datos de [GenBank](https://www.ncbi.nlm.nih.gov/nucleotide/); entender un archivo de extensión "fasta"; generar un alineamiento de secuencias con mafft; y entender los formatos de archivos para inferencia filogenética. La instrucciones detalladas del taller se encuentran [aquí](/clase_3/Taller_4.md).

**Tarea 1:** Subir las respuestas del taller 1 a la carpeta "Taller 1" del [Drive del curso]() a mas tardar el lunes 9 de mayo.

**_NOTA:_** Para la próxima clases se requiere leer alguno de los siguientes artículos:

- Máxima Parsimonia: [Lanteri (2006)](/clase_3/Parsimonia.pdf) **o** [Baum & Smith (2013)](/clase_3/MP_baum_smith2013.pdf)

#

**[Clase 2](/clase_4/Taller_MP.md). Máxima Parsimonia** Esta clase hace una breve mención a los métodos que dieron origen a los métodos modernos de inferencia filogenética y abordaremos el concepto del criterio de optimalidad y el método de la Máxima Parsimonia. Descargar diapositivas [aquí](/clase_2/Clase_2.pdf). 

<p align="center">
  <img src="https://github.com/jaaguirresant/Sistematica-Filogenetica/blob/master/clase_2/Hennig_book.jpg" width="130" height="200" />
</p>

**Tarea:**

**[IR AL TALLER](/clase_4/Taller_MP.md)**



**NOTA:** Para quien quiera ir prácticando con el script de R que usaremos en la próxima clase, se puede bajar [aquí](/clase_5/parsimonia.R)

#

**[Clase 4](/clase_5/Taller_MP2.md). Máxima Parsimonia II.** En esta clase se explican algunas ramificaciones de la Máxima Parsimonia ([bajar diapositivas aquí](/clase_5/Clase_5.pdf)) y termina con una práctica computacional de inferencia filogenética con Máxima Parsimonia usando el paquete Phangorn de R. 

**[IR AL TALLER OPCIONAL DE TNT](/clase_5/Taller_TNT.md)**

**[IR AL SCRIPT DE R](/clase_5/parsimonia.R)**. Para ejecutar este escript deben guardar el siguiente archivo con el nombre "ADN.nex" usando un editor texto: (ir al archivo: [ADN.nex](/clase_3/ADN.nex)).

**NOTA:** Para la clase del martes leer:

[Baum & Smith (2013)](/clase_5/baumsmith2013_ML.pdf)(Texto en inglés) **o** [Abascal et al (2014)](/clase_5/ML_Espanol.pdf) (Texto en español)

#

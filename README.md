<img src="https://github.com/jzavalar/2211088-informatica/blob/main/conjunto-baseIzt.png" alt="UAM Iztapalapa" width="60%"/>

## Programa Analítico de la UEA An (Teoría y Práctica)
## Licenciatura en Administración

**Clave de la UEA:** *2211092*, **Grupos:** *HE11* y *HE12*, **Trimestre:** *22-I*

**Horario:** *Lunes y miércoles* de *12:00 a 14:00* (**Grupo:** *HE11*) y de *16:00 a 18:00* (**Grupo:** *HE12*).

**Salón:** Transmisión de la clase *vía remota* por [Telegram](https://telegram.org/apps) a través del canal privado respectivo.

**Asesorías:**  *Martes* de *20:00* a *22:00 hr*, vía [Telegram](https://telegram.org/apps), previa solicitud.

**Profesor:** *dr. Jesús Zavala Ruiz*

**Contacte al profesor**:
- Correo electrónico: [jzr@xanum.uam.mx](mailto:jzr@xanum.uam.mx)
- Telegram: <img src="https://github.com/jzavalar/2211088-informatica/blob/main/telegram_logo.svg" alt="Telegram" width="3%"/> [@jzavalar](https://telegram.me/jzavalar)


### Introducción

Afines de los años 1930s, a solicitud del gobierno británico, el profesor P.M.S. Blackett y su equipo de científicos e ingenieros desarrollaron métodos para “resolver problemas técnicos relacionados con el desarrollo de nuevas armas y equipo durante la Segunda Guerra Mundial” (Jaiswal, 1997, p. 2)[^1], con un enfoque hacia problemas técnicos operativos (p. 4). Según, este autor, después de la Segunda Guerra Mundial, los científicos e ingenieros asociados con el profesor Blackett pasaron de la industria militar a los sectores civiles como el transporte, la salud y la industria, convencidos de que podían analizar esas operaciones con las mismas herramientas analíticas (p. 4).

Así surgió la **investigación de operaciones** (*operations research*) que se concibió como una "colección de herramientas y técnicas que podían utilizarse para mejorar sistemas bajo el control de un encargado independientemente de su campo de la actividad" (idem). El arsenal metodológico y computacional de la posguerra incluyó la programación lineal, la teoría de juegos, la programación dinámica, la simulación de eventos discretos con la computadora digital, adicionalmente a las teorías de inventarios y colas, el modelado de Markov y los métodos básicos de optimización. Actualmente, la *investigación de operaciones* se define como "la aplicación de los métodos de la ciencia a problemas complejos que se presentan en la dirección y la administración de grandes sistemas de hombres, máquinas, materiales y dinero, en la industria, los negocios, el gobierno y la defensa" (Gass y Fu, 2013, p. viii) [^2]; aunque también se define como “la ciencia de decidir cómo obtener el mejor diseño y cómo operar los sistemas hombre-máquina” y como “un método científico para proveer de los departamentos ejecutivos una base cuantitativa para la toma de decisiones” (idem).

La investigación de operaciones derivó en el ‘*análisis de sistemas*’ asociado a la *toma de decisiones*, considerada para entonces como “el examen sistemático de las distintas alternativas” (Hitch, 1955, p. 477)[^3] que se atribuyó como competencia de los gerentes (*managers*). En cambio, el llamado '*análisis puro'* estaba relacionado con la logística oper^ativa y era realizado por los 'técnicos' (*technicians*) o analistas (*analysts*). Así, el *análisis de sistemas* se puede considerar como “un enfoque sistemático para ayudar a un tomador de decisiones (*decision maker*) que elija un curso de acción, investigando su problema completo, buscando objetivos y alternativas y comparándolas considerando sus consecuencias, usando un marco de referencia apropiado -tan analítico como sea posible- para invocar el juicio y la intuición de expertos sobre el problema" (Jaiswal, 1997, p. 5). Esta definición sugiere que debe considerarse que *un ciclo de toma de decisiones* consiste desde "la definición de los objetivos, la exploración de las alternativas y su evaluación en términos de sus costos(/beneficios) y eficacia” (idem).

Desde los años 1950s, el concepto de *análisis de sistemas* ha permanecido, hasta nuestros días, asociado a la ‘toma de decisiones’, a la ‘administración de proyectos’ y otras disciplinas, siempre persiguiendo el mismo objetivo: *decidir racionalmente ante la incertidumbre*. Como consecuencia, surgieron las *ciencias de la administración* como un enfoque interdisciplinario que pasó de la eficiencia técnica a la eficacia de los sistemas sociotécnicos. Formalmente, la *ciencia de la administración* (*management science*) se define como la "aplicación de la metodología o los principios científicos a las decisiones administrativas" y el "uso de métodos cuantitativos para resolver problemas de decisiones gerenciales y de organización" (Gass y Fu, 2013, p. viii). En ese sentido, la ciencia de la administración es una expresión más de la teoría de la elección racional (*rational choice*) que Herbert A. Simon (1959)[^4] concibió como un comportamiento bajo una racionalidad limitada.
^
En 1961 se institucionalizó la *investigación de operaciones y el análisis de sistemas* (*Operations Research and Systems Analysis, ORSA*) y, para 1967, la investigación de operaciones se atribuía a sí misma como objetivo la toma de decisiones (cf. Beer, 1967)[^5] y el *análisis de sistemas* se convirtió, *de facto*, en *análisis de decisiones*, sin usar ese término. Así, la ciencia de la administración se convirtió en una confluencia interdisciplinaria, que algunos autores como Witzel (2012)[^6] consideran que si bien surgió como disciplina del conocimiento en la década de 1950s, con la expansión del pensamiento administrativo a nivel mundial, es la consecuencia de la evolución del pensamiento de la Administración Científica (*Scientific Management*), propuesta por Frederick. W. Taylor a principios del siglo XX.

Desde la década de 1970, la toma de decisiones agrupó las más diversas disciplinas, como las matemáticas, la sociología, la economía y la ciencia política (Buchanan y O’Connell, 2006, p. 32)[^7], así como las ciencias de la computación en la forma de la *teoría de la información*, la *cibernética*, la *inteligencia artificial* y el *pensamiento sistémico*. Así, las ciencias de la computación y la estadística fortalecieron el desarrollo de la investigación de operaciones dando origen al término *análisis de decisiones* (*decision analysis*), que alcanzó su auge en la década de 1980s.

En la actualidad, el **análisis de decisiones se considera**: (1) un **campo multidisciplinario** o una *rama de la investigación de operaciones* que “usa las matemáticas aplicadas y el razonamiento científico para encontrar soluciones óptimas a problemas complejos” (Chen, Schauver y Chunk, 2009, p. 983)[^8], es decir, a problemas que involucran múltiples variables, objetivos, incertidumbres y restricciones, pero también múltiples involucrados (*stakeholders*) y tomadores de decisiones; (2) una **herramienta metodológica** que “permite la evaluación cuantitativa de la toma de decisiones bajo condiciones de incertidumbre” (idem); (3) una **filosofía** o **postura epistemológica** que pretende responder a preguntas tales como las siguientes “¿Cómo deben evaluarse las opciones cuando las consecuencias son inciertas? ¿Cuándo se tiene suficiente información para tomar una decisión? ¿Cuánto se debe pagar por nueva información que reduzca la incertidumbre? ¿Cuál es el nivel de riesgo ‘correcto’?” (Call y Miller, 1990, pp. 116, 115)[^9].

La UEA *Análisis de Decisiones* se enfoca en desarrollar las habilidades de *pensamiento estratégico cuantitativo* indispensables para la toma de decisiones complejas. Esta UEA es parte del paquete de UEA cuantitativas de la Licenciatura en Administración y la primera de aplicación específica a la toma de decisiones. Estas habilidades van de la mano con el uso de computadoras digitales y software especializado, para que se percaten de la importancia que tiene en la administración de las empresas privadas, la administración pública y las organizaciones, en general.

[Programa vigente](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2211092pe.pdf).
[Programa vigente de la UEA prerrequisito UEA Estadística I](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2132044pe.pdf).

[Calendario UAM vigente](http://www.uam.mx/calendario/index.html).


### Objetivos 

#### Objetivo General:
Que al final del curso los alumnos sean capaces de:
- Comprender a la toma de decisiones como un proceso sistematizado con un enfoque sistémico.
- Identificar a la toma de decisiones como una forma equivalente de solucionar problemas en la administración.

#### Objetivos Específicos:
Que al finalizar el curso el alumno sea capaz de:
- Realizar la estructuración de problemas de decisión en la administración, seleccionar y aplicar en problemas de administración el modelo de decisión.
- Buscar y ponderar información relevante en fuentes diversas.
- Argumentar una propuesta crítica sobre un tema específico.


### Contenido Sintético

#### Unidad 0. Presentación
1. Presentación del programa
2. Evaluación Global y de Recuperación
3. Programa oficial vigente de la UEA ([pdf](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2211092pe.pdf)) y Programa oficial vigente de la UEA prerrequisito: [Estadística I](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2132044pe.pdf)
4. Acceso a nueva plataforma de [Virtuami](http://virtuami.izt.uam.mx/aulas/apresencial2)
5. Prácticas:
    - *Práctica 0.1: Bases de trabajo colaborativo con Google Drive* (Demostrativa online).
   
      *Objetivo*: Aprender las operaciones con archivos y directorios en Google Drive, como un ejemplo de plataformas de cómputo en la nube.
   
      Cree la estructura de directorios en [Google Drive](https://drive.google.com/drive/my-drive) para la entrega de controles de lectura, prácticas y proyecto final de acuerdo a un sistema de organización de archivos ([guía](https://www.youtube.com/watch?v=duNwB8xt2_w)). ([tutorial](https://www.youtube.com/watch?v=I3jii6ltINY&frags=pl%2Cwn)).

    - *Práctica 0.2: Instalación de software para grabación de audio y video* (Demostrativa online).
   
      *Objetivo*: Aprender a descargar e instalar un software para grabar video y una para audio y aprender a buscar tutoriales en YouTube para utilizarlo.
   
      *Parte 1*. Instale [vokoScreenNG](https://linuxecke.volkoh.de/vokoscreen/vokoscreen-download.html) o instale la aplicación de su preferencia.
          - Primero instale los prerrequisitos (vea [aquí](https://github.com/vkohaupt/vokoscreenNG): [codec pack](https://www.windows10codecpack.com/) y [GStreamer](https://gstreamer.freedesktop.org/pkg/windows/1.14.4/gstreamer-1.0-x86-1.14.4.msi); alternativamente, puede usar estos [codecs](https://codecguide.com/download_kl.htm)).
          - Alternativamente, puede usar [Open Broadcaster Software (OBS Studio)](https://obsproject.com/es)) (grabación, edición y transmisión de video) ([tutorial](https://www.youtube.com/watch?v=qLuSrSiC9Xc)), si los recursos de su computadora lo permiten.  
   
      *Parte 2*. Grabe su pantalla y capture la toma de la cámara y hable sobre las expectativas que tiene del curso usando el software (ver [tutorial](https://www.youtube.com/watch?v=mh5qV2iAiVs)). Puede agregar algún fondo musical.  
   
       Busque en YouTube los tutoriales que le sirvan para completar la práctica con éxito.
   
       Al terminar suba sus videos y su audio a su Google Drive donde corresponda, según la estructura de directorios de la Práctica 0.1.

    - *Práctica 0.3: Instalación de software libre, abierto y privativo* (Demostrativa online).
   
      *Objetivo*: Aprender a descargar e instalar aplicaciones portables en una USB y en computadora.
   
      *Parte 1*. Active su cuenta de [Office 365 Pro Plus](http://www.uam.mx/o365/) (software de oficina) e instale su copia de [Office Pro](http://www.uam.mx/ti/soft/microsoft.html) (software de oficina) (documente el proceso).
   
      *Parte 2*. Si tiene computadora en casa, descargue en instale el siguiente software: [*7-zip*](https://www.7-zip.org/download.html) (compresor/descompresor), *CMapTools* ([mapas conceptuales](https://cmap.ihmc.us/)), [*ClamWin*](http://www.clamwin.com/) (antivirus), [*LibreOffice*](https://www.libreoffice.org/) (suite de oficina) (edite un documento PDF), [*R*](https://www.r-project.org/) (estadística), [*RStudio*](https://www.rstudio.com/) (estadística).
   
      *Parte 3*. Para la práctica requiere una USB de por lo menos 4 Gb, misma que utilizará para varias prácticas posteriores. Descargue e instale [*PortableApps*](https://portableapps.com/) ([tutorial 1](https://www.youtube.com/watch?v=Ux_3p4lDmTg), [tutorial 2](https://www.youtube.com/watch?v=Ux_3p4lDmTg)) en su USB vacía. 
   
      (N. B: Desactive su antivirus para realizar la práctica y usar *PortableApps*. [guía](https://www.youtube.com/watch?v=HDEhLpS7UwM)).
   
      *Parte 4*. Descargue e instale [Firefox](https://portableapps.com/apps/internet/qbittorrent_portable) desde PortableApps ([tutorial](https://www.youtube.com/watch?v=zzq2kDEsiAs)) o localícela y descárguela desde la [lista de aplicaciones](https://portableapps.com/apps). En seguida, instale el plugin de bloqueo de publicidad, por ejemplo Ghostery y otros ([tutorial](https://www.youtube.com/watch?v=g3Dw_7085r8)).
   
      *Parte 5*. Descargue e instale el siguiente software portable en una USB: *LibreOffice* (suite de oficina) ([portable](https://portableapps.com/apps/office/libreoffice_portable)), *7-zip* (compresor/descompresor) ([portable](https://portableapps.com/apps/utilities/7-zip_portable)), [*R Portable*](https://sourceforge.net/projects/rportable/files/R-Portable/)) (estadística) y [*RStudio Portable*](https://sourceforge.net/projects/rportable/files/R-Studio/) (estadística).

      ##### *Bibliografía Complementaria:*
         - Ibiza, D. (2018, Apr 3). 1. Introducción a *Google Drive*: Primeros pasos ([tutorial](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=330s)), 2. Gestión de archivos y carpetas ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=2042s)), 3. Opciones de archivos y carpetas ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=3313s)), 4. Cómo compartir archivos y carpetas ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=4238s)), 5. Trabajar con documentos ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=5222s)) . In Tutorial Google Drive | Completo | Principiantes | Paso a Paso. YouTube. (video). ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk)).
        - Universitat de les Illes Balears. Som UIB (2021). MOOC Aprende R : Introducción al tratamiento de datos con R y RStudio. *YouTube*. ([url](https://www.youtube.com/playlist?list=PLnXFIHWLWQXFOIOdpAv2ioBHQuYgV7x2t)).
        - Alva Majo. (2018, Jul 11). Aprende a programar en 11 minutos. *YouTube* [video]. (12:32 min). ([url](https://www.youtube.com/watch?v=TAyyujKoY6k)). (Lectura 2.1.)


#### Unidad 1. Presentación
1. Introducción
2. La ciencia de la administración y la toma de decisiones
3. Contexto histórico del análisis de decisiones
4. Prácticas:  
    - *Práctica 1.1: Preparación de RStudio Cloud*.  
  
      *Objetivo*: Aprender a preparar el entorno de *RStudio Cloud* para generar un libro *RMarkdown*.  
  
      Cree su cuenta en [RStudio cloud](https://rstudio.cloud/). Luego, descargue los [archivos fuente](https://github.com/CerebralMastication/R-Cookbook/) desde *GitHub* del libro [*R Cookbook*](https://rc2e.com/). Copie el archivo comprimido (.zip) de su computadora a su propio proyecto *R Cookbook* en su cuenta de *RStudio cloud*. Una vez descomprimido, mueva todos los archivos a la raíz del proyecto. Finalmente, instale todos los paquetes necesarios, de manera progresiva, a partir de la ejecución del archivo *index.Rmd*, hasta que ya no haya errores y regenere en su propia copia del libro.  
  
      Esto le permitirá ejecutar el código fuente de las recetas del libro, hacer las modificaciones que requiera y usarlas para sus propias necesidades.  
  
      Por último, haga un video tutorial grabando la pantalla de su equipo con [Vokoscreen-NG](https://linuxecke.volkoh.de/vokoscreen/vokoscreen.html) conforme vaya realizando su práctica hasta que haya cumplido el objetivo. Suba su video a su cuenta de Google Drive donde corresponda y al chat de Telegram con el profesor. 
  
    - *Práctica 1.2: Fundamentos de R*.  
  
      *Objetivo*: Aprender a usar el código fuente de los ejemplos de un libro de R en el entorno de *RStudio Cloud*.  
  
      Localice el código fuente del libro *R in a Nutshell* [pdf](https://www.guianaplants.stir.ac.uk/seminar/resources/R_in_a_Nutshell_Second_Edition.pdf) y [cargue el paquete](https://learning.oreilly.com/library/view/r-in-a/9781449377502/pr03s04.html) correspondiente. Alternativamente, descargue el [código fuente](https://resources.oreilly.com/examples/9780596801717) desde el sitio del editor y úselo en su proyecto. Luego, pruebe los ejemplos del Capítulo 3. Pruebe variaciones del código hasta que comprenda la lógica de funcionamiento de cada ejemplo y pueda usarlo para sus propias necesidades.
  
      Estudie las convenciones de [codificación para R de Google](https://google.github.io/styleguide/Rguide.html) para que escriba código R de manera clara y eficaz, al modificar sus ejemplos.  
  
      Por último, haga un video tutorial grabando la pantalla de su equipo conforme vaya realizando su práctica hasta que haya cumplido el objetivo. Suba su video a su cuenta de Google Drive donde corresponda y al chat de Telegram con el profesor.   

    - *Práctica 1.3. Bases de datos I: Bases de datos pequeñas*. (Entrega: 18 de marzo de 2022). 

      *Objetivo*: Aprender los principios de una base de datos y usar tablas dinámicas y filtros para la resolución de preguntas cuantitativas.
    
      *Parte 1*. Desde el sitio web del Inegi, del [Censo Nacional de Población y Vivienda del INEGI](https://www.inegi.org.mx/programas/ccpv/2010/), descargue el [Cuestionario Básico](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cpv2010_cuest_basico_d.pdf), la [Descripción de la Base de Datos](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/diccionario_cuestionario_basico.xls), una [muestra de la base de datos](https://www.inegi.org.mx/programas/ccpv/2010/), la [Síntesis Metodológica y Conceptual](http://internet.contenidos.inegi.org.mx/contenidos/Productos/prod_serv/contenidos/espanol/bvinegi/productos/metodologias/est/sm_cpv2010.pdf) y el [Cuestionario Ampliado](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cpv2010_cuest_ampliado_d.pdf).
    
      De la pestaña [Microdatos](https://www.inegi.org.mx/programas/ccpv/2010/#Microdatos), descargue la muestra de la Base de Datos de Personas ([dbf en zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/microdatos/ejemplobd/dummy_personas_cpv2010_dbf.zip)), Base de Datos de Viviendas ([dbf en zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/microdatos/ejemplobd/dummy_viviendas_cpv2010_dbf.zip)) y el Catálogo de la Integración General de Localidades (CIGEL) ([dbf en zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cigel_2010_hab_dbf.zip)) y los demás catálogos.
    
      También descargue el archivo [DUMMY_PERSONAS_5K.dbf.zip](https://drive.google.com/file/d/1TNXXZZQ9GEJKU8UD-YyuklF4a1E8w_0b/view?usp=sharing), que es una muestra muy pequeña de la base de datos, para realizar el ejercicio.
    
      *Parte 2*. En primer lugar, utilice *Calc* de *LibreOffice* ([ayuda](https://help.libreoffice.org/Calc/Importing_and_Exporting_dBASE_Files/es)) para abrir el archivo disponible del Inegi en el formato DBF y expórtelo a cualquier otro como XLSX, XLS o CSV. En segundo lugar, utilice el paquete [*rio*](https://cran.r-project.org/web/packages/rio/) en [*RStudio*](https://rstudio.com/) para abrir (importar / exportar) y convertir alguno de los archivos en los formatos disponibles del Inegi: DBF, SAS, SAV, DTA a cualquier otro como XLSX, XLS o CSV. Básese en [este script](https://drive.google.com/file/d/15W7CjN2TmjFo5OSXbbftaWCwm8DagNWo/view?usp=sharing) y adáptelo a su caso particular hasta que le funcione correctamente.
    
      *Parte 3*. Practique la consulta multidimensional de datos con la pequeña muestra de la base de datos descargada en la Parte 1 (DUMMY_PERSONAS_5K.dbf). Luego, revise la metodología y la solución en *Google Sheets* (en *Google Drive*) [aquí](https://drive.google.com/file/d/1Uqu6m_Fv1AqR5Nf8H_8JbffWmr_L01si/view?usp=sharing) y haga lo equivalente en *Excel* (*Microsoft Office*) y en *Calc* (*LibreOffice*).  
  
      Tome como base la siguiente pregunta compuesta:      
          - *¿Cuántos jefes de familia hay en la base de datos que son estudiantes y son menores de edad?* y  
          - *¿Cuál es su distribución por edad y sexo?*  
  
      *Tip*: Si bien, este problema puede resolverse aplicado filtros de manera consecutiva, también puede resolverse realizando una consulta a la base de datos mediante una tabla dinámica.  
  
      Saque sus conclusiones y documente su experiencia en la realización de la actividad en un video de hasta 10 minutos, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.

    - *Práctica 1.4. Base de datos II: Bases de datos geográficas*. (Fecha de entrega: 18 de marzo de 2022).  
  
      *Objetivo*: Crear un sistema de bases de datos geográficas con *PostgreSQL*, *R* y *QGIS*.  
  
      *Parte 1*. Instale [*PostgreSQL*](https://www.postgresql.org/), [*Stack Builder*](https://www.enterprisedb.com/edb-docs/d/postgresql/installation-getting-started/installation-guide-installers/11/PostgreSQL_Installation_Guide.1.09.html) y [*PostGIS*](https://www.postgis.net/) ([url](https://www.postgresql.org/download/windows/)), [*pgAdmin 4*](https://www.pgadmin.org/) en *Windows* ([guía](https://www.youtube.com/watch?v=bq9dOrwZ-KA)) y [*QGIS*](https://www.qgis.org/en/site/index.html) ([guía](https://www.youtube.com/watch?v=PG3Xmt3S9Ac)).      
  
      *Parte 2*. Cree un usuario del servidor *PostgreSQL* y conéctese al servidor ([guía](https://www.youtube.com/watch?v=jxIEDKzGrOs&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=1)).      
  
      *Parte 3*. Descargue los archivos de la base de datos geográfica ([url](http://s3.cleverelephant.ca/postgis-workshop-2018.zip)) ([tutorial *PostGIS*](https://postgis.net/workshops/postgis-intro/)). Cree una base de datos espacial ([guía](https://www.youtube.com/watch?v=UtiIY39qmhg)).      
  
      *Parte 4*. Use la aplicación *shp2pgsql* para importar los archivos shapefiles ([guía 1](https://postgis.net/workshops/postgis-intro/loading_data.html), [guia 2](https://www.youtube.com/watch?v=N_GvAi5RitM)) (si después de instalar *PostGIS* (en *Windows*), ocurre un error por la falta del archivo *libsqlite3-0.dll*, éste debe descargarse y copiarse al directorio base de la aplicación desde [aquí](https://www.pconlife.com/download/otherfile/35257/d56eb0e10349ffd8a57efb66d452d3a2/), por ejemplo, la [versión 64 bits](https://www.pconlife.com/download/otherfile/35257/d56eb0e10349ffd8a57efb66d452d3a2/)).      
  
      *Parte 5*. Conéctese a la base de datos desde *RStudio* y pruebe *R* con la base de datos ([guía](https://www.youtube.com/watch?v=-F5SpGhnNG8)).      
  
      *Parte 6*. Conéctese a la base de datos con *QGiS* y despliegue el mapa ([guía](https://www.youtube.com/watch?v=NYKHlSd932c)).  
      *Parte 7*. Respalde la base de datos ([guía](https://www.youtube.com/watch?v=icEvkyIXqug&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=66&t=0s)).  
  
      Busque en YouTube los tutoriales que le sirvan para completar la práctica con éxito o pruebe algún otro tutorial.      
  
      Saque sus conclusiones y documente en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  

      ##### *Bibliografía Obligatoria:*
         - Witzel, M. (2012). 9 From Scientific Management to Management Science. In *A history of management thought* (capítulo 9). London: Routledge. ([url](https://www.amazon.com/History-Management-Thought-Morgen-Witzel/dp/0415600588)) ([torrent](https://thepiratebay.org/description.php?id=7912663)) ([epub url](http://libgen.rs/book/index.php?md5=1F104CC3F1936AF817CC64261EBDB0DA)). (*Lectura 1.1.*).
         - Drucker, P. F. (1955). "Management Science" and the manager. *Management Science 1*(2), 115-126. doi: http://doi.org/10.1287/mnsc.1.2.115 ([pdf](http://libgen.rs/scimag/10.1287%2Fmnsc.1.2.115)). (*Lectura 1.2*).
         - Zavala, J. (2016). El análisis de decisiones: Un panorama histórico-metodológico. (Mimeo). (Disponible en el grupo de Telegram). (*Lectura 1.3*).  

      ##### *Bibliografía Obligatoria:*
         - Ensmenger, N. L. (2010). The *cosa nostra* of the data processing industry. In *The computer boys take over: Computers, programmers, and the politics of technical expertise* (pp. 137-161). USA: The MIT Press. ([pdf](https://www.mondotheque.be/wiki/images/0/0b/Ensmenger_The_Computer_Boys_Take_Over%28BookZZ.org%29.pdf)).


#### Unidad 2. La toma de decisiones y la teoría de la elección racional
1. ¿Qué es una decisión?
2. La toma de decisiones como proceso cibernético
3. Teoría de la elección racional
4. La racionalidad limitada
5. Tipos de problemas de decisión
6. Tareas y Prácticas:
    - *Tarea 2.1*: *Teoría de las bases de datos relacionales*. (Fecha de entrega: 25 de marzo de 2022).  

      Resuelva el siguiente cuestionario ([parte 1](https://drive.google.com/file/d/17IhZFgxB1XCeEYaJjTIJxKQQ-Rv1Vs2q/view?usp=sharing), [parte 2](https://drive.google.com/file/d/1zswLrAe5IBZXhq3YylAR5Sk_EhKdGiAH/view?usp=sharing), [parte 3](https://drive.google.com/file/d/1rdmW5IvGtipYRR4W8Yxhh8sbNOlB2ct2/view?usp=sharing)) en su cuaderno de apuntes para que refuerce la teoría, a partir de la siguiente [presentación](https://drive.google.com/file/d/1leDmRFqWQygcwnYro9315PeUGWjXIF0V/view?usp=sharing) sobre el tema.  
  
      Suba las fotos (legibles) de la tarea a su cuenta de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.  
  
      Saque sus conclusiones y documente en un video la realización de la tarea y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  
  
      **Bibliografía**: Quiroz, J. (2003). El modelo relacional de bases de datos. *Boletín de Política Informática (INEGI)*, (6), 53-61. ([pdf](http://ingenieriasimple.com/conred/el%20modelo%20relacional.pdf)). 

    - *Práctica 2.2. Base de datos III: SQL*. (Fecha de entrega: 25 de marzo de 2022).  
  
      *Objetivo*: Aprender las operaciones básicas de administración de bases de datos en *PostgreSQL* con *pgAdmin 4*.
  
      *Parte 1*: *Administración del servidor*. Utilice como base el [Curso de PostgreSQL](https://www.youtube.com/playlist?list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2), el [tutorial en línea](https://postgresqltutorial.com/) ([traducción](https://postgresqltutorial-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=en&_x_tr_pto=wapp)), principalmente la [administración de bases de datos](https://www.postgresqltutorial.com/postgresql-administration/) ([traducción](https://www-postgresqltutorial-com.translate.goog/postgresql-administration/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=en&_x_tr_pto=wapp)) o la [hoja de tips de PostgreSQL](https://www.postgresqltutorial.com/wp-content/uploads/2018/03/PostgreSQL-Cheat-Sheet.pdf).  
  
      Prerrequisitos: Debe completar la *Práctica 1.4.*.
  
      Conéctese al servidor de base de datos *PostgreSQL* ([guía](https://www.youtube.com/watch?v=jxIEDKzGrOs&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=1)) con [pgAdmin 4](https://www.pgadmin.org/). (Tip: Para usar pgAdmin 4 para restaurar y respaldar bases de datos, debe configurar la ruta de ubicación del servidor (*Binary PATH*) de los archivos ejecutable (C:\Program Files\PostgreSQL\14\bin) en las preferencias de pgAdmin 4.)
  
      *Parte 2*: *Operaciones de administración de la base de datos*. 
  
      Crear una base de datos ([guía](https://www.youtube.com/watch?v=GruJjmfm_gs&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=3)). Crear una tabla tal como se ve en la [guía](https://www.youtube.com/watch?v=LIUW0XWdy80&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=5&t=0s). Identifique el tipo de dato que requiere para cada columna ([guía](https://www.youtube.com/watch?v=9IEQKbItnCE&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=8&t=0s)). Modificar la tabla para alojar una lista de personas (nombre, apellido materno y paterno y su edad ([guía](https://www.youtube.com/watch?v=eEbqN7Hz7FM&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=13&t=0s)).  
  
      Ingresar siete registros ([guía](https://www.youtube.com/watch?v=nsU3IwSASDg&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=6&t=0s)) (Tip: Considere una llave primaria con autoincremento numérico ([guía](https://www.youtube.com/watch?v=210SPHcrWr8&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=15&t=0s)). Eliminar dos registros ([guía](https://www.youtube.com/watch?v=eJQCl5zIknA&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=11&t=0s)). Actualizar los registros cambiando los datos de la tabla ([guía](https://www.youtube.com/watch?v=2EN1amBNZvQ&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=7&t=0s)).  
  
      Modificar la tabla para alojar a la lista de personas su correo electrónico ([guía](https://www.youtube.com/watch?v=eEbqN7Hz7FM&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=13&t=0s)).  
  
      Modificar una columna para que acepte valores nulos y cambiar el tipo de dato, según la [guía](https://www.youtube.com/watch?v=sKWCb_ZEzoM&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=14&t=0s).  
  
      Exportar la tabla a un archivo CVS ([guía](https://www.youtube.com/watch?v=Lk5L58uIzm4&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=66)). Eliminar la tabla creada ([guía](https://www.youtube.com/watch?v=Lk5L58uIzm4&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=66)). Importar la tabla exportada ([guía](https://www.youtube.com/watch?v=w9kibRWlQQg)).  
  
      Respaldar (exportar) la base de datos ([guía](https://www.youtube.com/watch?v=icEvkyIXqug&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=66&t=0s)). Luego, eliminar la base de datos ([guía](https://www.youtube.com/watch?v=iqRathev-Zw&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=4&t=0s)). Finalmente, restaurar ([importar](https://www.youtube.com/watch?v=icEvkyIXqug&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=66&t=0s)) la base de datos ([guía](https://www.youtube.com/watch?v=icEvkyIXqug&list=PL8gxzfBmzgex2nuVanqvxoTXTPovVSwi2&index=66&t=0s)) que respaldó.  
  
      Para cada operación documente el script o las instrucciones que permiten su ejecución.  
  
      Repita y practique las operaciones hasta que entienda su lógica. Reflexione sobre lo aprendido en la práctica.
  
      *Parte 3*. Finalmente, pruebe restaurar la [base de datos de prueba *DVDrental*](https://www.postgresqltutorial.com/postgresql-sample-database/) descargando el ([archivo zip](https://sp.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)) que le permitirá poder probar todas las operaciones del [Tutorial](). Apóyese en el diagrama entidad-relación ([pdf](https://sp.postgresqltutorial.com/wp-content/uploads/2018/03/printable-postgresql-sample-database-diagram.pdf)) y la ([guía](https://www.postgresqltutorial.com/postgresql-sample-database/)). Siga el procedimiento para cargar la base de datos según el siguiente [tutorial](https://www.postgresqltutorial.com/load-postgresql-sample-database/) o este [otro tutorial](https://www.postgresqltutorial.com/postgresql-restore-database/) para restaurarla. **Tenga cuidado. Restaure en la base de datos correcta.** 
  
      Una vez restaurada la bases de datos, practique los comandos *psql* y las operaciones de consulta en una terminal y con *pgAdmin 4*, con ayuda de la hoja de tips ([cheat sheet](https://www.postgresqltutorial.com/postgresql-cheat-sheet/)).
  
      Entregue reporte de la práctica elaborando un video de cada operación narrando lo que muestra el video, tipo tutorial. Incluya los *scripts* en *SQL* que permiten realizar cada operación, identificando con precisión cada una.  
  
      Busque en YouTube los tutoriales que le sirvan para completar la práctica con éxito o pruebe algún otro tutorial.  
  
      Saque sus conclusiones y documente en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  
  
    - *Tarea 2.3*: *Cuestionario*. (Fecha de entrega: 30 de marzo de 2022).  

      *Objetivo*: Aprender el lenguaje de uso en la unidad.
  
      Resuelva el siguiente [cuestionario](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad%202.%20Cuestionario.md) en su cuaderno de apuntes, para que refuerce la teoría sobre el tema de la Unidad.  
  
      Suba las fotos (legibles) de la tarea a su cuenta de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.  
  
      Saque sus conclusiones y documente en un video la realización de la tarea y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  

      ##### *Bibliografía Obligatoria:* 
         - Pérez, D. (2013). Elección racional. *YouTube*. ([Video 2.1](https://www.youtube.com/watch?v=tPj2sEBdB3s)) (10:51 min). (Identificar los postulados básicos de la elección racional).  
         - - Simon, H. A. (2016/1992). Why decision making is so difficult. *YouTube*. ([Video 2.2](https://www.youtube.com/watch?v=eTXkZURBq7k&list=PL1s8eXa4Q_bjXPayLmo1Hbq5cJLzcwZz7&index=3)). (2:19 min). (Identificar la complejidad de la toma de decisiones).
         - Elster, J. (2013). Racionalidad e interés: Tratado de hombre económico contemporáneo. ([Video 2.3](https://www.youtube.com/watch?v=aBfrWUXI9ns)). (1:11:34 hr). (Identificar los postulados de la teoría de la racionalidad limitada, sus éxitos y fracasos).  
         - Sun Tzu. *El arte de la guerra*. *YouTube*. ([Video 2.4](https://www.youtube.com/watch?v=tp8-VK56O90)). (1:30:38 hr).  
         - Simon, H. A. (1955). A behavioral model of rational choice, *The Quarterly Journal of Economics, 69*(1), 99-118. ([pdf](https://www.suz.uzh.ch/dam/jcr:ffffffff-fad3-547b-ffff-fffff0bf4572/10.18-simon-55.pdf)). (*Lectura 2.5*).  
         - Simon, H. A. (2000). Bounded rationality in social science: Today and tomorrow. *Mind & Society, 1*(1), 25-39. ([pdf](http://ipwna.ir/wp-content/uploads/2018/08/Bounded_rationality_in_social_Today-and-Tomorrow-irpublicpolicy.pdf)). (*Lectura 2.6*). 
         - Cameron, S. (2002). Tools of the trade: Rational choice.  In *The economics of sin: Rational choice or no choice at all?* (pp. 14-39). Cheltenham, Glos, U.K.: Edward Elgar Publishing. ([url](http://libgen.rs/search.php?req=The+economics+of+sin%3A+Rational+choice+or+no+choice+at+all%3F&open=0&res=100&view=simple&phrase=1&column=title)) (*Lectura 2.7*). (Identificar los postulados de la teoría de la racionalidad limitada).  

      ##### *Bibliografía Complementaria:*
         - Foucault, M. (1988). El sujeto y el poder. *Revista Mexicana de Sociología, 50*(3) (Jul - Sep), 3-20. ([pdf](https://perio.unlp.edu.ar/catedras/cdac/wp-content/uploads/sites/96/2020/03/T-FOUCAULT-El-sujeto-y-el-poder.pdf)).  
         - Cabantous, L. y Gond, J-P. (2010). Rational decision making as performative praxis: Explaining rationality's Éternel Retour. *Organization Science,22*(3), 573-586. ([pdf](https://openaccess.city.ac.uk/id/eprint/6929/1/)).  
         - Kurtz, C. F. y Snowden, D. J. (2003). The new dynamics of strategy: Sense-making in a complex and complicated world. *IBM Systems Journal, 42*(3), 462-483. ([pdf](https://www.researchgate.net/publication/3228283_The_new_dynamics_of_strategy_Sense-making_in_a_complex_and_complicated_world)).  
         - Novikov, D.A. (2016). *Cybernetics: From past to future*. Springer. ([url](http://libgen.rs/book/index.php?md5=C3E6D1E999983C24D496BE7CC10A69F5)).  
         - New Economic Thinking (2015). The death of ‘*Homo economicus*’. *YouTube*. ([Video](https://www.youtube.com/watch?v=ParPPYMzfQM)). (20:29 min).  
         - Searle, J. R. (2003). The classical model of rationality and its weaknesses. In (auth.) *Rationality in action* (pp. 1-32). Cambridge: The MIT Press. ([url](http://libgen.rs/book/index.php?md5=AE2CE1B934DFC35B2B1D8B12D2BEC6D3)).

 
#### Unidad 3. El análisis de decisiones
1. ¿Qué es el análisis de decisiones?
3. Alcances y limitaciones del análisis de decisiones
4. Herramientas analíticas del análisis de decisiones
5. Tareas y prácticas:
    - *Práctica 3.1*: *Operaciones matriciales con R y aplicaciones*. (Fecha de entrega: 10 de abril de 2022).
  
      *Objetivo*: Realizar un recordatorio sobre los vectores, las matrices y sus operaciones, usando R, como preparación para su aplicación en la programación lineal.  

      *Parte 0. Preparación*. Previamente debe abrir su cuenta en [RStudio.cloud](https://rstudio.cloud/). En su proyecto de la UEA, cree un folder con el nombre la práctica, para que ahí genere sus archivos correspondientes.  
  
      *Parte 1. Vectores en R*. Convierta el siguiente tutorial sobre [Vectores en R](https://r-coder.com/vectores-r/) en un archivo RMarkdown (.Rmd) y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final, escriba sus propias conclusiones.  
  
      *Parte 2. Matrices en R*. Convierta el siguiente tutorial sobre [Matrices en R](https://r-coder.com/matrices-r/) en un archivo RMarkdown (.Rmd) y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.  
  
      *Parte 3. Operaciones con Matrices en R*. Convierta el siguiente tutorial sobre [Operaciones con Matrices en R](https://r-coder.com/operaciones-matrices-r/) en un archivo RMarkdown (.Rmd) y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.
  
      *Parte 4. Métodos cualitativos para el Análisis de decisiones*. Considere el siguiente video sobre *[Métodos Cualitativos para el Análisis de Decisiones](https://www.youtube.com/watch?v=Vz2Uiy67cm0)* y, a partir de lo que aprendió en las primeras partes, conviértalo en un archivo RMarkdown (.Rmd) con la receta de la solución y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.  
  
      *Parte 5. Método del Valor Esperado*. Considere el siguiente video sobre *[Metodo del Valor Esperado para el Análisis de Decisiones](https://www.youtube.com/watch?v=d2D8aUZHAWs)* y, a partir de lo que aprendió en las primeras partes, conviértalo en un archivo RMarkdown (.Rmd) con la receta de la solución y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.
    
      Suba los archivos de la práctica a su cuenta de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Saque sus conclusiones y documente en un video la realización de la tarea y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  

    - *Tarea 3.2*: *Fundamentos del análisis de decisiones*. (Fecha de entrega: 17 de abril de 2022).  

      *Objetivo*: Aprender los fundamentos del análisis de decisiones.  

      Resuelva el siguiente [cuestionario](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad%203.%20Cuestionario.md) sobre los *fundamentos del análisis de decisiones*.
  
    - *Práctica 3.3. Manipulación de datos con R*. (Fecha de entrega: 24 de abril de 2022).  

      *Objetivo*: Aprender la limpieza y manipulación de datos con R para el análisis de datos.  

      *Parte 0*: Organícense en parejas.  
  
      *Parte 1*: Estudie la [Transformación de datos](https://es.r4ds.hadley.nz/transform.html#transformaciones-agrupadas-y-filtros) y resuelva los [ejercicios respectivos](https://es.r4ds.hadley.nz/transform.html#transformaciones-agrupadas-y-filtros) mediante la elaboración de un archivo RMarkdown.  

      *Parte 2*: Estudie los principios de la [Ordenación de datos](https://es.r4ds.hadley.nz/datos-ordenados.html) con el paquete *tidyverse* y resuelva los ejercicios del capítulo (12.2.1, 12.3.3, 12.4.3, 12.5.1, 12.6.1) mediante la elaboración de un archivo RMarkdown.  

      Suban los archivos de la práctica, creados o modificados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Saquen sus conclusiones y documenten en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial y compartan el video en el grupo de Telegram.

    - *Práctica 3.4. Manipulación de datos relacionales con R*. (Fecha de entrega: 24 de abril de 2022).  

      *Objetivo*: Aprender la manipulación de datos relacionales con R, como aproximación a las bases de datos relacionales.  

      *Parte 0*: Organícense en parejas.  
  
      *Parte 1*: Prerrequisitos: Debe haber realizado las primeras dos partes de esta práctica y haber resuelto la *Tarea 2.1: Teoría de las bases de datos relacionales*.  
  
      *Parte 2*: Estudie los principios de manejo de [Datos relacionales](https://es.r4ds.hadley.nz/datos-relacionales.html) y resuelva los ejercicio del capítulo (13.2.1, 13.3.1, 13.4.6, 13.5.1) mediante la elaboración de un archivo RMarkdown.  

      Suban los archivos de la práctica, creados o modificados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Saquen sus conclusiones y documenten en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial y compartan el video en el grupo de Telegram.

    - *Práctica 3.5. Optimización con R*. (Fecha de entrega: Ninguna, pues es opcional).  

      *Objetivo*: Aprender el procedimiento general de resolución de problemas de programación lineal con R.  

      *Parte 0*: Organícense en parejas.  
  
      *Parte 1*: Repase la teoría de optimización matemática de la *programación lineal* usando R en este tutorial-ejemplo de *Optimización en R* de [Chung (2020, Jun 23)](https://rpubs.com/vchung/programacion), en este otro tutorial sobre *Optimización Lineal con R* de [Berrendero (2015)](https://caminosaleatorios.files.wordpress.com/2015/03/optimizacion-lineal-r.pdf) y el tutorial sobre *Calculadoras de Optimización* o (*Solvers*) de [Palomar (2020)](https://palomar.home.ece.ust.hk/MAFS6010R_lectures/Rsession_solvers.html), donde también encontrará soluciones para otras técnicas como *mínimos cuadrados*, *programación entera*, *programación cuadrática* y *programación mixta*, entre otros. 
  
      *Parte 2*: Aparte de los paquetes [lpSolve](https://cran.r-project.org/web/packages/lpSolve/index.html) y [lpSolveAPI](https://cran.r-project.org/web/packages/lpSolveAPI/index.html), es de particular interés el paquete [R Optimization Infrastructure (ROI)](https://roi.r-forge.r-project.org/) porque es la solución de optimización más completa disponible actualmente en R. 
  
      *Parte 3*: Enfóquese en aprender:   
          a. A utilizar la codificación en LaTEX para escribir ecuaciones, matrices y símbolos matemáticos (ver [Editor Online](https://latex.codecogs.com/eqneditor/editor.php)),  
          b. La codificación de vectores y matrices para reolver los problemas de optimización con los paquetes *lpSolve*, *lpSolveAPI* y *ROI* de R con RStudio,  
          c. La graficación simple con R apoyándose en el tutorial de [Alegre Ordoñez (2019, Mar 7)](http://rstudio-pubs-static.s3.amazonaws.com/474421_3dfcb62391eb4ac495a863dea86121d9.html), y  
          d. Reproduzcan los ejercicios respectivos, comprobando la validez y documenten el algoritmo en una compilación en un archivo *RMarkdown*.  

      *Parte 4*: Explore y exponga algunos de los problemas representativos de su carrera que podría resolver utilizando estas técnicas y saquen sus conclusiones.   

      Suban los archivos de la práctica, creados o modificados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Documenten en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial y compartan el video en el grupo de Telegram.

      ##### *Bibliografía Obligatoria:*
         - Mote, V. L. y Meenakshi Malya, M. (1970). Decision analysis: Experiences and expectations. *Economic and Political Weekly, 5*(22), M53+M55+M57-M58. ([url](https://www.jstor.org/stable/4360049)) ([pdf](https://sci-hub.se/10.2307/4360049)). (Lectura 3.1).  
         - Goodwin, P. y Wright, G. (2004). Introduction. In *[Decision analysis for management judgment](http://libgen.rs/book/index.php?md5=3B2F1C8F5947F079F9064CA6BAA7031B)* (pp. 1-13). Chichester, West Sussex, England: John Wiley & Sons. (Lectura 3.2).  
         - Howard, R. A. (1988). Decision analysis: practice and promise, *Management Science, 34*(6), 679-695. ([url](https://www.jstor.org/stable/2632123)) ([pdf](https://sci-hub.se/10.2307/2632123)). (Lectura 3.3).  
         - Howard, R. A. (1968). The foundations of decision analysis. *IEEE Transactions on Systems Science and Cybernetics, 4*(3), 211-219. ([url](https://ieeexplore.ieee.org/abstract/document/4082150)) ([pdf](https://sci-hub.se/10.1109/TSSC.1968.300115)). (Lectura 3.4).  

      ##### *Bibliografía Complementaria:*
         - Garber, R. (2009). An interview with Ronald A. Howard. *Decision Analysis, 6*(4), 263–272. ([url](https://pubsonline.informs.org/doi/pdf/10.1287/deca.1090.0160)) ([pdf](https://sci-hub.se/10.1287/deca.1090.0160)).  
         - Goodwin, P. y Wright, G. (2003). How the people make decisions involving multiple objectives. In *[Decision analysis for management judgment](http://libgen.rs/book/index.php?md5=3B2F1C8F5947F079F9064CA6BAA7031B)* (pp. 14-26). Chichester, West Sussex, England: John Wiley & Sons.  
         - Howard, R. A. (1966). *Decision analysis: Applied decision theory*. ([pdf](http://www.sdg.com/wp-content/uploads/2015/06/Decision-Analysis-Applied-Decision-Theory.pdf)).  
         - Ralph L. Keeney, R. L. (1982). Feature Article - Decision analysis: An overview. *Operations Research, 30*(5), 803-838. ([pdf](https://pubsonline.informs.org/doi/pdf/10.1287/opre.30.5.803)).  
         - Smith, J. E. y von Winterfeldt, D. (2004). Decision Analysis in "Management Science". *Management Science, 50*(5), 561-574. ([pdf](https://sci-hub.se/10.2307/30046097)).  


#### Unidad 4. Los problemas de decisión
1. Modelación de los problemas de decisión
2. Proceso de resolución de problemas de decisión
3. Estructuración de problemas de decisión
4. La situación a analizar
5. Modelos de decisión: 
   - Matriz de pagos
   - Árboles de decisión
   - Modelo de scoring
   - Modelo de norma mínima
   - Otras técnicas
6. Tareas y prácticas
   - *Tarea 4.1*: *Fundamentos de la estructuración de problemas de decisión*. (Fecha de entrega: 11 de mayo de 2022).  

     *Objetivo*: Aprender los fundamentos de la estructuración de problemas de decisión.  

     *Parte 0*: Organícense en parejas.  
  
     *Parte 1*: Resuelva el siguiente [cuestionario](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad%204.%20Cuestionario.md) sobre la *estructuración de los problemas de decisión*, mediante la elaboración de un archivo RMarkdown.  
 
     Saquen sus conclusiones y suban los archivos creados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.

   - *Práctica 4.2*: *Instalación y uso básico de Radiant, análitica de negocios con R y Shiny*. (Fecha de entrega: 11 de mayo de 2022).    
      
     *Objetivo*: Instalar y usar *Radiant* para el análisis de negocios con *R* y *Shiny* en *RStudio*.    
      
     *Parte 1*: Instale el plugin [Radiant](https://cran.r-project.org/web/packages/radiant.data/readme/README.html), de acuerdo a las [instrucciones](https://radiant-rstats.github.io/docs/index.html), en su instalación de *RStudio*.  
      
     *Parte 2*: *Instrucciones generales*. Estudie el tema de *Análisis de Decisiones* usando *árboles de decisión* en el [tutorial escrito](https://radiant-rstats.github.io/docs/model/dtree.html) de *Radiant* y en la [lista de reproducción](https://www.youtube.com/watch?v=plSeVJ7c-Iw&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw) correspondiente. 
      
     Utilice el [tutorial escrito](https://radiant-rstats.github.io/docs/model/dtree.html) como base para la generación del archivo *RMarkdown* que contenga las recetas correspondientes en español. Este será un entregable. 
      
     Además, utilice los [archivos YAML](https://uc2a9e31d90010cc1bfd4229da2a.dl.dropboxusercontent.com/zip_download_get/BH8yEm5Fx3j6a7es51fpAxNGw4eiKdA41uC8yYW-Voo8Gzh05VpCnCTEiQpyPTdSgDj0IoIkw-x-63Z0xmYavHUiFmBOtGHfr9g2Y95nrB7YQA?dl=1#) de los ejercicios como insumos, introduzca los comentarios respectivos en el archivo YAML (con # igual que en R) y traduzca lo que corresponda. Estos archivos serán sus otros entregables. 
      
     Una vez que haga la simulación con los árboles de decisión inicial y final, guarde sus resultados en el archivo RMarkdown.
   
     *Parte 3:* Estudie los primeros tres videos en la [lista de reproducción](https://www.youtube.com/watch?v=plSeVJ7c-Iw&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw) correspondiente y reproduzca los dos ejercicios (#1 y #2) que se muestran en los videos y genere el archivo *RMarkdown* traducido al español y haga su video de evidencia.  
      
     *Parte 4*: Estudie el tema del *análisis de sensibilidad* en *árboles de decisión* en el video 4 de la [lista de reproducción](https://www.youtube.com/watch?v=c_pCCCn6FEw&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=4) correspondiente. Reproduzca el  ejercicio #3 que se muestra en el video y genere la parte correspondiente del archivo *RMarkdown* en español y haga su video de evidencia.  
      
     *Parte 5*: Estudie la depuración de los errores de la entrada de datos en *árboles de decisión* en el video 5 de la [lista de reproducción](https://www.youtube.com/watch?v=oiwv15bbjzs&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=5) correspondiente.  Reproduzca el ejercicio #4 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.  
      
     *Parte 6*: Estudie el tema de probabilidad en *árboles de decisión* en el video 6 de la [lista de reproducción](https://www.youtube.com/watch?v=xuv9zgAcvCQ&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=6) correspondiente. Reproduzca el  ejercicio #3 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.
      
     *Parte 7*: Estudie el tema de *árboles de decisión* con información imperfecta en el video 7 de la [lista de reproducción](https://www.youtube.com/watch?v=xuv9zgAcvCQ&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=7) correspondiente. Reproduzca el  ejercicio #4 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.
      
     *Parte 8*: Aprenda a desarrollar los *árboles de decisión* con información imperfecta en el video 8 de la [lista de reproducción](https://www.youtube.com/watch?v=xuv9zgAcvCQ&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=8) correspondiente. Reproduzca el  ejercicio #2 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.
      
     Saquen sus conclusiones y suban los archivos creados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.

   - *Práctica 4.3*: *Las decisiones grupales: Un enfoque deontológico*. (Fecha de entrega: 16 de mayo de 2022 a las 24:00 hr, 1 punto extra en la Unidad 4, a quien lo realice).    
      
     *Objetivo*: Comprender la complejidad de la toma de decisiones grupales y la importancia de la ética.    
      
     Desarrolle la siguiente [actividad](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad_4._Practica_4.3.md).  
 
     Saquen sus conclusiones y suban los archivos creados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.


     ##### *Bibliografía Obligatoria:*
        - Ley-Borrás, R. (2015). Deciding on the decision situation to analyze: The critical first step of a decision analysis. *Decision Analysis, 12*(1), pp. 46-58. ([pdf](https://sci-hub.se/10.1287/deca.2014.0308)) (*Lectura 4.1*).  
        - Keeney, R. L. (2007). Developing objectives and attributes. In W. Edwards, R. F. Miles y D. von Winterfeldt. (2007). [*Advances in Decision Analysis: From foundations to applications*](http://libgen.rs/book/index.php?md5=AE826E7206D6FE17FD495BDB3BE0BC7B) (pp. 104-128), Cambridge: Cambridge University Press. (*Lectura 4.2*).
        - Rojas, G., Fernandez, E., Whitney, C., Luedeling, E. & Cuneo, I. F. (2021). Adapting sweet cherry orchards to extreme weather events: Decision analysis in support of farmers "Investments in Central Chile.” *Agricultural Systems* 187(February): 103031. DOI: https://doi.org/10.1016/j.agsy.2020.103031 . ([url](https://sci-hub.se/10.1016/j.agsy.2020.103031)). ([video](https://www.youtube.com/watch?v=kpsqzkeg53Y)). (**Estudio de caso**). (*Lectura 4.3*).  

     ##### *Bibliografía Complementaria:*
        - Barclay, S. *et al.* (1977). Diagramming and solving decisions problems. In *Handbook for Decisions Analysis: Decisions and Designs* (pp. 1-20). Washington, D.C.: Advanced Research Projects Agency. ([pdf](https://files.eric.ed.gov/fulltext/ED153329.pdf)).  
        - Cashin, J. A., Polimeni, R. S. (1980). *Contabilidad de costos*. Mexico: McGraw-Hill. ([url](http://libgen.rs/book/index.php?md5=84A7C8752F1C3869D0FFAE8D8ACEBEE4)).  
        - Clemen, R. T y Kwit, R. C. (2001). The value of decision analysis at Eastman Kodak Company, 1990-1999. *Interfaces, 31*(5), pp. 74-92. ([pdf](https://sci-hub.se/10.1287/inte.31.5.74.9655)).  
        - Clemen, R. T. y Reilly, T. (2004). *Making hard decisions with decision tools*. USA: Cengage Learning. ([url](http://libgen.rs/book/index.php?md5=741D87EE4E16DCFFD7BCBB4840CD6B78)).  
        - Detsky, A. S., Redelmeier, D., y Abrams, H. B. (1987). What's wrong with decision analysis? Can the left brain influence the right?. *Journal of Chronic Diseases, 40*(9), pp. 831-836. ([pdf](https://libgen.rocks/ads.php?doi=10.1016/0021-9681%2887%2990181-0)).  
        - Drury, C. (2020). *Management and cost accounting*. USA: Cengage Learning EMEA. ([url](http://libgen.rs/book/index.php?md5=32C869373F6352B932D6EF56FB9CD9D4)).  
        - Parnell,G. S., Bresnick, T. A., & Tani, S. N. (2013). *Handbook of decision analysis*. Hoboken, New Jersey: John Wiley. ([pdf](http://library.wbi.ac.id/repository/135.pdf)).  
        - Proctor, T. (2019). *Creative problem solving for managers: Developing skills for decision making and innovation*. London: Routledge. ([url](http://libgen.rs/book/index.php?md5=FDD1A6CBEFEF95C7EDB630312F5CF965)).  
        - Ragsdale, C. (2008). Introduction to modeling and decision analysis. In [*Spreadsheet modeling & decision analysis: A practical introduction to management science*](http://libgen.rs/book/index.php?md5=442D6BCA8F1998623582DEF3815DD9E9). Mason, MO, USA: Cengage Learning.  
        - Ríos, S., Ríos, D., Mateos, A. y Martín, J. (1998). *Programación lineal y aplicaciones: Ejercicios resueltos*. México: Alfa Omega Ra Ma. ([pdf](http://library.lol/main/C3553551396E715FAD11F850D70DF9F2)).  
        - Vanderbeck, E. J. (2017). *Principios de contabilidad de costos*. Cengage Learning. ([url](http://libgen.rs/book/index.php?md5=10A696DBB7D2AB1F5BAC60C0C868D51C)).


### Bibliografía General:
- Paquete [Multi-Criteria Decision Aiding (MCDA)](https://www.decision-deck.org/r/), [tutorial](https://www.decision-deck.org/r/tutorial.html#tutorial-r-mcda).
- Cochran et al. (2015). Wiley encyclopedia of operations research and management science. Wiley. ([url](http://libgen.rs/book/index.php?md5=79C89EF789E282EC4CFD15B19CF0A91D)).
- Bouyssou, D., Marchant, T., Pirlot, M., Perny, P., Tsoukià, A., & Vincke, P. (2000) *Evaluation and decision models: A critical perspective*. Kluwer, Dordrecht. ([url](http://libgen.rs/book/index.php?md5=D17907F555C0E2A519EA0EDCBDAC8F43)).
- Luedeling, E. et al (2022, Feb 18). Package ‘decisionSupport’ (Quantitative Support of Decision Making under Uncertainty). *CRAN*. ([pdf](https://cran.r-project.org/web/packages/decisionSupport/decisionSupport.pdf)).
- Gass, S. I. & Fu, M. C. (2013). Encyclopedia of operations research and management science (pp. 367-372). (3rd. Ed.). New York: Springer ScienceþBusiness Media. ([url](http://libgen.rs/book/index.php?md5=DD2A825793319105943B8B28CF0F83AB)).
- Haber, S. H. (Ed.). (2002). Crony capitalism and economic growth in Latin America: Theory and evidence. Stanford, USA: Hoover Institution Press. ([url](http://libgen.rs/book/index.php?md5=B0750211B7978624626DF228B5CDB873)).
- Howard, R. A., & Abbas, A. E. (2016). Foundations of decision analysis. Great Britain: Pearson Education. ([url](http://libgen.rs/book/index.php?md5=4B19F574BA8246A5BA274A7AF4BFB6A5)).
- Krogerus, M., & Tschäppeler, R. (2012). The decision book: Fifty models for strategic thinking. London: Profile Books. ([url](http://libgen.rs/book/index.php?md5=9B263D6F2C7B79A11FA0D2B9A0880FDD)).  
- Meyer, P., Bigaret, S., Hodgett, R., & Olteanu, A-L. (2021, May 04). Package MCDA (Support for the Multicriteria Decision Aiding Process). CRAN. ([url](https://cran.r-project.org/package=MCDA)). 
- Sparxs Systems (2021). Enterprise Architect. Modeling Software. ([url](https://sparxsystems.com/)). ([torrents](https://thepiratebay.org/search.php?q=Enterprise+Architect&apps=on&search=Pirate+Search&page=0&orderby=))
- Weick, K. E. (1995). *Sensemaking in organizations*. Thousand Oaks, CA, USA: Sage. ([url](http://libgen.rs/book/index.php?md5=6362CD2CBBE13DC182B79815E388052D)).

- Recursos digitales en la UAM: biblioteca de la Unidad Iztapalapa ([url](http://contingencia.izt.uam.mx/wp-content/uploads/2020/04/Biblioteca-Nuevo-3b-bindani-B.pdf)), biblioteca digital ([url](https://bidi.uam.mx/index.html)), [recursos varios](http://pcyti.izt.uam.mx/recursos/infext/infoext.html).  
- Recursos controversiales: [Library Genesis](http://gen.lib.rus.ec/) (libros, artículos, novelas), [**SciHub**](https://sci-hub.se/about) (artículos), [The Pirate Bay](https://thepiratebay.org/index.html) (P2P file sharing network) (archivos), [Academic Torrents](http://academictorrents.com/) (artículos, datos y cursos).
- Repositorios de software: [Software para la comunidad UAM](https://www.uam.mx/ti/soft/), [AlternativeTo](https://alternativeto.net/), [SourceForge](https://sourceforge.net/), [CDLibre](https://www.cdlibre.org/), [Software Heritage](https://www.softwareheritage.org/?lang=es), [GitHub](https://github.com/github).
- Hernández, L. (2012, Nov 16). **El Software Libre y la educación** por Richard Stallman. *YouTube* ([url](https://www.youtube.com/watch?v=aRvorE9PJso)).  
- Valcheva, S. (s.f.). 10 Open Source Decision Tree Software Tools. ([url](https://www.intellspot.com/open-source-decision-tree/)).

- Universitat de les Illes Balears. Som UIB (2016, Sep 22). MOOC Aprende R : Introducción al tratamiento de datos con R y RStudio. *YouTube*. ([Lista de videos](https://www.youtube.com/playlist?list=PLnXFIHWLWQXFOIOdpAv2ioBHQuYgV7x2t)).
- Wickham, H. & Grolemund, G. (2017). *R for data science: Import, tidy, transform, visualize, and model data*. O'Reilly. ([url](https://r4ds.had.co.nz/)). (R para ciencia de datos, [traducción español](https://r4ds-en-espaniol.netlify.app/)). (Solución de los ejercicios, [url](https://cienciadedatos.github.io/r4ds-soluciones/index.html)).
- Teetor, P. (2019). *R cookbook: Proven recipes for data analysis, statistics, and graphics*. O'Reilly. [Online] ([url](https://rc2e.com/)). ([traducción al español](https://translate.google.com/translate?sl=en&tl=es&u=https://rc2e.com/)).
- Wickham, H. & Grolemund, G. (2017). R for data science. [Online] ([url](https://r4ds.had.co.nz/)), [traducción al español] ([url](https://es.r4ds.hadley.nz/)).
- RStudio cheatsheets. ([url](https://github.com/rstudio/cheatsheets)).

## Modalidades de Evaluación

### Evaluación Global
La asistencia puntual a la clase es obligatoria, según el reglamento de estudios. Es importante la *participación activa clase a clase*. La falta de participación en clase y la no entrega de sus reportes de prácticas a lo largo del trimestre, tendrá repercusiones en la evaluación final que puede llegar a la reprobación del curso. Ver porcentajes de ponderación de calificación.

#### Calificación
| Factor | Porcentaje | Observaciones |
| --- | :---: | ------------- |
| Asistencia puntual | 10% |  |
| Tareas|30% |Se entrega en la fecha programada |
| Prácticas| 30% |Se entregan  en la fecha programada |
| Exámenes| 30% | Primero (a), Segundo (b)|
| Total | 100% | |

**Notas:
  - **a).** Primer examen: *Teórico* (Unidades ) y *Práctico* (): Fecha: 
  - **b).** Segundo examen: *Teórico - Práctico* (Unidad 4): Fecha: 
  - **Evaluación Global:** Todo el curso (Teoría y Práctica) para quienes tengan baja calificación o deseen subir.
  - **Entrega de calificaciones:** .

La *evaluación final* será un examen teórico-práctico que versará sobre la totalidad de las unidades. 

### Evaluación de Recuperación
La *evaluación de recuperación* no será aplidada por el profesor, sino por la Coordinación de la Licenciatura en Administración, de acuerdo a las políticas definidas por la misma y será realizada según el calendario vigente. Por lo que deberá coordinarse con el Coordinador de la Licenciatura.

**Notas:**
[^1]: Jaiswal, N. K. (1997). *Military operations research: Quantitative decision making*. New York: Springer Science+Business Media.
[^2]: Gass, S. I. y Fu, M. C. (2013). Preface. *In* Saul I. Gass y Michael C. Fu (Eds.). *Encyclopedia of operations research and management science*. New York, Heidelberg, Dordrecht, London: Springer
[^3]: Hitch, C. (1955). An appreciation of systems analysis. *Journal of the Operations Research Society of America, 3*(4), 466-481.
[^4]: Simon, H. A. (1955). A behavioral model of rational choice. *The Quarterly Journal of Economics, 69*(1) (Feb), 99-118.
[^5]: Beer, S. (1967). *Management science: The business use of operations research*. Doubleday
[^6]: Witzel, M. (2012). *A History of Management Thought*. London: Routledge.
[^7]: Buchanan, L y O'Connell, A. (2006). A brief history of decision making. *Harvard Business Review, 84*(1), 32-41, 132.
[^8]: Chen, N. C., Shauver, M. J., & Chung, K. C. (2009). A primer on use of decision analysis methodology in hand surgery. *The Journal of Hand Surgery, 34*(6), 983-990.
[^9]: Call, H. J., y Miller, W. A. (1990). A comparison of approaches and implementations for automating decision analysis. *Reliability Engineering & System Safety, 30*(1-3), 115-162.

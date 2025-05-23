# IIC2133 - Estructuras de Datos y Algoritmos
## 2021-2

Bienvenido al sitio web del curso de Estructuras de Datos y Algoritmos. En esta página podrás encontrar la información administrativa del curso. En el repositorio podrás encontrar código ya preparado por tus ayudantes, junto con los eventuales enunciados de las tareas y las diapositivas de clases.

## Tabla de contenidos 
 * [Clases y ayudantías](#clases-y-ayudantías)
 * [Equipo](#equipo)
     * [Profesores](#profesores)
     * [Ayudantes](#ayudantes)
 * [Política de Integridad Académica](#política-de-integridad-académica)


## Curso de C
[Into a C por Vicente Errázuriz y Raúl Álvarez](https://github.com/DCCentral-de-Apuntes/intro-C)

## Clases y Ayudantías
| Tipo | Número | Tema | Fecha | Grabación | Material |
| :--: | :--: | :--: | :--: | :--: | :--: |
| Clase | 0 | Introducción | 16/08 | [Grabación Zoom](https://zoom.us/rec/play/4Q-fdL42jF7WKViVCu0SozPYzsXy2FXQJZ2iRKCQ9frqUzNHpTDD7JhRf-ZrJkql4ONAGi5GOIqftfOy.2ebROmMFplDFBb_h?continueMode=true&_x_zm_rtaid=i1JMy9qXQi2UnTUbCZE3wg.1629665339504.2319da3fbb4ac84c3129cec48313e29b&_x_zm_rhtaid=875) [YouTube](https://youtu.be/UUzeO7Eoz7o) | |
| Taller | 0 | Introducción a C | 18/09 | [Grabación](https://youtu.be/lQ8NsfGNsbU)| [Repo taller](https://github.com/IIC2133-PUC/Taller0)|
| Taller | 1 | Continuación Taller introductorio a C | 20/08 | [Grabación](https://youtu.be/xtqvCs1v83k) ||  
| Clase | 1 | Selection Sort y Correctitud | 23/08 | [Grabación](https://www.youtube.com/watch?v=0ZnIxyX3FzU)| [Diapos](https://github.com/IIC2133-PUC/2021-2/tree/master/Clases/01.%20Selection%20e%20Insertion%20sort.pdf) |
| Clase | 2 | Insertion Sort y Sorting | 25/08 | [Grabación](https://youtu.be/GHnOuCCqoSI)| [Diapos](https://github.com/IIC2133-PUC/2021-2/tree/master/Clases/01.%20Selection%20e%20Insertion%20sort.pdf) |
| Ayudantía | 1 | Selection Sort, Insertion Sort y Correctitud | 27/08 | [Grabación](https://youtu.be/9WW-VoADRnM)| [Diapos](https://github.com/IIC2133-PUC/2021-2/blob/master/Ayudant%C3%ADas/Ayudant%C3%ADa%201%20-%20Repaso%20ordenaci%C3%B3n/Ayudantia_1.pdf) |
   
## Equipo

### Profesores

| Nombre               |  Sección         |  Email         |
|:-------------------- |:--------------|:--------------|
| Yadran Eterovic | 1 | yadran@ing.puc.cl |
| Martín Muñoz | 2 | mmunos@ing.puc.cl |


### Ayudantes

| Nombre                | Email       | Github |
|:--------------------- |:-------------| :---------|
| Carlos Paredes | cparedesr@uc.cl | [@CarloGauss33](https://www.github.com/CarloGauss33)|
| Ignacio Bascuñan | nachobascar@uc.cl | [@Nachobascar](https://github.com/nachobascar)|
| Cristobal Berrios | crisberrios@uc.cl | [@CrisBerriosL](https://www.github.com/CrisBerriosL)|
| Cristian Alonso Carrasco | cristian.carrasco@uc.cl | |
| Sergio Matamala | matamalaappels@uc.cl | [@Huasito-Appel](https://www.github.com/Huasito-Appel)|
| Agustin Rios | arios6@uc.cl | [@agustin-rios](https://www.github.com/agustin-rios)|
| Fernando Torres | fernando.torres@uc.cl | [@FdoTorres1](https://www.github.com/FdoTorres1)|
| Ziqi Yan | zyan@uc.cl | [@chineseJack564](https://www.github.com/chineseJack564)|
| Ignacion Zuñiga | inzuniga@uc.cl ||
| Tanya Garrido | tcgarrido@uc.cl | [@tcgarrido](https://www.github.com/tcgarrido)
| Nicholas Mc-Donnell | namcdonnell@uc.cl | [@N9199](https://www.github.com/N9199)|
| Nicolás Fraga | nfraga@uc.cl | [@nfragav](https://www.github.com/nfragav)|
| Felipe Lois | fplois@uc.cl| [@fplois](https://www.github.com/fplois)|
| José Tomas Jimenez | josejimenez@uc.cl | [@josejimenezp](https://www.github.com/josejimenezp)|
| Sergio Gutierrez | sergio.gutierrez@uc.cl | [@sgutgar](https://www.github.com/sgutgar)|
| Ignacio Porte | ignacio.porte@uc.cl | [@IgnacioPorte](https://www.github.com/IgnacioPorte)|

## Evaluación

El curso consta de una parte teórica, evaluada mediante evaluaciones escritas (interrogaciones), y una parte práctica, evaluada mediante tareas de programación en C.

### Evaluaciones Escritas

Habrá 3 interrogaciones, donde se evaluarán los aspectos más teóricos del contenido.

| Evaluación | Fecha |
|:----------|:----------|
| Interrogación 1 |  |
| Interrogación 2 |  |
| Interrogación 3 |  |


### Tareas

Habrá 4 tareas de programación en C, donde deberán resolver un problema complejo y analizarlo en un informe escrito. 

La nota final del curso se calcula de la siguiente manera:

```c++
double nota_final()
{
    /* La nota de cada tarea */
    double T0,T1,T2,T3;    
    /* La nota de cada interrogación*/
    double I1,I2,I3;

    /* Promedio de tareas */
    double NT = (T0 + T1 + T2 + T3) / 4;
    /* Promedio de interrogaciones */
    double NI = (I1 + I2 + I3) / 3;
    
    /* Nota final */
    double NF = (NT + NI) / 2;
    
    /* Es necesario tener sobre 3.7 en las evaluaciones escritas y las tareas por separado para aprobar el curso */
    if(NI < 3.7 || NT < 3.7)
    {
       return min(3.9, NF);
    }
    else
    {
       return min(NF, 7);
    }
}
```

## Política de integridad académica

Este curso se adscribe a la política de integridad académica de la Escuela de Ingeniería y el Departamento de Computación.

---

Los alumnos de la Escuela de Ingeniería de la Pontificia Universidad Católica de Chile deben mantener un comportamiento acorde a la Declaración de Principios de la Universidad.  En particular, se espera que **mantengan altos estándares de honestidad académica**.  Cualquier acto deshonesto o fraude académico está prohibido; los alumnos que incurran en este tipo de acciones se exponen a un Procedimiento Sumario. Es responsabilidad de cada alumno conocer y respetar el documento sobre Integridad Académica publicado por la Dirección de Docencia de la Escuela de Ingeniería (disponible en SIDING).

Específicamente, para los cursos del Departamento de Ciencia de la Computación, rige obligatoriamente la siguiente política de integridad académica. Todo trabajo presentado por un alumno para los efectos de la evaluación de un curso debe ser hecho individualmente por el alumno, sin apoyo en material de terceros.  Por “trabajo” se entiende en general las interrogaciones escritas, las tareas de programación u otras, los trabajos de laboratorio, los proyectos, el examen, entre otros.

**En particular, si un alumno copia un trabajo, o si a un alumno se le prueba que compró o intentó comprar un trabajo, obtendrá nota final 1.1 en el curso y se solicitará a la Dirección de Docencia de la Escuela de Ingeniería que no le permita retirar el curso de la carga académica semestral.**

Por “copia” se entiende incluir en el trabajo presentado como propio, partes hechas por otra persona.  **En caso que corresponda a “copia” a otros alumnos, la sanción anterior se aplicará a todos los involucrados**.  En todos los casos, se informará a la Dirección de Docencia de la Escuela de Ingeniería para que tome sanciones adicionales si lo estima conveniente. Obviamente, está permitido usar material disponible públicamente, por ejemplo, libros o contenidos tomados de Internet, siempre y cuando se incluya la referencia correspondiente y sea autorizado por los ayudantes.

Lo anterior se entiende como complemento al Reglamento del Alumno de la Pontificia Universidad Católica de 
Chile<sup><a name="pucCLBack">[1](#pucCL)</a></sup>.  Por ello, es posible pedir a la Universidad la aplicación de sanciones adicionales especificadas en dicho reglamento.

<sub>**<a name="pucCL">[1](#pucCL)</a>**: Reglamento del Alumno de la Pontificia Universidad Católica de Chile disponible en: http://admisionyregistros.uc.cl/alumnos/informacion-academica/reglamentos-estudiantiles [&#8593;](#pucCLBack)</sub>

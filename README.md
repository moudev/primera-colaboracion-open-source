# Primera colaboración Open Source

**📚 Tabla de contenido**

- [📍 Aspectos Generales](#-aspectos-generales)
- [📑 Detalles](#-detalles)
- [🔖 Guía de colaboración desde cero](#-guía-de-colaboración-desde-cero)
  * [1- Hacer fork del repositorio original](#1--hacer-fork-del-repositorio-original)
  * [2- Clonar el repositorio de forma local](#2--clonar-el-repositorio-de-forma-local)
  * [3- Realizar modificaciones](#3--realizar-modificaciones)
  * [4- Subir los cambios locales hacia el repositorio copia](#4--subir-los-cambios-locales-hacia-el-repositorio-copia)
  * [5- Crear un pull request](#5--crear-un-pull-request)
  * [6- Asignar issues resueltos](#6--asignar-issues-resueltos)
  * [Actualizar repositorio copia luego de haber unido los cambios propuestos](#actualizar-repositorio-copia-luego-de-haber-unido-los-cambios-propuestos)
- [📍 Recomendaciones](#-recomendaciones)

## 📍 Aspectos Generales

El objetivo de la iniciativa es explicar un poco sobre cómo realizar contribuciones a proyectos *Open Source*, los cuales en este caso están alojados en la plataforma `GitHub`.

La guía está enfocada a personas que apenas empiezan en el uso del controlador de versiones `Git` y de la plataforma `GitHub`.

Un punto importante de la guía es; ayudar a las personas a ganar confianza en realizar colaboraciones a proyectos publicados a lo largo de Internet y, que sea uno de los primeros pasos para sembrar la cultura de seguir investigando por cuenta propia, aparte, para ampliar el panorama del alcance que puede llegar a tener el realizar colaboraciones de este tipo.

Esta iniciativa fué creada debido al evento [Hacktoberfest 2020](https://hacktoberfest.digitalocean.com/).

## 📑 Detalles

Para poder completar el *Hacktoberfest* es necesario crear cuatro *Pull Request(PR)* a repositorios públicos dentro de *GitHub*. Pueden ser varios *Pull Request(PR)* dentro del mismo repositorio.

Esta guía debe de servir como ayuda para poder completar con éxito el *Hacktoberfest*. 

Dentro de esta guía existen cinco carpetas de las cuales dentro de cada una se encuentra la maquetación *HTML* de una *Lading Page*(página de inicio), cuya maquetación cuenta con un nivel básico de diseño y que no tiene mayor complejidad.

Para cada diseño existe una cantidad de tareas(*issues*), cada una de ellas respectivamante etiquetadas para saber a qué *Landing Page* pertenece la tarea. Las tareas(*issues*) no son complicadas y son de modificaciones sencillas para facilitar la colaboración. Cada tarea cuenta con una descripción bastante clara de lo que se debe de realizar.

La idea propuesta sería realizar un *PR* en cada una de las *Landing Pages* hasta completar la cantidad de cuatro.

Para poder ver el listado de tareas hay que entrar en la [pestaña de issues de este repositorio](https://github.com/moudev/primera-colaboracion-open-source/issues) y elegir la tarea en la que se considere tener la capacidad de colaborar. Varias personas pueden participar en la misma tarea ya que ninguna colaboración terminará siendo unida(hacer *merge*) al repositorio por que el objetivo es solamente simular el proceso de colaboración en un proyecto.

**🤔 ¿Cualquier persona puede participar y colaborar en este repositorio?** Sí, toda ayuda es bien recibida y más aún cuando sea para mejorar la experiencia de las personas participantes de esta iniciativa. Solamente existen condiciones de colaboración en las tareas de cada *Landing Page*.

**🤔 ¿Existe una forma en la cual mi colaboración no sea tomada en cuenta?** Sí, para completar el *Hacktoberfest* deben de ser cuatro *PR* válidos, es decir que no hayan sido marcados como *spam*, si uno de los *PR* es marcado como tal, no cuenta. Dentro de este repositorio existen condiciones para dar como válida una colaboración.

**🤔 ¿Por qué motivos un *PR* puede ser marcado como *spam*?** En este caso será cuando la persona que realiza colaboración ya tenga experiencia en colaborar en proyectos *Open Source* y que solamente está buscando tareas sencillas para poder completar el *Hacktoberfest*. Esta iniciativa está enfocada a personas que no tienen experiencia o poco conocimientos sobre colaborar en Internet. Si la colaboración es de alguien con experiencia y solamente es corrección de texto, no cuenta, debe de ser algo que genere valor al proyecto y que será evaluado por la persona administradora del repositorio.

*👋🏽 Nota de redacción:* 
Si has llegado hasta este punto de la lectura, ¡que bueno!. Si consideras que esta iniciativa puede ayudarle a más personas el hecho de compartirla puede ser de ayuda, no necesariamente tiene que ser de forma pública a través de redes sociales, puedes hacerlo de la forma que encuentres más conveniente para que pueda llegar a la mayor cantidad posible de entusiastas. Espero que puedas ganar más confianza para colaborar en proyectos Open Source y poder completar el Hacktoberfest :)

No se nace sabiendo algo, hay que prácticar tarde o temprano. Gracias por tu atención. 

## 🔖 Guía de colaboración desde cero

Guía con imagenes sobre los pasos para poder resolver los `issues` en cada una de las landing pages. Leer el texto de las indicaciones con atención.

**Requerimientos:**
- [Instalar `git`](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Tener un editor de texto instalado

### 1- Hacer fork del repositorio original

![1-fork](https://user-images.githubusercontent.com/43508962/95669569-82309800-0b3f-11eb-85c9-05bf0a2dcaf4.png)


Luego de presionar en `fork` se podrá ver el proceso mientras se crea una copia del repositorio y en el cual se puede hacer modificaciones.

![2-process-fork](https://user-images.githubusercontent.com/43508962/95669607-d2a7f580-0b3f-11eb-88f4-42e85caacc72.png)

Luego de haber hecho la copia se puede observar que no se está en la ruta del repositorio original. El texto `forked from` quiere decir que se trata de un copia y por lo tanto tiene una ruta diferente al repositorio original.

![3-check-fork](https://user-images.githubusercontent.com/43508962/95669625-04b95780-0b40-11eb-93b7-3f433f752e9c.png)

### 2- Clonar el repositorio de forma local

Luego de haber copiado el repositorio se debe de clonar de forma local en la computadora que se está usando, para ello es necesario presionar sobre el botón de `Code`, luego, en el icono similar a un hoja. Lo que se copia es la URL del repositorio.

![4-copy-clone](https://user-images.githubusercontent.com/43508962/95669638-33cfc900-0b40-11eb-9be7-96ec60eb22f1.png)

Posterior de haber copiado el enlace del repositorio, es necesario abrir una consola en la computadora, la ruta de la consola puede ser en cualquier lugar siempre y cuando se recuerde la ruta.

En consola ejecutar el comando;

```shell
git clone https://URL-DEL-REPOSITORIO-COPIADO
```

![5-command-clone](https://user-images.githubusercontent.com/43508962/95669678-78f3fb00-0b40-11eb-920a-f67dad26d047.png)


Una vez el paso de clonar el repositorio haya terminado, se tiene que entrar en la carpeta del repositorio. Si se revisan las carpetas dentro de la carpeta del repositorio clonado, se podrán observar las carpetas de cada landing page.

![6-clone-enter-carpet](https://user-images.githubusercontent.com/43508962/95669699-a2ad2200-0b40-11eb-9daf-dac12f77e627.png)

### 3- Realizar modificaciones

Posterior de entrar en la carpeta y haber elegido una landing page que modificar, se tiene que abrir el editor de texto de preferencia y completar los `issues` que la landing page tiene asignados.

En el caso de la siguiente imagen, se abrió la carpeta de la landing page 1 y, se modificó el nombre de una de las opciones del menú.

![7-modify-file-visual-code](https://user-images.githubusercontent.com/43508962/95669731-d8520b00-0b40-11eb-8323-2aaf2d38bcb5.png)

Una vez hecho los cambios y guardados, se debe de regresar a la consola y ejecutar el comando;

```shell
git status
```

`git status` permite ver cuales han sido los archivos que han sufrido cambios, en este caso el archivo `index.html` de la landing page 1

![8-command-git-status](https://user-images.githubusercontent.com/43508962/95669749-14856b80-0b41-11eb-982c-84dde95e7874.png)

Una vez revisado qué archivos fueron modificados, se tiene que ejecutar el comando;

```shell
git add .
```

El comando `git add .` agrega todos los archivos modificados en un registro que luego será enviado hacia el repositorio que es copia.

Luego de agregar los archivos al registro, es necesario confirmar los cambios para que sean agregados al historial de modificaciones, con el comando;

```shell
git commit -m "Modificando landing page 1"
```

Lo que está dentro de las comillas dobles es el mensaje que se le asigna, este mensaje puede ser el que se desee aunque, se recomienda que sea descriptivo por que servirá más adelante para temas de historial de cambios.

![9-git-add-commit](https://user-images.githubusercontent.com/43508962/95669813-d2105e80-0b41-11eb-85bd-466fa7c8875e.png)

### 4- Subir los cambios locales hacia el repositorio copia

Una vez se confirmaron los cambios, se tienen que enviar de el repositorio local en la computadora, hacia el repositorio que es copia y que se encuentra en `GitHub`, con el comando;

```shell
git push origin master
```

![10-git-push-origin](https://user-images.githubusercontent.com/43508962/95669819-ece2d300-0b41-11eb-8003-cdfff23a1c6f.png)

### 5- Crear un pull request

Luego que se han subido los cambios, se puede notar en el repositorio copia de `GitHub` el mensaje; `This branch is 1 commit ahead of ...`, esto quiere decir que la copia tiene una modificación que el repositorio original no tiene.

Para poder proponer estos cambios al repositorio original, lo que se tiene que hacer es algo llamado `Pull request`, que es una solicitud para que acepten los cambios recién hechos, en este caso el cambio hecho en la landing page 1.

![11-click-pull-request](https://user-images.githubusercontent.com/43508962/95669841-1f8ccb80-0b42-11eb-89e8-568e689cb20a.png)

Una vez presionado en `Pull Request` se mostrará lo cambios que se quieren enviar hacia el repositorio original. Luego de revisar si todo está bien, es hora de confirmar que se quiere hacer una petición para proponer modificaciones en el repositorio original, para ello hay que presionar sobre `Create pull request`

![12-preview-pull](https://user-images.githubusercontent.com/43508962/95669847-34695f00-0b42-11eb-9d04-ac1b7c0b6193.png)

Luego de presionar sobre `Create pull request` se mostrará el repositorio original, esto se puede saber porque en el título ya no aparece `forked from ..`

En la página ahora se mostrará un formulario para hacer la solicitud que se acepten los cambios. Se pueden agregar detalles como el título de la solicitud, la descripción de los cambios que se quieren proponer.

Una vez redactada la solicitud, se tiene que presionar sobre `Create pull request`, que es la acción que oficialmente propone los cambios para que las personas que son propietarias del repositorio original puedan revisarlos.

![13-write-pull-click-send](https://user-images.githubusercontent.com/43508962/95669901-89a57080-0b42-11eb-8d73-1aa6ef33f6a7.png)

### 6- Asignar issues resueltos

Luego de haber creado el `Pull request` se procede a enlazar los `issues` que fueron resueltos, en el caso de las landing pages, cada una ya los tiene asignados. Estas asignaciones son para llevar un mejor control y orden del repositorio, entre más especificas sean las relaciones, mejor.

Se presiona el icono en la sección de `Linked issues` y se mostrará un listado con barra de búsqueda, seleccionar los `issues` que están siendo resueltos y listo.


![14-add-issue-link](https://user-images.githubusercontent.com/43508962/95669951-16e8c500-0b43-11eb-9b82-c4c9df7120ef.png)


Todos los pasos anteriores son los necesarios para poder hacer modificaciones y proponerlas dentro de un repositorio de `GitHub`. Es posible que los cambios no sean aceptados, o que se soliciten modificaciones por las personas administradoras del repositorio, o en un caso afortunado ser aprobados de una sola vez.

Existe un punto muy importante cuando se hace una copia de un repositorio, es probable que desde el momento que se hizo la copia, el original ya tenga más cosas agregadas y esos cambios tienen que estar en la copia que fué hecha con `fork`.

En este caso puede ocurrir que se proponen modificaciones sobre una landing page y, luego se propondrán modificaciones sobre otra, en el tiempo entre propuestas es muy posible que el repositorio original sufra cambios. 

Antes de proponer un `Pull request` se tiene que confirmar que la copia que está en la computadora tenga las últimas modificaciones del repositorio original.

### Actualizar repositorio copia luego de haber unido los cambios propuestos

En la siguiente imagen se muestra el ejemplo cuando el `pull request` fué aceptado y el repositorio copia ya no está sincronizado con el original. La copia tiene un registro menos en el historial de modificaciones.

![15-check-own-repo-after-merge](https://user-images.githubusercontent.com/43508962/95669968-2700a480-0b43-11eb-8ccc-ed38b1d840ff.png)

Para poder sincronizar los últimos cambios del repositorio original con la copia que está en la computadora, es necesario agregar la URL del repositorio original desde consola, es un paso muy similar a cuando se clonó el repositorio.

Teniendo en cuenta que ya se tiene el enlace del repositorio original, se procede a agregarlo desde la raíz de la carpeta que contiene a todas las landing pages, con el comando;

```shell
git remote add upstream https://URL-REPOSITORIO-ORIGINAL
```

Luego de haber agregado el repositorio original, se necesita hacer una petición de estos cambios, pero estos cambios en este momento aún no serán agregados en el historial de modificaciones de la computadora, porque se necesita otro paso de confirmación, con `fetch` es un estilo de petición para dejarlos a un lado mientras tanto.

![16-add-upstream-repo](https://user-images.githubusercontent.com/43508962/95670016-d178c780-0b43-11eb-8bef-a63b4aac2b3c.png)


Con el siguiente comando se confirma que se quieren unir el historial del repositorio original, con el historial del repositorio de la computadora, para ello se tiene que hacer un `pull` de la rama `master` del repositorio original;

```shell
git pull upstream master
```

![17-git-pull-upstream](https://user-images.githubusercontent.com/43508962/95670033-008f3900-0b44-11eb-84ca-63083234e637.png)


Luego de haber ejecutado el comando, los cambios en el historial se podrán notar y con eso poder hacer modificaciones sobre la última versión del repositorio original, esto se puede hacer las veces deseadas, lo recomendable es siempre tratar de manterlo al día.

El comando para ver el historial de modificaciones es;

```shell
git log
```

![18-git-log](https://user-images.githubusercontent.com/43508962/95670039-20266180-0b44-11eb-9edb-5565d2800cb5.png)


## 📍 Recomendaciones

Se recomienda hacer un `pull request` por cada landing page con sus respectivos `issues` en lugar de completar un `issue` de distintas carpetas. Se tienen cinco landing pages dando la oportunidad de poder hacer 5 `pull request` cuando solo se necesitan 4. 

---

Espero que esta iniciativa pueda servirte a ganar confianza en colaborar en proyectos de otras personas, el Hacktoberfest fué el motivo por el cual yo hice mi primer `Pull request` , me ayudó mucho y es por eso el tiempo invertido en crear esto. Una disculpa si no fué de ayuda o no cumplió las espectativas. 

Si se tiene alguna duda, la forma de contacto puede ser a través de [@_codemart](https://twitter.com/_codemart)

¡Saludos!


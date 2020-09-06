---
date: "2020-09-01"
draft: false
type: page
linktitle: Share educational material and maintain authorship.
summary: sharing your educational material so that other people can use it is a powerful and generous idea. In this post we tell you how to do it while maintaining your authorship.
title: Share educational material and maintain authorship.
authors: 
    - yabellini
type: post
weight: 1
tags: 
  - share
  - open education
  - technical tips
---

As detailed in [[1]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005963) generating educational material, they require a significant effort both for its initial development and to keep it updated.

Although there is the _reusability paradox_ [[2]](https://opencontent.org/blog/archives/3854) - [[3]](https://opencontent.org/blog/archives/6585) that postulates that a teaching material will be more reusable when it is as generic as possible but will be more effective when it is personalized for a particular audience, in a particular context [[4]](https://third-bit.com/2015/04/22/the-paradox-of-learning-objects.html); sharing our material in a way that other people can _find it, **use it**, improve it, and **quote it**_ is an activity worth the effort.

With the advent of forced virtuality due to COVID-19, many teachers have found it necessary to share their material in a digital format, in addition to having to adapt some part of it.

Both in [[1]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005963) and [[5]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006915#pcbi.1006915.ref009), it is mentioned that treating the lessons as a community resource to be gradually updated, adapted and improved can _increase the quality of educational material and free up valuable time for teachers in designing their own material_. Not only would we be helping our colleagues, but we can also add benefits for students who can access our material at no cost and when they need it. Finally we would have a quotable product, that is, we could ask for and obtain credit for the material that we have developed, and we could also know who is using this material and where.

_So if I want to share my didactic material, how do I do it? Keep reading that we will tell you_

## Three simple steps to share lessons

* **Step 1: select an open license** make it clear about how to use the material. The most used licenses are known [Creative Commons](http://www.creativecommons.org.ar/licencias.html).  There are different types of licenses depending on what we want the user of our materials to be able to do. If we do not know very well which is the license that best suits our needs, there is a [license selector](https://creativecommons.org/choose/?lang=es_AR) hat can help us.

Si nuestro material tiene código en algún lenguaje de programación, entonces deberemos seleccionar también una [licencia abierta, pensada para software](https://www.gnu.org/licenses/license-list.html#SoftwareLicenses).  Sugiero la licencia [MIT](https://opensource.org/licenses/MIT) o bien, teniendo en cuenta el impacto que el software y la ciencia de datos tienen en nuestra vida, la [licencia hipocrática](https://firstdonoharm.dev/), que permite usar el código libremente siempre que el usuario no esté violando los tratados básicos de derechos humanos. 

* **Paso 2: almacenar el material en un repositorio que nos permita publicarlo.** Un lugar que nos permite realizar esta tarea es [GitHub](https://github.com/) que se usa para desarrollar una variedad de materiales porque nos permite tener diferentes tipos de contenido como diapositivas, documentos, código fuente, imágenes y también nos permite desarrollarlo continuamente a través de un proceso iterativo y con comentarios de otros, ya que GitHub implementa un [sistema de control de versiones](https://es.wikipedia.org/wiki/Control_de_versiones). Si no has usado GitHub, podes utilizar este [tutorial inicial sobre Git](https://yabellini.netlify.app/es/courses/tallerdegitconr/).

* **Paso 3: agregar un [indentificador de objeto digital (DOI)](https://es.wikipedia.org/wiki/Identificador_de_objeto_digital) para que sea citable.** Vamos a describir este paso con mucho detalle siguiendo estas [intrucciones de GitHub](https://guides.github.com/activities/citable-code/).

    * Entrar a [Zenodo](https://zenodo.org/) y presionar el botón Login en la parte superior derecha de la página y seleccionar la opción de iniciar sesión con tu cuenta de GitHub. 
   {{< figure src="/img/screen1.png" >}}

    * Debemos _autorizar la aplicación_ para otorgarle a Zenodo los permisos que necesita para poder asignar un DOI a tu repositorio. 
    {{< figure src="/img/screen2.png" >}}

    * Luego de confirmar que es nuestra cuenta (nos llegará un mail), estaremos logueados en Zenodo y en la esquina superior derecha aparece nuestro correo asociado a GitHub, si hacemos click en el triangulito se despliega un menú donde seleccionamos GitHub:  
    {{< figure src="/img/screen3.png" >}}

    
    * Ahora, elije el repositorio que deseas archivar. Para habilitar esta funcionalidad hacemos clic en el botón Activar junto a al repositorio (en este caso GEE_course_code). El respositorio debe ser _público_

    {{< figure src="/img/screen4.png" >}}

    * Debemos verificar que la configuración del repositorio para enviarle mensajes a Zenodo fue exitosa, para eso hacemos clic en la pestaña de configuración en tu repositorio y luego clic en _Webhooks_ en el menú de la izquierda. Deberías ver una pantalla similar a la siguiente imagen: 

    {{< figure src="/img/screen5.png" >}}

    * Crea una nueva versión: Zenodo archiva tu repositorio cada vez que generes una nueva versión. Para esto regresamos a la vista principal del repositorio y en el menú de la derecha clickeamos en _create new release_.
    {{< figure src="/img/screen6.png" >}}
   
    * Debemos completar la versión de este _release_, el título y la descripción y luego presionar el botón _publish release_, como se muestra en la siguiente figura.
    {{< figure src="/img/screen7.png" >}}

    * Ahora vamos a obtener el DOI, para eso debemos volver a Zenodo y hacer click en _Upload_. Allí va a mostrarnos los diferentes materiales que tenemos publicados enZenodo, si hacemos click en el nombre, nos muestra todo el detalle, podemos editar la inforamción y si bajamos en la página a la derecha nos muestra el DOI y una cita sugerida.

    {{< figure src="/img/screen8.png" >}}


Listo, ya tenemos el DOI y la cita que podemos agregar a nuestro repo y pedirle a las personas que usen nuestros materiales que la utilicen para mencionarnos.






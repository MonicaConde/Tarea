## **GESTOR DE VERSIONES SUBVERSION**##

A principios de 2000, *CollabNet, Inc*. (http://www.collab.net) comenzó a buscar a los desarrolladores para escribir un sustituto para **CVS**.

CollabNet ofrece una suite de software de colaboración denominado CollabNet Enterprise Edition (CEE), de los cuales uno de los componentes era el control de versiones. Aunque CEE utiliza CVS como su sistema de control de versiones inicial, las limitaciones de CVS eran evidentes desde el principio, y CollabNet sabía que tendría que encontrar algo mejor. 

Desafortunadamente, CVS se había convertido en el estándar de facto en el mundo del código abierto en gran medida porque no había nada mejor, al menos no bajo una licencia libre. Así CollabNet decidió escribir un nuevo sistema de control de versiones desde cero, manteniendo las ideas básicas de CVS, pero sin sus fallos y defectos.

En febrero de 2000 Karl Fogel y Jim Blandy aceptaron trabajar en el proyecto, decidiendo llamarlo **Subversion**

En febrero de 2000 contactaron a Karl Fogel ofreciendole trabajar en el 
proyecto. Coincidentemente Karl y su amigo Jim Blandy habian discutido el 
diseño deun nuevo sistema de control de versiones. Jim habia pensado 
cuidadosamenre acerca de mejores formas de administrar datos versionados y ya 
habia llegado al nombre de **subversion** y al **diseño basico del almacen de 
datos** del mismo.

Cuando CollabNet llamó, Karl acepto inmediatamente trabajar en el proyecto y 
Jim consiguio que su empresa, Red Hat Software, le donara escencialmente al 
proyecto por un periodo de tiempo indefinido.

CollabNet contrató a **Karl** y a **Ben Collins-Sussman**, y el trabajo de 
diseño detallado se inició en mayo de 2000. 

Con la ayuda de algunos estimulos bien colocados de Brian Behlendorf y Jason 
Robbins de CollabNet, y desde Greg Stein, **Subversion** atrajo rápidamente a 
una comunidad de desarrolladores activos. Resultó que muchas personas habian 
encontrado las mismas experiencias frustrantes con CVS y dio a la bienvenida a 
la oportunidad de finalmente hacer algo al respecto.

El equipo de diseño original establecio algunos objetivos simples:

* No querian abrir nuevos caminos en la metodologia decontrlo de versiones,sólo
querian corregir CVS.
* Decidieron que Subversion corresponderia con las mismas caracteristicas de CVS.
* Conservar el mismo modelo de desarrollo, pero sin duplicar los defectos de 
CVS.
* Debia ser lo suficientemente similar a CVS, para que cualquier usuario del 
mismo pudiera hacer el cambio con poco esfuerzo.

Despues de 14 meses de codificación, Subversion se convirtio en 
“**self-hosting**” el 31 de agosto de 2001. Es decir, los desarrolladores de 
Subversion dejaron de usar **CVS** para gestionar su propio código fuente de 
*Subversion* y empezaron a usar **Subversion** en su lugar.

Mientras CollabNet comenzó el proyecto, y todavia financiaba una gran parte de 
la obra, Subversion funciona como la mayoria de los proyectos de código abierto.

En 2009, CollabNet trabajó con los desarrolladores de Subversion para alcanzar 
el objetivo de integrar el proyecto Subversion a la **Apache Software 
Foundation** (ASF), uno de los colectivos más conocidos de proyectos de código 
abierto en el mundo.

Raíces de Subversion, las prioridades de la comunidad y las prácticas de 
desarrollo eran un ajuste perfecto para la ASF, muchos de cuyos miembros ya 
eran contibuyentes activos de Subversion.

A principios de 2010, *Subversion* fue plenamente adoptado en la familia de la 
*ASF* de proyectos de primer nivel, se trasladó su proyecto de presencia en la 
web para http://subversion.apache.org, y fue rebautizado "**Apache 
Subversion**".

# Financial App: BANQUI.

## ÍNDICE

* [1.CONTEXTO](#1-CONTEXTO)
* [2.RESEARCH/PROBLEMÁTICA](#2-RESEARH-PROBLEMATICA)
* [3.ACCIONES](#3-ACCIONES)
* [4.ENTREGABLES](#4-ENTREGABLES)
* [5.PROCESO](#5-PROCESO)

***

# 1. CONTEXTO

Banqui es una Fintech peruana que lanza al mercado su app financiera para fomentar el ahorro. Esta tiene el objetivo de que sea una experiencia digital simple, rápida y personalizada.
Al transcurrir un tiempo después de la fase BETA se obtienen los primeros resultados donde pueden observarse varias áreas de oportunidad, las cuales se trabajarán con el equipo UX de laboratoria para el rediseño de la misma.

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Landing%20page%201.png">

# Objetivos del proyecto

*	Rediseño exitoso de la app, creando una interfaz  amigable e intuitiva.
*	Entendimiento del UX research para poder enfocarnos en los puntos principales.
*	Desarrollar testeos de usabilidad a partir de lo solicitado por Banqui.
*	Generar ideas a partir de los resultados obtenidos.
*	Cumplir con lo solicitado por nuestro stakeholder.

# 2. RESEARCH/PROBLEMÁTICA

## Problemas

* Se encontró que solamente el 10% de los usuarios que entran al landing page se registran en la app.

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/9.jpg" width="400">

*	La interfaz cuenta con varios detalles visuales que suelen confundir al usuario, esto se debe a que no es 100% intuitiva.
*	Algunos elementos visuales no son apreciados por el usuario.
*	Los usuarios valoran el ahorro sin embargo, no se ha encontrado una plataforma digital la cual los haga cumplir sus metas o donde puedan ser constantes, de igual manera la mayoría de las personas aprecia tener recordatorios de pago ya que los ayuda a programarse, es necesario que se les esté avisando constantemente que deben ahorrar.
*	El 70% de los visitantes al landing page utilizan Android, esto supone una clave importante para generar posicionamiento dentro de la appStore y la Google play.
*	Se requiere adaptar la aplicación al mercado mexicano, cubriendo el cambio de moneda (De soles a pesos) y poder utilizar palabras que sean entendibles al público mexicano.

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/10.jpg" width="400">

_Promedio de visitas al landing page que realizaron un proceso exitoso. (noviembre-enero)_

## Problemas encontrados por el equipo:

* Los usuarios observan elementos innecesarios al momento de registrarse, tal como pedir una foto de perfil. _“¿Por qué me pide fotografía?”_.
* Tienen confusión con ciertas palabras o tecnicismos usados dentro de la app, esperan que esto al no ser un banco pueda ser más amigable dentro del UX writing.
* Algunos usuarios presentan confusión con el área de gastos y otros no lo identifican dentro de la app.
* Temen por la privacidad de sus datos al no encontrar botón de “cerrar sesión”, esto indica un flujo de punta a punta incompleto.

## Objetivo del negocio

Identificar potenciales usuarios que puedan utilizar la app de forma recurrente para llegar a sus objetivos de ahorro, generar fidelidad por parte de ellos y a futuro puedan hacer uso de productos activos de Banqui. Otorgar un producto pasivo de ahorro de captación de dinero sin estrategia de marketing inmediata.

Lee la [guía de entrevista](https://docs.google.com/document/d/1E8RpddA9wQk7WBiN8NCUSu5HJD3RlgXSBuk8xs154wM/edit) 

# 3. ACCIONES

Al momento de analizar los test realizados al PMV decidimos tomar acción dentro de la interfaz, diagrama de flujo de las pantallas, UX writting, eliminamos ciertos elementos y/o modificando su lugar para generar mayor interacción con el usuario y facilidad de uso de la app.

## Interfaz amigable e intuitiva

Desarrollamos un cambio de diseño visual en todas las pantallas, modificando los colores sutilmente y la ubicación de algunos elementos, también realizamos cambios al ícono principal sin perder de vista el estilo de Banqui. Las modificaciones principales han sido con base a la guía de estilos, donde se modificó levemente los colores y algunos íconos para la componetización.

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Logo.png" width="450">

Implementamos en la pantalla de sign up una micro interacción en la parte de abajo para indicarle al usuario en que paso se encuentra y así poder validar si a futuro puede apoyar al aumento de registros, debido a que se visualizó anteriormente que los usuarios desistían en este paso al pensar que el registro tardaría “más tiempo”.
También agregamos la opción de que el usuario agregara su nombre y apellido para brindarle mayor seguridad y habilitamos un ícono dónde el usuario pueda aceptar términos y condiciones.

Se rediseñó por completo la pantalla de “gastos” creando así una interfaz más atractiva visualmente, en este espacio puede visualizarse con mayor facilidad la modificacion de la paleta de colores, este cambio se realizó con la finalidad de generar mayor confianza a los usuarios y darle más usabilidad a la app, ya que ahora se pueden visualizar mucho mejor varios botones, íconos y la letra.

Se modificó el UX writing al utilizar un lenguaje amigable, informal y adaptable para un público general, esto con el objetivo de generar cercanía y empatía con los usuarios, reemplazamos tecnicismos y en la pantalla de inicio se les recibe con un mensaje de bienvenida.

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Bienvenida.png">

Modificamos el ícono de menú y lo trasladamos a la parte superior izquierda, también modificamos el texto para que fuese más entendible hacia donde dirigía cada uno.

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Men%C3%BA%20original.png">

_(Original)_

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Men%C3%BA%20redise%C3%B1o.png">

_(Rediseño)_

## Resultados de testing.

*	La paleta de colores tuvo buena aceptación “Me agrada el color, es llamativo”, se indica que el contraste de colores es bonito, no se pierden las palabras y son visibles.
*	La gráfica en el área de “gastos” fue aceptada por los cinco usuarios finales, indicaron que visualmente es más comprensible y pueden comprender mejor como llevan la organización en sus pagos.
*	En el área de productos anteriormente se marcaba la cantidad actual en rojo, los usuarios solicitaron que se modificara ese color, ya que a pesar de que sí resaltaba, daba una impresión que esa cantidad era negativa y no la cantidad dentro de la cuenta.

**Hallazgos**

* El registro se volvió más intuitivo y entendible, después de notificar el número de cuenta por correo electrónico.
* El cambio de ciertas palabras facilitó el entendimiento del usuario y ayudó a agilizar el proceso de crear una meta.
* Los gráficos son muy valorados y entendibles por los usuarios(as)

# 4. ENTREGABLES
## Producto mínimo viable

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/PMV.png">


## Diseño de la aplicación para Android

Aquí puedes revisar nuestro prototipo en [figma](https://www.figma.com/proto/0P3axB67aepwxNtH2aY7cw/App-Financiera-Squad-3?node-id=1381%3A8436&scaling=scale-down)

## Diseño de la aplicación para iOS

Aquí puedes revisar nuestro prototipo en [figma](https://www.figma.com/proto/0P3axB67aepwxNtH2aY7cw/App-Financiera-Squad-3?node-id=1620%3A17917&scaling=scale-down)

## Video de Loom

En este link te mostramos nuestro [vídeo](https://drive.google.com/file/d/1BZKINiQjqmkjdMTdvbq8Tkz-KWLXEy_A/view?usp=sharing)

## Presentación

Tenemos nuestro pitch justo [aquí](https://www.canva.com/design/DAD7ffAhf74/Zb6fUEJ58ZF7IVpnUgVGCA/view?utm_content=DAD7ffAhf74&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton)

# 5. PROCESO

Aquí puedes visualizar nuestra primer [documentación](https://docs.google.com/document/d/1nIFK5Bk7yzmT8iPQi3ywRLk9vUOuU1d7zeLC3hA_Lx8/edit?usp=sharing)

## Sustento de las propuestas de diseño

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/1.jpg" width="400">

## Conclusiones a partir de los usuarios testeados

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Gr%C3%A1ficos.png">

## Affinity map

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Affinity%20map.png">

## Customer journey map

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Customer%20journey%20map%20banqui.png">

## User persona

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/User%20persona.png">

## Benchmark

<img src="https://github.com/AndyyAg/ux-financial-app/blob/master/Im%C3%A1genes/Benchmark.png">


¿Quieres saber como iniciamos este proyecto? Haz click [aquí](https://docs.google.com/presentation/d/1IfZN_XOQIbvlqjp_Xq1HAnaKQuQ_4FLD-s6mgxs0Ut0/edit?usp=sharing)

_Proyecto realizado el 05/2020 por Katherin Chi, Guadalupe Larios, Laura Tellez y Andrea Aguilar._

_Laboratoria, UX CDMX009-LIM012._
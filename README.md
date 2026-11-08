# practica-1
 Crear una página web comparando carreras, universidades y sus salidas
Proyecto Web: Comparativa de Universidades y Grados Universitarios
1. Descripción y objetivo del proyecto
Este proyecto diseñado por una estudiante de segundo de Bachillerato consiste en la creación, el diseño y el desarrollo de una página web que informa sobre los aspectos de la carrera universitaria ADE entre 3 universidades distintas. El objetivo principal es explicar, presentar y comparar diferentes universidades con sus titulaciones, procesos, características y aspectos generales y específicos.
Esta página web se ha convertido en una herramienta de consulta que permite a los interesados en esta carrera acceder de manera organizada, clara y concisa a información relevante sobre los programas de estudio, modo de acceso, localidad, etc.
El objetivo es ofrecer una página web fácil de navegar, visualmente fácil, accesible y que facilite la búsqueda de información y comparación de estas universidades. Con la estructura clara permite a otros adolescentes tener toda la información necesaria para tomar decisiones en una sola página.
Funcionalidades principales

Consultar información sobre estas 3 universidades (Icade, Ceu e IE)
Explorar el grado de ADE en estas universidades.
Comparar planes de estudio, criterios académicos…
Navegar distintos aspectos en mi menú
Obtener información de manera visual con tablas, acordeones, cards…
Adaptación del contenido en diversos dispositivos electrónicos

2. Estructura del proyecto y modo de apertura
Organización de archivos
El proyecto se encuentra dividido en 1 menú con 3 elementos que me permite separar la información y organizarla con HTML:
Index.html, Opciones.html y salidas.html
Estilos CSS
Imágenes
README
Cómo ejecutar el proyecto
Para visualizar correctamente el sitio web:
Descargar (o clonar) el repositorio de GitHub.
Descomprimir el proyecto (si se ha descargado como archivo ZIP, como se pide en los requisitos).
Abrir la carpeta principal del proyecto.
Abrir el archivo index.html en un navegador web.
Utilizar el menú de navegación para acceder a las diferentes páginas.
No se requiere la instalación de aplicaciones adicionales para abrir el proyecto. 
3. Tecnologías y herramientas utilizadas
El desarrollo del sitio web se ha realizado utilizando las siguientes tecnologías:
Tecnología
Aplicación en el proyecto
HTML
Estructurar organizar del contenido en mi págin web
CSS
Personalizar visualmente y diseño
Bootstrap 5.3
Diseño elaborado a través de la utilización de componentes prediseñados.
Visual Studio Code
Edición y desarrollo del código.
Git y GitHub
Control de versiones y almacenamiento del proyecto.

Versión de Bootstrap
Se ha utilizado Bootstrap 5.3, es una versión de uno de los frameworks CSS y JavaScript más populares del mundo para el desarrollo de sitios web adaptables (responsive) y modernos, que permite acceder a partes del código prediseñadas.
4. Fuentes de información y documentación
Para la elaboración de los contenidos se han consultado fuentes institucionales y documentación técnica, priorizando la información procedente de las páginas oficiales de las universidades.
Fuente
Información consultada
Fecha de consulta
IE University
Información sobre titulaciones y programas académicos.
11/2026
Universidad CEU San Pablo
Oferta académica y características de los grados.
11/2026
Universidad Pontificia Comillas (ICADE)
Planes de estudio y créditos universitarios.
11/2026
Páginas para las imágenes


11/2026













Los contenidos se han elaborado tomando como referencia estas fuentes, procurando mantener la precisión y actualidad de la información presentada. En el caso de no ser posible asegurar la veracidad a lo largo del tiempo, ha sido indicado en la página con el enlace a la página variante.
5. Créditos, recursos gráficos y licencias
Los recursos gráficos utilizados en el proyecto proceden de diferentes fuentes. Su utilización tiene como finalidad complementar la información textual y mejorar la presentación visual del sitio web.
A continuación, se detallan los recursos utilizados:
Imagen o recurso
Autor
Fuente
Licencia
Modificaciones
[Título de imagen 1]
[Autor]
[Enlace]
[Licencia]
[Cambios realizados]
[Título de imagen 2]
[Autor]
[Enlace]
[Licencia]
[Cambios realizados]
[Título de imagen 3]
[Autor]
[Enlace]
[Licencia]
[Cambios realizados]

Los recursos externos se atribuyen respetando las condiciones de sus respectivas licencias y los derechos de sus autores.
6. Decisiones técnicas de desarrollo
Durante el proceso de desarrollo he  usado diferentes decisiones técnicas para garantizar una estructura organizada, una presentación visual coherente y una navegación adecuada.
6.1. Estructuración mediante HTML
Se ha empleado HTML5para organizar semánticamente los contenidos de las diferentes páginas. Se han utilizado elementos estructurales como h1, body,..., con el objetivo de mantener una jerarquía lógica y facilitar la comprensión del documento.
Asimismo, se han utilizado tablas para presentar la información y los componentes interactivos para organizar contenidos secundarios.
6.2. Personalización mediante CSS
Se ha desarrollado una hoja de estilos CSS externa para personalizar la apariencia del sitio web.
Esto permite mantener separada la estructura del contenido de su presentación visual, facilitando el mantenimiento y la modificación del diseño.
Se han definido estilos propios para los colores, las tipografías, los márgenes, los espacios y diferentes elementos de la interfaz, buscando mantener una identidad visual uniforme en todas las páginas.
6.3. Implementación de Bootstrap 5.3
Se ha incorporado Bootstrap 5.3 para aprovechar sus herramientas de diseño prediseñadas.
Entre los elementos utilizados se encuentran el sistema de cuadrícula, las tablas, los acordeones y los componentes de navegación, las card, las columnas…
Además, se han combinado las clases de Bootstrap con estilos CSS propios para adaptar los componentes a la identidad visual del proyecto sin perder su funcionalidad.
7. Pruebas y validación del sitio web
Una vez finalizado el desarrollo, se han realizado diferentes comprobaciones para verificar el correcto funcionamiento de las páginas y su adaptación a distintos dispositivo.
7.1. Pruebas de visualización
Se ha comprobado la presentación del sitio web en diferentes anchos de pantalla:
Ordenador: comprobación de la distribución general y la correcta visualización de los elementos.
Tablet: verificación de la adaptación de las columnas, imágenes y elementos de navegación.
Móvil: comprobación de la legibilidad del contenido y la adaptación de los componentes a pantallas reducidas.
7.2. Pruebas funcionales
Se han realizado comprobaciones de los principales elementos de navegación e interacción:
Funcionamiento de los enlaces internos y externos.
Acceso a las diferentes páginas mediante el menú de navegación.
Visualización y funcionamiento de los acordeones.
Correcta presentación de las tablas.
Comprobación de las imágenes y los recursos gráficos.
Verificación de que no existan elementos desbordados o superpuestos.
Además, a través de la página https://validator.w3.org/ , he podido encontrar los errores:
7.3. Error detectado y solución aplicada
Error detectado: Elementos a lo largo del código sin cerrar o sin abrir
Causa: Al añadir texto u otros elementos, se han ido perdiendo hasta que el código estaba escaso de muchos cierres importantes.
Solución aplicada: Localizarlos a través del validator, añadirlos y comprobar que funciona
Resultado: Tras aplicar la corrección, se volvió a comprobar el funcionamiento del elemento afectado para verificar que el problema había quedado solucionado.
Error detectado: Problema con los colores, que no funcionaban
Causa: Estaba mal citado la carpeta en el html y faltaba un script al final de cada página
Solución aplicada: Renombrar al inicio de cada página la carpeta correcta de css
Resultado: Tras aplicar la corrección, se volvió a comprobar el funcionamiento del elemento afectado para verificar que el problema había quedado solucionado.
8. Evidencias del proyecto
Se incluyen cuatro capturas de pantalla que permiten comprobar la adaptación del sitio web a diferentes resoluciones y dispositivos.
Evidencia
Descripción
Captura 1
Página principal en resolución de ordenador.
Captura 2
Página principal en resolución de tablet.
Captura 3
Página principal en resolución de móvil.
Captura 4
Tabla de contenido visualizada desde un dispositivo móvil.

Pruebas de las páginas adicionales
Además de las cuatro evidencias principales, se han comprobado las restantes páginas del proyecto, verificando su estructura, navegación, visualización y funcionamiento de los componentes.
10. Herramientas externas y declaración de uso de inteligencia artificial
Para el desarrollo del proyecto se han utilizado diferentes herramientas digitales como apoyo al proceso de programación, diseño y documentación.
Entre ellas se encuentran:
Visual Studio Code: entorno utilizado para la edición y organización de los archivos.
Bootstrap: framework utilizado para facilitar la implementación de componentes y el diseño adaptable.
GitHub: plataforma utilizada para alojar el repositorio y gestionar las versiones del proyecto.
ChatGPT: herramienta de inteligencia artificial utilizada como apoyo para resolver dudas técnicas, y sintetizar información compleja difícil de entender de las páginas web utilizadas, o establecer comparaciones económicas y a nivel futuro
El código obtenido o modificado con ayuda de herramientas externas ha sido revisado y contrastado antes de incorporarse al proyecto. Se ha procurado comprender su funcionamiento y comprobar su correcta integración.
11. Repositorio y publicación
Repositorio de GitHub
El código fuente y los archivos del proyecto se encuentran disponibles en el siguiente repositorio:
Repositorio: https://github.com/mariadelrioalvarez/tic2-practica01.git 

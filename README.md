# Proyecto final Sprint I

Desarrollar un sitio web que conste de 5 secciones, cada sección deberá ser realizada por un estudiante. Los diferentes elementos del sitio web contarán con estilos personalizados creados por los estudiantes y deberán estar condensados en una sola hoja de estilos.

Para iniciar con el desarrollo del sitio web, los estudiantes deberán definir previamente aspectos como ancho del sitio (mínimo 1200px), la información a presentar en el sitio web, diseñar un mockup, borrador o bosquejo, también descargar, diseñar o crear los recursos a utilizar como imágenes, iconos, logos, entre otros y finalmente asignar responsable a cada sección.

El proyecto, deberá manejarse versionado en un repositorio remoto en github, en el que los diferentes miembros del equipo deben tener acceso, no se permite el push directo a las ramas Dev o Master.

## Secciones

Sección superior, cabecera o header: esta sección deberá contar con el menú de navegación a tres páginas internas del sitio web y su respectivo enlace al inicio. Debe contar con una imagen que ocupe el ancho del sitio.

  El menú debe de estar en un tag `<nav></nav>`.
Sección de servicios: aquí los estudiantes deberán dividir en ancho del sitio en 3 partes y en cada parte se deberá incluir un servicio. Cada servicio debe contar con una breve descripción, un logo, ícono o imagen que lo identifique y un enlace al detalle de los servicios. El elemento donde están los servicios debe de tener un `id=”services”`.

Sección de noticias: El estudiante encargado de la sección de noticias, deberá dividir el ancho del sitio web en 2 filas y dos columnas para presentar 4 noticias. Cada noticia debe contar con un resumen, una imagen y un enlace a leer la noticia completa.
  El elemento donde están los servicios debe de tener un `id=”news”`

Sección de equipo: El estudiante deberá dividir el ancho del sitio entre el número de participantes del equipo e incluir junto con cada uno una foto o imagen, el nombre y algún dato como la institución educativa, edad, pasatiempo, entre otros.
  El elemento donde están los servicios debe de tener un `id=”team”`

Sección Footer o pie del sitio: el estudiante deberá crear el pie del sitio web en donde se incluye información de contacto, deberá estar dividido en dos partes, en una se tendrá la información del sitio web como el motivante del desarrollo y el enlace al repositorio de github, y en la otra los contacto de los miembros del equipo con sus nombres y roles. La sección debe de estar en un tag <footer></footer>

## Proceso

Para este proyecto se realizo esta serei de pasos:

- Primero contactar con los miembros del equipo para el desarrollo del poryecto.
- Se establecieron reunionos para determinar requerimientos y generar esquemas para la posible solucion. Esto se realizo mediante herramientas viruales para la comunicacion.
- Se dividio el trabajo en tareas y se asignaron a cada integrante.
- Cada integrante realizo los pasos de Usuario Colaboradores para poder trabajar en su tarea.
- Cada integrante realizo la seccion correspondiente, investigo si es necesario para dar un buen resultado final.
- Se establecio nuevamente una reunion para revisar los resultados obtenidos.
- Por ultimo se unierion todos las versiones pertienentes en github.


## Usuario principal

-Descargar el repositorio y descomprimir 
http://github.com/Tecnalia.Cilco-3/semana-1

-Copiar la carpeta creada dentro del Work Directory
semana-1-183 --> WorkDirectory

-Inicializar el repositorio en el nuevo destino
git init 

-Compartir acceso con colaboradores
En Github crear organización - invitar colaboradores - crear repositorio

-Sincronizar repositorio local con el remoto
git remote add semana-1-183 https://github.com/MISION-TIC2022/Semana-1-183.git
git push -b semana-1-183 dev 

## Usuarios colaboradores

-Crear la carpeta Work Directory
-Clonar el repositorio en la carpeta Work Directory
-Crear nueva rama
git checkout -b nueva_rama

-Delegar tareas.
Implementacion de sección Header.
Implementacion de sección Servicios.
Implementacion de sección Noticias.
Implementacion de sección Equipo.
Implementacion de sección Footer.

-Codificar tarea asiganda en index.html y el style.css del repositorio clonado.

-Revisar funiconamiento de la tarea implementada.


## Union de Secciones realizadas

-Guardar los arvhivos.

-Añadir los archivos al repositorio.
git add .

-Añadir los correspondientes commit.
git commit -m "Descripcion del cambio realizado"

-Verificar si todos los commit fueron relizados .
git log

-Volver a la rama dev.
git checkout dev

-Combinar lso archivos para actulizacion de cambios.
git merge nueva_rama

-Verificar el estado
git status

-Subir dichos camibios al repositorio remoto.
git push origin dev

-Cargar los cabios realizados por todas las tareas.
git pull origin dev


## Autores:
-Gustavo Gómez

-Mariver Milena Garcia Santana

-William Nicolás Buitrago Ballestas

-Harold Isaias Sanchez Cabezas

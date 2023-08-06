# Diario del Programador

## Prólogo 

La idea de este documento es poder documentar todos los conocimientos adquiridos respondiendo a preguntas que me van surgiendo y ordenándolas de forma sistemática para un rápido acceso. Además la idea es hacer todo un mapa de los conocimientos que voy necesitando para desarrollarme en el ámbito del Desarrollo Web pero con conceptos generales y útiles para el ingreso a cualquier área de la computación y el desarrollo de software 

Además busco poder dar explicaciones directas, sencillas y al punto. Buscando relacionar conceptos abstractos con las tecnologías de las que me surgieron las dudas o de las que se relacionan esos conceptos. 

Sería una idea para el futuro que todos los que tengan dudas que quieran agregar al documento se podría hacer un libro del desarrollador que englobe dudas de todo tipo e introducciones a la mayor cantidad de áreas del desarrollo de software.

Por otro lado acá voy a ir desarrollando una guía para entender cómo va a ser este documento.
Enlaces a documentación externa 
## Tabla de contenidos

- Recomendaciones y consejos

  - Cómo empezar con una nueva tecnología

- Conceptos Básicos

  - Diferencia entre librería, módulo, paquete, dependencia
  - Diferencia entre update y upgrade
  - Que es una interfaz GUI | CLI

- Lógica básica de programación 

  - Que es un lenguaje y su relación con la programación? 
  - Que lógica tiene la programación? 
  - Que hace que un lenguaje sea de programación? 

- JavaScript

  - Introducción 
  - Sintaxis 
  - Funcionalidades 

- React
  - React Native
    - Que es React Native 
    - Diferencia hay con React JS
    - Como comienzo un proyecto? 
      - Entorno de desarrollo 
      - Flujo de trabajo 
      - Expo GO | React Native CLI
      - Visualización de mi proyecto u otros 

  - React JS
    - Que es React JS
    - Que diferencia hay con React Native
    - Como comienzo un proyecto? 
      - Entorno de desarrollo 
      - Flujo de trabajo 
      - Visualización de mi proyecto u otros 

- HTML

- CSS

- Atajos de teclado 

- Visual Studio Code 


## Conceptos Básicos

###  Diferencia entre librería, módulo, paquete, dependencia

- Módulo. La pieza más pequeña de software. Puede ser un conjunto de métodos o funciones para usarlo.

- Paquete. Colección de módulos.

- Librería. Colección de paquetes.

- Framework. Conjunto de librerías. No solo ofrecen funcionalidades, sino que también arquitectura. Uno no incluye un framework, uno incluye código dentro de un framework.

- Dependencia. Se refiere a cuán interconectados están los módulos. O sea, que tu software depende de módulos para funcionar.

### Diferencia entre update y upgrade 

“update” se refiere a actualizar la lista de paquetes disponibles, mientras que “upgrade” se refiere a la instalación o actualización real de esos paquetes en tu sistema.

## ReactNative

Para visualizar un proyecto en React Native deberiamos saber si se esta usando Expo Go o React Native CLI, ya que la diferencia principal es que en Expo Go no tenemos acceso a los archivos base de IOS y Android mientras que en React Native CLI si. Por otro lado en Expo Go solo necesitaremos la aplicacion y unos sencillos pasos, mientras que en React Native CLI tendremos que hacer mas configuraciones del entorno de desarrollo.

## Visualizalizar un proyecto de ReactNative

1. instalar dependencias: Estando dentro de la carpeta del proyecto, ejecutamos el comando _npm(1) install_ para que instale todas las dependencias del proyecto.

(\*1) Dependiendo del gestor de paquetes que usemos varia el comando

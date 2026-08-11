# Motín en la Cárcel — Entorno de Realidad Virtual

Experiencia de Realidad Virtual desarrollada en Unity que recrea el patio de una cárcel durante una misión de búsqueda y captura relacionada con un plan de huida.

## Descripción

El proyecto consiste en la creación de un entorno 3D inmersivo en el que el usuario se encuentra en el patio de una cárcel durante una misión de búsqueda y captura.

La experiencia permite al usuario desplazarse por el entorno mediante los controladores de realidad virtual e interactuar con diferentes elementos de la escena.

El escenario combina elementos de diferentes recursos de Unity Asset Store, materiales, texturas, iluminación y elementos propios de la configuración del proyecto para crear un entorno penitenciario detallado y realista.

## Escena

La escena principal del proyecto es:

**Motín en la cárcel**

El entorno representa el patio de una cárcel e incluye diferentes elementos relacionados con el escenario, como:

- Edificios y estructuras penitenciarias.
- Vallas y elementos de seguridad.
- Vehículos policiales.
- Personajes policiales.
- Cámaras de vigilancia.
- Puertas metálicas.
- Bancos y mobiliario.
- Elementos de iluminación.
- Vegetación.
- Elementos decorativos y urbanos.

## Realidad Virtual

El proyecto utiliza las herramientas de Realidad Virtual de Unity para proporcionar una experiencia inmersiva.

Se han utilizado:

- XR Plugin Management.
- XR Interaction Toolkit.
- XR Origin.
- Controladores de Realidad Virtual.
- Character Controller.
- Character Controller Driver.

El usuario puede desplazarse utilizando el joystick izquierdo de los controladores y controlar la rotación mediante el joystick derecho.

## Interacción

La escena incorpora elementos interactivos que permiten al usuario interactuar con determinados objetos del entorno.

También se incluyen personajes policiales que pueden ser destruidos durante la experiencia.

Los personajes realizan desplazamientos a velocidad moderada en horizontal sobre su posición y eje de inicio.

Para la configuración de las interacciones se utilizan:

- Prefabs.
- Colliders.
- Rigidbody.
- XR Simple Interactable.
- Etiquetas para la identificación de objetos.
- Scripts de movimiento.
- Scripts de destrucción.

## Scripts

El proyecto incorpora scripts desarrollados en C# para controlar el comportamiento de diferentes elementos de la experiencia.

### Script de movimiento

Controla el desplazamiento de los personajes dentro de la escena, realizando movimientos horizontales a una velocidad moderada.

### Script de destrucción

Permite activar la destrucción de determinados objetos mediante la interacción del usuario con los controladores de Realidad Virtual.

El sistema de interacción está configurado para permitir la activación mediante los controles de los dispositivos VR.

## Navegación

El sistema de navegación está diseñado para proporcionar un movimiento sencillo y cómodo dentro del entorno virtual.

El usuario puede:

- Desplazarse mediante el joystick izquierdo.
- Rotar mediante el joystick derecho.
- Explorar el patio de la cárcel en primera persona.
- Interactuar con diferentes elementos del escenario.

La navegación utiliza `Character Controller` y `Character Controller Driver`.

## Entorno 3D

Uno de los principales objetivos del proyecto es la creación de un entorno penitenciario detallado.

Para ello se han utilizado diferentes recursos de Unity Asset Store, además de materiales y texturas para mejorar el aspecto visual de la escena.

Entre los recursos utilizados se encuentran elementos relacionados con:

- Entornos industriales.
- Edificios.
- Vehículos policiales.
- Personajes.
- Cámaras de vigilancia.
- Puertas.
- Vallas.
- Vegetación.
- Mobiliario.
- Iluminación.
- Terreno.
- Cielos y skyboxes.

## Optimización y experiencia de usuario

El proyecto presta especial atención a la organización del entorno y a la experiencia del usuario dentro de la aplicación.

Se han incluido:

- Una jerarquía organizada.
- Una estructura ordenada de los recursos.
- Abundantes elementos de diseño del entorno.
- Elementos visuales para aumentar el realismo.
- Optimización del escenario.
- Sistema de navegación sencillo y accesible.

## Tecnologías

- Unity
- C#
- XR Plugin Management
- XR Interaction Toolkit
- Realidad Virtual
- Character Controller
- Character Controller Driver
- Unity Asset Store
- Modelos 3D
- Materiales y texturas

## Estructura del proyecto

El proyecto completo se encuentra organizado de la siguiente forma:

RV_Pract 1 - Motín en la Cárcel/
│
├── Assets/
│   └── Recursos, escenas, scripts, prefabs, materiales y elementos 3D
│
├── Build PC/
│   └── Ejecutable del proyecto para PC
│
├── Packages/
│   └── Paquetes y dependencias de Unity
│
├── ProjectSettings/
│   └── Configuración del proyecto Unity
│
└── Vídeo/
    └── Vídeo de demostración del proyecto

Ejecución

El proyecto dispone de dos formas de ejecución: mediante el proyecto de Unity o mediante el ejecutable para PC incluido en Build PC.

Opción 1 — Ejecutable para PC

La forma más sencilla de probar la aplicación es utilizar el ejecutable incluido en la carpeta:

Build PC/

Pasos:

Descargar el proyecto completo desde Google Drive.
Entrar en la carpeta Build PC.
Ejecutar el archivo .exe incluido.
Conectar las gafas de Realidad Virtual y sus controladores al PC.
Iniciar la experiencia.
Opción 2 — Abrir el proyecto en Unity

Para modificar o ejecutar el proyecto desde Unity:

Descargar el proyecto completo.
Abrir Unity Hub.
Seleccionar Open / Add project from disk.
Seleccionar la carpeta raíz RV_Pract 1 - Motín en la Cárcel.
Abrir el proyecto con la versión de Unity utilizada durante su desarrollo.
Esperar a que Unity importe los paquetes y recursos.
Abrir la escena Motín en la cárcel desde Assets.
Conectar las gafas de Realidad Virtual y sus controladores al PC.
Pulsar Play en Unity.
Proyecto completo

Debido al tamaño del proyecto y a la cantidad de recursos 3D utilizados, el proyecto completo se encuentra disponible en Google Drive.

Incluye:

Carpeta Assets.
Carpeta Packages.
Carpeta ProjectSettings.
Ejecutable para PC en Build PC.
Vídeo de demostración.

Acceder al proyecto completo en Google Drive

Demostración

La carpeta Vídeo contiene una grabación del funcionamiento de la experiencia de Realidad Virtual.

Recursos utilizados

Durante el desarrollo se han utilizado diferentes recursos disponibles en Unity Asset Store para la construcción del entorno, personajes, vehículos, objetos, iluminación, vegetación y texturas.

Mi aportación

Mi participación en el proyecto se centró en el desarrollo y configuración de la experiencia de Realidad Virtual, colaborando en la creación y organización del entorno, la configuración de la navegación e interacción y la integración de los diferentes elementos necesarios para el funcionamiento de la escena.

Entre las tareas realizadas se incluyen:

Desarrollo y configuración del entorno de Realidad Virtual.
Organización de la escena y sus diferentes elementos.
Configuración del sistema de navegación.
Integración de elementos 3D y recursos del entorno.
Configuración de elementos interactivos.
Trabajo con prefabs, colliders y Rigidbody.
Integración y configuración de scripts de movimiento y destrucción.
Configuración del sistema XR.
Pruebas de funcionamiento de la experiencia con las gafas de Realidad Virtual.
Trabajo en equipo

Proyecto desarrollado en grupo por:

Marc Forés Doménech
Carlos Molina Castellanos

Grado en Tecnología Digital y Multimedia
Universitat Politècnica de València

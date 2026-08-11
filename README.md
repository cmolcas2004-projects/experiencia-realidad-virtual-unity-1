# Motín en la Cárcel

Experiencia de Realidad Virtual desarrollada en Unity en la que el usuario se encuentra en el patio de una cárcel durante una misión de búsqueda y captura relacionada con un plan de huida.

## Descripción

El proyecto consiste en el desarrollo de un entorno de Realidad Virtual ambientado en el patio de una cárcel, diseñado para ofrecer una experiencia inmersiva en la que el usuario debe desenvolverse dentro del escenario mientras interactúa con diferentes elementos del entorno.

La escena recrea un entorno carcelario utilizando diferentes modelos, objetos, materiales y elementos decorativos procedentes de Unity Asset Store.

El usuario puede desplazarse por el escenario mediante los controles de Realidad Virtual y enfrentarse a personajes que se desplazan por el entorno.

Entre las principales características se incluyen:

* Entorno 3D ambientado en el patio de una cárcel.
* Experiencia inmersiva mediante gafas de Realidad Virtual.
* Movimiento mediante el joystick izquierdo.
* Rotación mediante el joystick derecho.
* Personajes policiales que se desplazan por el escenario.
* Objetos y elementos decorativos distribuidos por el entorno.
* Uso de colliders y rigidbodies para las interacciones físicas.
* Interacción mediante XR Simple Interactable.
* Elementos configurados para poder ser destruidos durante la experiencia.
* Diseño del escenario mediante diferentes assets, materiales y texturas.
* Experiencia sencilla y accesible para el usuario.

## Tecnologías

* Unity
* C#
* XR Plugin Management
* XR Interaction Toolkit
* Unity Input System
* Character Controller
* Character Controller Driver
* Blender / modelos 3D
* Unity Asset Store

## Escena principal

El proyecto cuenta con una escena principal:

**Motín en la cárcel** – Entorno 3D correspondiente al patio de una cárcel en el que se desarrolla la experiencia de Realidad Virtual.

El escenario incluye diferentes elementos como edificios, vallas, vehículos, personajes, cámaras de vigilancia, mobiliario urbano, árboles, iluminación y otros elementos decorativos.

## Interacciones y movimiento

El usuario puede desplazarse por el escenario utilizando los controladores de Realidad Virtual.

* **Joystick izquierdo:** desplazamiento del personaje.
* **Joystick derecho:** rotación de la cámara/personaje.
* **Personajes policiales:** realizan desplazamientos horizontales a velocidad moderada sobre su posición y eje de inicio.
* **Objetos interactivos:** utilizan los componentes de interacción proporcionados por XR Interaction Toolkit.
* **Elementos destruibles:** están configurados para responder a las acciones de interacción del usuario.

La navegación utiliza **Character Controller** y **Character Controller Driver**, proporcionando un movimiento adecuado para la experiencia de Realidad Virtual.


## Ejecución

> **IMPORTANTE:** para ejecutar la experiencia de Realidad Virtual se necesitan unas gafas de RV compatibles conectadas al PC.

### Opción 1 – Ejecutable

El proyecto incluye un ejecutable ya generado dentro de la carpeta **Build PC**, por lo que no es necesario abrir Unity para probar la experiencia.

Para ejecutar el proyecto:

1. Descargar el proyecto completo desde Google Drive.
2. Mantener la estructura de carpetas del proyecto.
3. Entrar en la carpeta **Build PC**.
4. Conectar las gafas de Realidad Virtual al ordenador.
5. Ejecutar el archivo `.exe` incluido en dicha carpeta.
6. Esperar a que se inicie la aplicación.
7. Utilizar los controladores de las gafas para desplazarse e interactuar con el entorno.

Esta es la forma recomendada para probar directamente la experiencia sin necesidad de modificar el proyecto.

### Opción 2 – Abrir el proyecto en Unity

También es posible abrir el proyecto completo mediante Unity.

1. Descargar el proyecto completo.
2. Extraerlo si se encuentra comprimido.
3. Abrir **Unity Hub**.
4. Seleccionar **Add / Open Project**.
5. Seleccionar la carpeta raíz `RV_Pract1`.
6. Abrir el proyecto con la versión de Unity utilizada para su desarrollo.
7. Comprobar que los paquetes y la configuración de XR están correctamente cargados.
8. Conectar las gafas de Realidad Virtual al ordenador.
9. Abrir la escena **Motín en la cárcel**.
10. Ejecutar el proyecto desde Unity mediante **Play**.

## Assets utilizados

Para la creación del entorno se han utilizado diferentes recursos de Unity Asset Store, entre ellos:

* Pillars Pack.
* Industrial Props Kit.
* Lighting Generator.
* Police Car & Helicopter.
* Police Officer.
* Metal Door.
* Surveillance Camera.
* City Props Pack.
* Plastic Trash Bins.
* Realistic Tree Pack.
* Black Walnut Tree.
* Street Lamps.
* Barrels.
* 3D Dumbbell.
* Low Poly Old School Gym Equipment.
* Simple Bench.
* Outdoor Bench.
* Street Lights Pack.
* Street Bench.
* AllSky Free – Sky / Skybox Set.
* Realistic Terrain Textures.
* Tower The Last.
* Chainlink Fences.
* Storage Building.

Los enlaces y referencias de los assets utilizados se encuentran recogidos en la documentación del proyecto.

## Mi aportación

Participación en el desarrollo del proyecto de Realidad Virtual, colaborando en la creación y configuración del entorno, la integración de elementos del escenario y la implementación de funcionalidades necesarias para el funcionamiento de la experiencia.

También se participó en las pruebas de funcionamiento, navegación e interacción del proyecto con dispositivos de Realidad Virtual.

## Material del proyecto

El material completo del proyecto, incluyendo los archivos de Unity, el ejecutable para PC y el vídeo de demostración, se encuentra disponible en el siguiente enlace:

' https://drive.google.com/drive/folders/1aCJ2JBKyxeiuJy_Y3BtcZ0bWowuWnfKN?usp=sharing&utm_source=chatgpt.com '

## Documentación

La documentación del proyecto recoge información sobre el entorno desarrollado, los integrantes del grupo, los elementos utilizados, la configuración de Realidad Virtual, los prefabs, scripts, navegación, ejecutable y aspectos adicionales incorporados a la experiencia.

## Proyecto académico

Proyecto desarrollado en grupo, dentro del **Grado en Tecnología Digital y Multimedia** de la **Universitat Politècnica de València (UPV)**.

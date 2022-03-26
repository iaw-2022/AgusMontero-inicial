# Proyecto Inicial

## Idea a Implementar

Un sitio web donde los usuarios puedan subir imágenes y clasificarlas por medio de etiquetas (o *tags*) y agruparlas en galerías.
Otras posibles funcionalidades a implementar:
- Importar imágenes desde la PC o la Web.
- Compartir galerías entre usuarios.
- Implementar un tipo de usuario *"premium"* que tenga acceso a más funciones que un usuario básico.
- Descarga de galerías enteras.
- Integrar un servicio externo de reconicimiento de imágenes que sugiera tags al subir una imágen.

## Diagrama ER

![Diagrama de clases](https://user-images.githubusercontent.com/20066395/160221572-e9389ce9-8474-43fd-aee9-16db771ecbda.png)

## Actualizaciones a los datos

Los usuarios podrán:
- Importar imágenes desde distintas fuentes las cuales se asociarán a la cuenta del mismo. A estas se le podrán modificar ciertas propiedades, como los tags o el nombre, o tambíen elimnarlas de la colleción.
- Crear galerías y agregar o remover imágenes a cada una. Una imágen puede pertenecer a varias galerías.
- Declarar sus galerías personales como públicas para que otros usarios puedan accederlas.
- Marcar galerías e imágenes públicas de otros usuarios como favoritas, o importarlas a sus cuentas lo cual creará una copia de ellas.

## Información del Servicio Web

Cada usuario podrá acceder a las imágenes y galerías, tanto las asociadas a su cuenta como las públicas, incluyendo la información pertinente a estas (dimensiones, tamaño, etc.).

## Visualización y Acceso a la Información

Los usuarios tendrán acceso a una galería general donde verán todas las imagenes asociadas a su cuenta o podrán abrir una de las galerías que hayan creado.
Las galerías se mostratrán como una grilla de miniaturas de las imágenes contenidas en ellas. Al seleccionar una imagen, se mostrará la misma junto sus datos y otras opciones.
Habrá un buscador para buscar contenido según los tags deseados junto con otros parámetros.

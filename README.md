# Clon-Paint 🎨

¡Bienvenido al proyecto Clon-Paint! Este es un clon básico de una aplicación de dibujo similar a Microsoft Paint, construido utilizando HTML, CSS y JavaScript. La aplicación permite a los usuarios dibujar, borrar, seleccionar colores, y dibujar rectángulos en un lienzo interactivo.

## Características

- **Dibujo**: Dibuja líneas libres en el lienzo.
- **Borrador**: Elimina partes específicas del dibujo utilizando una herramienta de borrado.
- **Dibujar Rectángulos**: Dibuja rectángulos y cuadrados en el lienzo.
- **Selector de Color**: Selecciona y cambia colores de dibujo.
- **Limpiar Lienzo**: Borra todo el contenido del lienzo con un solo clic.

## Tecnologías Utilizadas

- **HTML**: Para la estructura básica de la aplicación.
- **CSS**: Para el estilo y diseño del lienzo y las herramientas.
- **JavaScript**: Para la lógica de interacción, manejo del lienzo, y funciones de dibujo.

## Lógica Implementada en JavaScript

El JavaScript de este proyecto maneja la mayoría de las interacciones del usuario con el lienzo de dibujo. A continuación, se detallan algunos de los aspectos clave de la lógica implementada:

- **Manejo del Lienzo**: Utilizamos el contexto de `CanvasRenderingContext2D` para realizar todas las operaciones de dibujo y borrado en el lienzo.
- **Modos de Dibujo**: Se implementaron diferentes modos (dibujo, borrado, rectángulo, y selector de color) utilizando un patrón de estado. Dependiendo del modo seleccionado, el comportamiento del ratón cambia.
- **Eventos de Ratón**: Se utilizan eventos de `mousedown`, `mousemove`, y `mouseup` para capturar las acciones del usuario y dibujar en el lienzo.
- **Rectángulos y Cuadrados**: El modo de rectángulo permite al usuario dibujar tanto rectángulos normales como cuadrados perfectos
- **Selector de Color**: Utilizamos la API `EyeDropper` para permitir a los usuarios seleccionar cualquier color del lienzo y utilizarlo para dibujar.
- **Optimización de Redibujado**: Al dibujar rectángulos, se guarda y restaura el estado del lienzo para evitar problemas de redibujado.

## Instalación y Uso

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/Clon-Paint.git

<h1 align='center'>Juego Amigo Secreto de Alura Latam y Oracle Next Education</h1>

Mi nombre es Cindy Acosta y este es el juego de amigo secreto como parte del curso de programación de Alura Latam y Oracle Next Education. Este es un proyecto simple en JavaScript para realizar un sorteo de "Amigo Secreto" de manera aleatoria. Permite agregar nombres a una lista, evitar duplicados y sortear de manera justa.

<p align="center">
   <img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green">
   <img src="https://img.shields.io/badge/Programa-ORACLE_LATAM-blue">
   <img src="https://img.shields.io/badge/Programa-NEXT_EDUCATION_G8-red">
   <img src="https://img.shields.io/badge/JUEGO%20AMIGO%20SECRETO-8A2BE2">
</p>


### Índice

- 🎯 [Características](#caracteristicas)
- ⚙️ [Requisitos](#requisitos)
- 📖 [Cómo usarlo](#como-usarlo)
- 🏗️ [Estructura del código](#estructura-del-codigo)
- 🎨 [Personalización](#personalizacion)


---

## 🎯 Características

- Agregar amigos a la lista con validación de nombres.
- Mostrar los amigos ingresados en una lista.
- Sortear amigos sin repeticiones hasta que todos sean seleccionados.
- Reiniciar automáticamente el sorteo cuando todos han sido elegidos.
- Ingresar nombres presionando la tecla **Enter**.

## ⚙️ Requisitos

Este proyecto usa únicamente HTML, CSS y JavaScript, por lo que **no necesitas instalar dependencias**. Solo debes ejecutar el archivo en un navegador moderno.

## 📖 Cómo usarlo

1. **Ingresar nombres** en el campo de texto y presionar el botón \"Agregar Amigo\" o la tecla **Enter**.
2. Los nombres válidos se mostrarán en una lista.
3. Presionar el botón **\"Sortear Amigo\"** para seleccionar un participante al azar.
4. Se mostrarán los nombres sorteados uno por uno, sin repeticiones.
5. Cuando todos los amigos sean sorteados, el sistema **se reiniciará automáticamente**.
6. También puedes reiniciar manualmente el sorteo en cualquier momento.

## 🏗️ Estructura del código

El código JavaScript se organiza en las siguientes funciones principales:

- **`agregarAmigo()`**: Agrega un amigo validando que el nombre sea válido y no esté repetido.
- **`mostrarAmigos()`**: Muestra la lista de amigos agregados en la interfaz.
- **`sortearAmigo()`**: Sortea un amigo de la lista, evitando repeticiones hasta que todos sean elegidos.
- **`reiniciarSorteo()`**: Reinicia la lista de amigos y el sorteo.
- **Evento `keydown` en el input**: Permite agregar nombres usando la tecla **Enter**.

## 🎨 Personalización

Si deseas modificar el proyecto, puedes hacer lo siguiente:

- 🖌️ **Estilos CSS**: Agregar estilos para mejorar la apariencia de la interfaz.
- 💾 **Almacenamiento Local**: Implementar almacenamiento local para conservar la lista de amigos al recargar la página.
- 🎭 **Efectos Visuales**: Agregar animaciones al sorteo de nombres para hacerlo más interactivo.


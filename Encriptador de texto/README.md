# Encriptador y Desencriptador de Texto

Este proyecto es una aplicación web interactiva que permite a los usuarios encriptar y desencriptar texto utilizando un algoritmo de sustitución personalizado. Diseñada con una interfaz intuitiva, la aplicación ofrece funcionalidades adicionales como copiar resultados, limpiar entradas y mantener un historial de operaciones recientes.

## Características

- Encriptación de texto: Transforma el texto ingresado según reglas predefinidas.
- Desencriptación de texto: Revierte el proceso de encriptación.
- Copiado rápido: Permite copiar el resultado al portapapeles con un clic.
- Limpieza de entrada: Facilita borrar el texto de entrada rápidamente.
- Historial de operaciones: Guarda las últimas 5 operaciones realizadas.
- Interfaz responsiva: Diseñada para funcionar en diversos dispositivos y tamaños de pantalla.

## Cómo funciona

El algoritmo de encriptación reemplaza las vocales por palabras específicas:

- 'e' se convierte en 'enter'
- 'i' se convierte en 'imes'
- 'a' se convierte en 'ai'
- 'o' se convierte en 'ober'
- 'u' se convierte en 'ufat'

La desencriptación realiza el proceso inverso.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript

## Estructura del Proyecto
encriptador de texto
│
├── index.html
├── styles.css
├── script.js
└── README.md

## Funciones principales:
- `encriptar(texto)`: Reemplaza ciertas letras con palabras específicas.
- `desencriptar(texto)`: Revierte el proceso de encriptación.
- `clickCopiarTexto()`: Crea un botón para copiar el texto resultante.
- `clickEncriptar()`: Maneja el evento de clic para encriptar el texto.
- `clickDesencriptar()`: Maneja el evento de clic para desencriptar el texto.
- `mostrarResultado(texto)`: Muestra el resultado en la interfaz.
- `limpiarResultado()`: Limpia el resultado y el campo de entrada.
- `agregarAlHistorial(textoOriginal, textoResultado, tipo)`: Agrega una entrada al historial.
- `mostrarHistorial()`: Muestra el historial de operaciones.
- `toggleHistorial()`: Alterna la visibilidad del historial.







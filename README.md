# Calculadora de construcción

## Descripción
La **Calculadora de construcción** es una aplicación web desarrollada en HTML, CSS y JavaScript que permite calcular **área, perímetro y volumen** de figuras geométricas comunes en contextos de construcción.

La aplicación ofrece dos formas de interacción:
- Uso mediante **interfaz gráfica**.
- Uso mediante **modo consola**, utilizando ventanas emergentes del navegador.

---

## Figuras disponibles
La aplicación permite realizar cálculos para las siguientes figuras:

- Rectángulo  
- Cuadrado  
- Círculo  

---

## Funcionalidades principales

### Interfaz gráfica
- Selección de figura desde un menú desplegable.
- Ingreso de medidas según la figura seleccionada:
  - Rectángulo: Largo y Ancho.
  - Cuadrado: Lado.
  - Círculo: Radio.
- Ingreso de **altura opcional** para el cálculo de volumen.
- Botones disponibles:
  - **Calcular**: realiza el cálculo y registra la operación.
  - **Limpiar**: reinicia los campos del formulario.
- Visualización inmediata de:
  - Área (m²)
  - Perímetro (m)
  - Volumen (m³), solo si se ingresa altura.
- Mensajes de estado que confirman el registro del cálculo.

---

### Modo consola
- Acceso a un modo alternativo de uso mediante el botón **Activar consola**.
- El usuario interactúa con la aplicación a través de:
  - Ventanas `prompt()` para ingresar datos.
  - Ventanas `alert()` para mostrar resultados.
  - Impresión del historial en la consola del navegador mediante `console.log()`.
- El ingreso de datos se valida utilizando estructuras de repetición (`while`), evitando valores inválidos.
- Los resultados obtenidos en modo consola también se almacenan en el historial general.

---

## Historial de operaciones
- Cada cálculo realizado se registra automáticamente.
- El historial muestra:
  - Tipo de figura.
  - Medidas ingresadas.
  - Área, perímetro y volumen calculados.
  - Origen de la operación (Interfaz o Consola).
- Funciones disponibles sobre el historial:
  - Filtrar operaciones por tipo de figura.
  - Visualizar un resumen de cálculos.
  - Mostrar el historial completo.
- El historial también se encuentra disponible en la **consola del navegador**.

---

## Resumen de cálculos
- La aplicación puede generar un resumen de las operaciones registradas.
- El resumen se construye a partir del historial y se imprime en consola.
- Se utilizan métodos de arreglo para procesar la información.

---

## Validación de datos
- No se permiten valores vacíos cuando son obligatorios.
- No se permiten valores menores o iguales a cero.
- En modo consola, los datos inválidos vuelven a solicitarse hasta que sean correctos.
- El volumen solo se calcula cuando se ingresa una altura válida.

---

## Estructuras de programación utilizadas
- Funciones para cálculos matemáticos.
- Condicionales (`if / else`) para control de flujo.
- Estructura `switch` para selección de figura.
- Ciclos `while` para validación en modo consola.
- Arreglos (`Array`) para el historial de operaciones.
- Objetos (`Object`) para representar resultados y operaciones.
- Métodos de arreglos como `forEach` y `map` para mostrar historial y resumen.
- Uso de la consola del navegador para depuración y visualización de datos.

---

## Ejecución del proyecto (macOS)
1. Abrir la carpeta del proyecto.
2. Ejecutar el archivo `index.html` en un navegador web.
3. Para abrir la consola del navegador en Mac:
   - Presionar **Option + Command + I**
   - Seleccionar la pestaña **Consola**

---

## Evidencia de funcionamiento
El proyecto incluye capturas de pantalla que muestran:
- Interfaz gráfica en funcionamiento.
- Registro de cálculos en el historial.
- Uso del modo consola con ventanas emergentes.
- Impresión del historial y resumen en la consola del navegador.

---

## Autor
- Carla

# 🏷️ Programa Etiquetas Agora - Asisman

Generador automático de etiquetas de precios en formato PDF, diseñado específicamente para la gestión eficiente de productos bajo la marca **Asisman**. Este programa permite convertir datos de un archivo CSV en etiquetas profesionales listas para imprimir.

## 🚀 Características

* **Formatos Estándar:** Generación de etiquetas en tamaños 62x40mm y 62x30mm.
* **Diseño Profesional:** Incluye automáticamente el prefijo "P.V.P" y el símbolo de Euro (€).
* **Legibilidad Mejorada:** Nombre del producto en tamaño 12pt y precio destacado en 20pt.
* **Totalmente Portable:** El ejecutable (.exe) contiene todos los recursos necesarios (logos e iconos) sin depender de carpetas externas.
* **Apertura Automática:** Tras generar el PDF, el programa lo abre automáticamente para su revisión e impresión.

## 📋 Requisitos

Para el correcto funcionamiento, asegúrese de cumplir con lo siguiente:
1.  Tener el archivo `etiquetas.csv` en la misma carpeta que el programa.
2.  El archivo CSV debe contener las columnas: `Producto` y `Precio`.

## 💻 Instalación y Uso

### Para Usuarios (Descargar Ejecutable)
1.  Ve a la sección de [Releases](https://github.com/TU_USUARIO/TU_REPOSITORIO/releases) de este repositorio.
2.  Descarga el archivo `generadorEtiquetas.exe`.
3.  Colócalo en una carpeta junto a tu archivo `etiquetas.csv`.
4.  Ejecuta el programa y selecciona el formato deseado.

### Para Desarrolladores (Python)
Si deseas ejecutar o modificar el código fuente:
1.  Clona el repositorio: `git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git`
2.  Instala las dependencias:
    ```bash
    pip install pandas fpdf Pillow
    ```
3.  Ejecuta el script: `python generadorEtiquetas.py`

## 🛠️ Tecnologías utilizadas

* **Python 3.x**
* **Tkinter:** Para la interfaz gráfica de usuario (GUI).
* **FPDF:** Para la generación de documentos PDF.
* **Pandas:** Para el procesamiento y lectura de datos CSV.
* **PyInstaller:** Para la creación del archivo ejecutable independiente.

## 📂 Estructura de archivos

* `generadorEtiquetas.py`: Código fuente principal.
* `etiquetas.csv`: Archivo de entrada de datos (ejemplo).
* `/imprimir`: Carpeta generada automáticamente donde se guardan los PDFs resultantes.

---
Generado con ❤️ por Rubén Aparicio Robles


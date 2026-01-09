📘 Manual de Usuario: Generador de Etiquetas Asisman
Este programa ha sido diseñado para automatizar la creación de etiquetas de precios en formato PDF a partir de un archivo de datos (CSV), permitiendo elegir entre dos tamaños estándar.
📋 Requisitos Previos
Para que el programa funcione correctamente, se deben cumplir estas condiciones:
1.	Archivo de datos: Debes tener un archivo llamado exactamente etiquetas.csv en la misma carpeta donde se encuentra el programa ejecutable.
2.	Formato del CSV: El archivo debe tener, al menos, dos columnas con los siguientes encabezados exactos:
o	Producto: Nombre o descripción del artículo.
o	Precio: El valor numérico del producto.
3.	Permisos: El programa debe tener permisos de escritura en la carpeta donde se encuentra para poder crear la subcarpeta de salida.

________________________________________

🚀 Instrucciones de Uso
Paso 1: Preparar los datos
Asegúrate de que tu archivo etiquetas.csv esté actualizado.
•	Nota sobre símbolos: No te preocupes por el símbolo del Euro (€); el programa lo añade automáticamente si el precio no lo tiene.
•	Nota sobre Office: El programa es compatible con archivos generados tanto en versiones antiguas como modernas de Excel o Bloc de Notas.
Paso 2: Ejecutar el programa
Haz doble clic en el archivo generadorEtiquetas.exe. Se abrirá la interfaz gráfica con el logo de Asisman.
Paso 3: Selección del formato
En la pantalla principal verás dos botones. Haz clic en el que necesites según tu papel de etiquetas:
•	Formato 62x40mm: Genera etiquetas más grandes (habitualmente 3 columnas por fila).
•	Formato 62x30mm: Genera etiquetas más estrechas (ajusta automáticamente el espacio del precio).
Paso 4: Generación y Apertura
Una vez hagas clic:
1.	El programa creará automáticamente una carpeta llamada imprimir (si no existe ya).
2.	Generará el archivo PDF dentro de esa carpeta.
3.	Apertura automática: El programa intentará abrir el PDF inmediatamente con tu visor predeterminado (Adobe Reader, Chrome, etc.) para que puedas imprimirlo.

________________________________________

📂 Ubicación de los Archivos
•	Entrada: [Carpeta del programa]/etiquetas.csv
•	Salida: [Carpeta del programa]/imprimir/Etiquetas_62x40.pdf (o 30).

________________________________________

⚠️ Resolución de Problemas (Errores Comunes)
Error mostrado	Causa posible	Solución
"No se encuentra etiquetas.csv"	El archivo no está en la carpeta o tiene otro nombre.	Renombra tu archivo a etiquetas.csv y muévelo junto al programa.
"Archivo en uso / Cierre el PDF"	Intentas generar etiquetas mientras tienes el PDF anterior abierto.	Cierra el archivo PDF en tu lector (Adobe/Chrome) y pulsa el botón de nuevo.
"Error al leer CSV"	El archivo está mal estructurado o los encabezados no son correctos.	Revisa que la primera fila tenga las palabras Producto y Precio.

________________________________________

💡 Consejos de Impresión
Al imprimir el PDF generado:
•	Asegúrate de configurar la escala de impresión al 100% (o "Tamaño Real") en los ajustes de tu impresora para que las medidas de 62mm coincidan exactamente con tu papel.
•	Verifica que la orientación del papel esté en Vertical.


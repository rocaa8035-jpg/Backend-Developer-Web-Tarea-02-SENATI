# Backend-Developer-Web-Tarea-02-SENATI

Esta tarea trata sobre la creación de un software capaz de buscar un producto en un array de productos mediante el id dado en el input presionando un boton "Buscar". El producto se mostrara con sus datos con un boton "Calcular" que permitira calcular el total (precio x cantidad). Si el producto no es encontrado, se mostrará un mensaje "Producto no encontrado.".

## Para la tarea se utilizó:

- PHP
- CSS
- imagenes ".png"
- servidor APACHE en XAMPP

<img width="415" height="239" alt="image" src="https://github.com/user-attachments/assets/d95ca465-d6e4-402b-b425-8087a0369666" />
<img width="573" height="1105" alt="image" src="https://github.com/user-attachments/assets/51c644b4-a346-48a1-986a-5d1fa86c2beb" />
<img width="354" height="646" alt="image" src="https://github.com/user-attachments/assets/6d081a88-9013-4ea5-8f4c-869f90a89601" />
<img width="354" height="635" alt="image" src="https://github.com/user-attachments/assets/ef0b369f-7f02-46ed-984e-6bcda3755cf3" />
<img width="354" height="599" alt="image" src="https://github.com/user-attachments/assets/430dc5ad-9961-43df-a635-407ec8c268c5" />
<img width="354" height="635" alt="image" src="https://github.com/user-attachments/assets/adc8a2e6-b3ed-4461-9ec8-2f0e2bebc5f7" />

# Guía de Instalación y Despliegue de la Aplicación Web

Este documento contiene las instrucciones necesarias para instalar el entorno de desarrollo local XAMPP y ejecutar esta aplicación web basada en PHP.

---

## Requisitos Previos

Antes de comenzar, asegúrate de tener descargado el instalador de XAMPP para el sistema operativo desde la página oficial de Apache Friends.

---

## Paso 1: Instalar XAMPP

1. Ejecuta el archivo instalador de XAMPP que descargaste.
2. Si aparece una advertencia sobre el Control de Cuentas de Usuario (UAC), haz clic en **Aceptar**.
3. En la ventana de selección de componentes, asegúrate de que **Apache** y **PHP** estén seleccionados (puedes dejar el resto por defecto).
4. Sigue el asistente de instalación haciendo clic en **Next** (Siguiente) y mantén la ruta de instalación por defecto: `C:\xampp`.
5. Haz clic en **Finish** (Finalizar) para completar la instalación y abrir el Panel de Control de XAMPP.

---

## Paso 2: Ubicar el Proyecto en el Servidor Local

Para que el servidor web pueda interpretar los archivos PHP, el proyecto debe estar dentro de la carpeta raíz de XAMPP.

1. Abre el explorador de archivos de Windows.
2. Dirígete a la siguiente ruta exacta:
   `C:\xampp\htdocs`
3. Dentro de `htdocs`, crea una nueva carpeta para tu proyecto. Por ejemplo, nombra la carpeta como `mi-app-web`.
4. Copia o mueve todos los archivos de este repositorio dentro de esa nueva carpeta.

La estructura debe quedar así:
`C:\xampp\htdocs\mi-app-web\Informe de Practica IP02`

---

## Paso 3: Iniciar el Servidor Web

1. Abre el **Panel de Control de XAMPP** (puedes buscarlo en el menú de inicio de Windows).
2. Localiza el módulo llamado **Apache**.
3. Haz clic en el botón **Start** (Iniciar) situado al lado de Apache.
4. Sabrás que está funcionando correctamente cuando el texto "Apache" se resalte en color verde y muestre los números de los puertos de red.

---

## Paso 4: Ejecutar la Aplicación en el Navegador

Una vez que el servidor esté activo y los archivos en su lugar, abre tu navegador web preferido (Chrome, Edge, Firefox, etc.) e ingresa la siguiente URL en la barra de direcciones:

```url
http://localhost/mi-app-web/Informe%20de%20Practica%20IP02/venta.php
```

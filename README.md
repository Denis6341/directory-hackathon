# 📒 Agenda Telefónica en Java  

¡Bienvenido a mi proyecto de **Agenda Telefónica**! 📱  
Este programa en **Java** te permite gestionar contactos de manera sencilla y rápida desde consola.  

---

## ✨ Funcionalidades  
La agenda cuenta con las siguientes opciones:  

✅ Añadir contacto (máximo 10 contactos)  
✅ Buscar contacto por nombre  
✅ Modificar el número de un contacto existente  
✅ Eliminar contactos  
✅ Listar todos los contactos guardados  
✅ Verificar espacios disponibles en la agenda  
✅ Menú interactivo para navegar entre las opciones  

---

## 🛠️ Tecnologías utilizadas  
- ☕ **Java** (Programación orientada a objetos)  
- 🗂️ **HashMap** para almacenar los contactos  
- 🖥️ **Consola interactiva** con `Scanner`  

---

## 📂 Estructura del código  
- **Clase principal**: `Directory`  
- **Clase interna**: `Contacto` (nombre y teléfono)  
- Métodos principales:
  - `añadirContacto()`  
  - `buscarContacto()`  
  - `modificarTelefono()`  
  - `eliminarContacto()`  
  - `listarContactos()`  
  - `espaciosLibres()`  
  - `ejecutarMenu()`  

---

## 🚀 Cómo ejecutar el proyecto  
1. Clona este repositorio en tu máquina:  
   ```bash
   git clone https://github.com/tuusuario/agenda-telefonica-java.git
Abre el proyecto en tu IDE favorito (Eclipse, IntelliJ, VSCode con extensión Java).

Compila y ejecuta la clase Directory.

¡Listo! Ya puedes empezar a guardar tus contactos.

---

## 🖼️ Vista previa en consola

=============================

      AGENDA TELEFÓNICA 

Elige una opción del menú: 

1. Añadir contacto
2. Buscar un contacto
3. Modificar número de contacto
4. Eliminar contacto
5. Ver lista de contactos
6. Verificar espacios libres restantes
7. Salir de la agenda

---

## 🌟 Ejemplo de uso

Ingrese el nombre del contacto: Juan

Ingrese el teléfono: 123456789

`----------------------------------`

Contacto añadido exitosamente.

`----------------------------------`

Ingrese el nombre del contacto a buscar: Juan

`----------------------------------`

El número es: 123456789

`----------------------------------`


---

## 🎯 Objetivo del proyecto
El propósito de este proyecto es practicar programación orientada a objetos en Java, reforzando conceptos como:

Clases internas

Métodos auxiliares

Manejo de excepciones (InputMismatchException)

Uso de colecciones (HashMap)

---

## 💡 Próximas mejoras
🔹 Permitir almacenar más de 10 contactos

🔹 Exportar la agenda a un archivo .txt o .csv

🔹 Añadir validaciones más completas para el número de teléfono

🔹 Interfaz gráfica (JavaFX o Swing)

---

## 👩‍💻 Autor
Creado con ❤️ por Den, en colaboración con Yeudiel y Dante, miembros de la cohorte 58 de Generation.

📌 Proyecto de práctica con Java


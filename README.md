# Ejercicio 01: Docker + Apache + Herramientas de Edición
**Estudiante:** María Soledad De Francesco Del Giorgio  
**Carrera:** Tecnicatura Superior en Programación Full Stack (2do Año)

## 📝 Descripción del Proyecto
Este ejercicio consistió en la configuración de un entorno de desarrollo basado en contenedores utilizando Docker. Se trabajó sobre una imagen de servidor web Apache con PHP para visualizar contenido estático y dinámico, integrando herramientas de edición remota.

## 🛠️ Tareas Realizadas

### 1. Optimización del Dockerfile
Se modificó la imagen base original para asegurar la compatibilidad con las extensiones de edición remota de Visual Studio Code:
* **Imagen utilizada:** `php:8.2-apache`
* **Instalación de paquetes:** Se automatizó la instalación del editor **Vim** mediante el comando:
  ```dockerfile
  RUN apt-get update && apt-get install -y vim

 ![Resultado Web](./ejemplos/ejem01/resultados.png) 
 
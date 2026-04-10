# Propuesta TP DSW

## Grupo
### Integrantes
* 53948 – Altamirano, Marianela Estefanía
* 54027 – Sayago, Valentina Nair
* 54207 – Spirce, Yasmín
 
### Repositorios
* Frontend: https://github.com/dsw-2026/frontend
* Backend: https://github.com/dsw-2026/backend

## Tema: Adopción de Mascotas
### Descripción

Sistema de gestión de adopción de mascotas que conecta adoptantes con publicadores (refugios y rescatistas) de toda la Argentina. Permite registrar usuarios, publicar animales disponibles, evaluar la compatibilidad entre adoptantes y mascotas, y dar seguimiento a cada caso de adopción. Su objetivo es agilizar el proceso de adopción y garantizar vínculos responsables y duraderos.

### Modelo
![Modelo_de_Dominio_Version_2](https://github.com/user-attachments/assets/2e5ee04c-a109-4f86-80c5-ec0585ac6359)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Macota<br>3. CRUD Provincia|
|CRUD dependiente|1. CRUD Solicitud {depende de} CRUD Adoptante, CRUD Mascota<br>2. CRUD Característica {depende de} CRUD Mascota|
|Listado<br>+<br>detalle| 1. Listado de mascotas disponibles para adoptar filtrado por especie, muestra nombre, imagen, edad, tamaño, sexo, caracter, energia, vacunación y castración => detalle muestra datos completos de la mascota<br> 2. Listado de solicitudes de adopción en proceso, filtrado por fecha descendente, muestra código de solicitud, nombre adoptante, nombre publicador, días transcurridos desde fecha solicitud => detalle CRUD Solicitud|
|CUU/Epic|1. Solicitar adopción de una mascota<br>2. Publicar mascota en adopción|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Localidad<br>3. CRUD Provincia<br>4. CRUD Adoptante<br>5. CRUD Publicador<br>6. CRUD Rescatista<br>7. CRUD Refugio<br>8. CRUD Mascota<br>9. CRUD Especie<br>10. CRUD Característica<br>11. CRUD Solicitud <br>12. CRUD Seguimiento<br>13. CRUD Formulario<br>14. CRUD Pregunta <br>15. CRUD Opcion_Respuesta <br>16. CRUD Respuesta|
|CUU/Epic|1. Solicitar adopción de una mascota<br>2. Publicar mascota en adopción<br>3. Adoptar una mascota|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |-|
|CUU/Epic|-<br>-|
|Otros|-|


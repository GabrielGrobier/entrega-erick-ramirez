# Proyecto Móvil: Registro de Mascotas en una Veterinaria

## Introducción al Caso
La veterinaria **"Vida Animal"** ha crecido rápidamente en los últimos años, lo que ha generado la necesidad de digitalizar su sistema de registro y seguimiento de mascotas atendidas. Actualmente, los doctores llevan un registro manual en hojas de papel, lo que ocasiona errores, pérdida de información y dificultades para consultar el historial de las mascotas.

Para solucionar este problema, se desarrollará una aplicación móvil que permita a los doctores registrarse, iniciar sesión y gestionar la información de las mascotas que atienden. Esta aplicación será práctica, sencilla y eficiente, y estará disponible en dispositivos Android a través de la Amazon Appstore.

---

## Requerimientos del Proyecto

### Roles principales
1. **Doctores Veterinarios:** Pueden registrarse, iniciar sesión y acceder a los datos de las mascotas que les han sido asignadas.
2. **Administrador:** (Opcional, si se quiere complejidad adicional). Puede gestionar los usuarios doctores y asignar mascotas a cada uno.

### Funcionalidades principales
- **Registro de doctores:** Permite que los doctores creen una cuenta proporcionando su nombre, correo electrónico, especialidad y contraseña.
- **Inicio de sesión:** Los doctores pueden autenticarse para acceder a la aplicación.
- **Gestión de pacientes (mascotas):**
  - Crear registros de mascotas con información básica: nombre, especie, raza, edad, nombre del dueño, contacto del dueño y motivo de la visita.
  - Consultar la lista de mascotas asignadas.
  - Actualizar la información de las mascotas (solo los doctores asignados pueden hacerlo).
  - Eliminar registros de mascotas en caso necesario.

---

## Entregas del Proyecto

### Primera Entrega: Vistas y Funcionalidad Básica
En esta fase se diseñarán las pantallas principales y se implementarán las validaciones necesarias. 

1. **Pantallas requeridas:**
   - Pantalla de bienvenida con opciones de registro e inicio de sesión.
   - Pantalla de registro de doctores (con validaciones como: correo válido, contraseña con al menos 6 caracteres).
   - Pantalla de inicio de sesión.
   - Pantalla principal con menú que permita acceder a las funciones de:
     - Ver pacientes asignados.
     - Registrar nuevas mascotas.
     - Editar o eliminar registros existentes.
   - Formulario para agregar o editar mascotas con validaciones (por ejemplo, campos obligatorios como nombre, especie y contacto del dueño).

2. **Validaciones:**
   - Los campos no deben estar vacíos.
   - Verificación de formato en el correo electrónico.
   - Contraseña con requisitos mínimos.

---

### Segunda Entrega: Persistencia y Conexión a APIs
En esta fase se implementará el almacenamiento de datos y la integración con servicios externos:

1. **Persistencia:**
   - Almacenar los datos de doctores y mascotas en una base de datos local o remota.
   - Implementar funcionalidades para consultar, agregar, actualizar y eliminar datos.

2. **Conexión con APIs:**
   - Consumir una API externa para obtener datos adicionales, como información de razas de mascotas o tips de cuidado.
   - Registrar y consultar la información en un servidor remoto.

3. **Sincronización:**
   - Asegurar que los datos puedan sincronizarse entre dispositivos en caso de usar una base de datos remota.

---

### Tercera Entrega: Publicación
En la etapa final, se optimizará la aplicación para ser publicada en una tienda de aplicaciones:

1. **Optimización:**
   - Asegurar que la aplicación funcione correctamente en dispositivos móviles y cumpla con los requisitos de la Amazon Appstore.

2. **Pruebas finales:**
   - Realizar pruebas funcionales y de usabilidad para identificar y corregir errores.

3. **Publicación:**
   - Generar un archivo APK firmado y publicar la aplicación en la Amazon Appstore con una descripción, capturas de pantalla y configuraciones necesarias.

---

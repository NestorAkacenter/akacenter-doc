# Manual de Pruebas: Test-Formulario

Este documento describe las funcionalidades y el uso de las dos secciones principales del sistema de test **Test-Formulario**: **Clean Data** y **New User**. Está dirigido al personal de testing para asegurar la correcta ejecución de pruebas sin afectar datos reales del sistema.

---

## 1. Acceso a las secciones del sistema

Las pruebas se realizan mediante acceso web a las siguientes URLs:

| Sección     | URL                                                                 |
|------------|---------------------------------------------------------------------|
| Clean Data | [https://formularios-anexos-9xigd.ondigitalocean.app/test/clean_data](https://formularios-anexos-9xigd.ondigitalocean.app/test/clean_data) |
| New User   | [https://formularios-anexos-9xigd.ondigitalocean.app/test/new_user](https://formularios-anexos-9xigd.ondigitalocean.app/test/new_user) |

> **Nota:** Se recomienda utilizar un navegador actualizado para garantizar la compatibilidad con todas las funcionalidades del sistema.

---

## 2. Sección: Clean Data

<img width="432" height="352" alt="image" src="https://github.com/user-attachments/assets/40778ef4-9f87-42bc-ba05-b5b2d112b3dd" />

La sección **Clean Data** permite limpiar o eliminar datos de usuarios específicos mediante su **NIF**.

### 2.1 Instrucciones generales

- Ingresar el **NIF exacto** del usuario que se desea modificar.  
- Verificar cuidadosamente los datos ingresados para evitar afectar información de otros usuarios.

### 2.2 Opciones disponibles

- **Limpiar datos personales:**  
  Elimina todos los datos del usuario excepto su NIF.

- **Borrar cursos:**  
  Elimina todos los cursos asociados al usuario.

- **Borrar usuario completo:**  
  Elimina al usuario del sistema, sin borrar los cursos asociados.

> **Nota:** Para eliminar un usuario junto con sus cursos y asi limpiar registro completamente, se deben seleccionar **Borrar cursos** y **Borrar usuario completo** simultáneamente.

---

## 3. Sección: New User

<img width="769" height="619" alt="image" src="https://github.com/user-attachments/assets/eb243b04-203b-43b3-97b6-854a11741145" />

La sección **New User** permite la creación de nuevos usuarios en el sistema.

### 3.1 Datos del usuario

- **Nombre:** opcional.  
- **NIF:** obligatorio (no es necesario que sea real).

### 3.2 Creación de cursos

Para asignar cursos a un nuevo usuario:

1. Ingresar el **nombre del curso**.  
2. Especificar el **correo electrónico** donde se recibirán notificaciones del curso.  
3. Adjuntar un **anexo específico**.  
4. Para agregar más cursos, utilizar el botón **"+ Agregar curso"**.

> Al crear el usuario, el sistema generará un `hashNIF`, que se añade al final de la URL del formulario.
<img width="926" height="87" alt="image" src="https://github.com/user-attachments/assets/98284a86-978c-4aac-a523-7e3e9d6b08fd" />

**Ejemplo de URL de formulario generado:**  
https://formularios-anexos-9xigd.ondigitalocean.app/formulario/<hashNIF>

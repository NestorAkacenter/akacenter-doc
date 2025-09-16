# Formulario de Preinscripción - Notas de la versión

**Versión:** 2.0.0
**Fecha:** 16/09/2025  

Este formulario permite a los **estudiantes** gestionar sus inscripciones a cursos mediante **anexos** personalizados. Cada curso tiene un anexo específico y el formulario se adapta automáticamente para mostrar los campos correspondientes. Al final, el estudiante puede **firmar el anexo** para completar su inscripción.

---

## ✨ Novedades y cambios principales

- **Guardado de cursos seleccionados**  
  Ahora, al guardar datos o firmar un anexo, se conservan los cursos que el estudiante o gestión había seleccionado previamente.

- **Campos condicionales**  
  Algunos datos se muestran solo en casos específicos, en lugar de mostrarse siempre, haciendo el formulario más claro y sencillo. (Ejemplo el campo de grupo de cotización)

- **Aviso de cursos no seleccionados**  
  Si el estudiante no tiene cursos seleccionados o inscritos, aparecerá un aviso y el formulario no se mostrará.
<img width="968" height="385" alt="image" src="https://github.com/user-attachments/assets/3f9155a7-378c-4d11-bba7-7ef19e157db0" />

- **Nuevas páginas de error**  
  - Por ejemplo, si no se detecta al usuario en la base de datos, se mostrará una página de error clara.
<img width="988" height="767" alt="image" src="https://github.com/user-attachments/assets/d14fe5c4-b5f6-445c-be50-3cf9e7bc8e45" />

- **Actualización de localidad en firma**  
  Al cambiar la localidad de residencia del usuario, se actualiza automáticamente en la sección de firma, aunque todavía puede cambiarse manualmente.

- **Generación de PDF de anexos**  
  - La tipografía ahora es **monospace** para mayor claridad.  
  - El contenido escrito en los campos se ajusta automáticamente al tamaño de la celda.
<img width="1026" height="387" alt="image" src="https://github.com/user-attachments/assets/c7fe863b-f520-4ae6-ba4a-131e9a073e86" />

  

- **Limitación de longitud de campos**  
  Todos los campos del formulario tienen ahora un límite de caracteres para evitar errores o desbordes.

- **Almacenamiento en Drive**  
  Todos los anexos generados se guardan en una carpeta de Google Drive con la siguiente lógica:

"dni_anexo_nombreAlumno_nombreCurso" ejemplo: 1344511C_I_LAURA_1.-CURSO_DE_INGLES


- **Registro en la base de datos**  
Cada formulario guarda un historial con fechas de:  
  Creación  
  Actualización  
  Firma del anexo  

- **Mejoras de interfaz**  
- El botón **"Volver al formulario"** durante la firma ahora está en la esquina superior izquierda.
  <img width="1831" height="515" alt="image" src="https://github.com/user-attachments/assets/78e04623-dd40-41d6-8836-507994e9af63" />

- El botón **"Completar y enviar preinscripción"** es ahora más grande y visible para facilitar su uso.

---

## ✅ Resumen
Con estas mejoras, el **formulario de preinscripción** es más **intuitivo, seguro y visualmente claro**, facilitando la inscripción de los estudiantes y el seguimiento de los anexos generados.

  

# Administrar Veterinaria

## Descripción
Una página web para registrar mascotas en una clínica veterinaria. Este proyecto ya se ha hecho muchas veces pero con diferenes tecnologias, ahora se realizo usuando React, TypeScript, Tailwind, Zustand, React hook Form. Los usuarios ingresan datos como el nombre del paciente, propietario, email, fecha de alta, y síntomas. 
Toda la información es validada con react hook form.  
Los datos pueden editarse fácilmente o eliminarsea. Se usa persist para toda la información se guarde en el Local Storage para persistencia. 

## Características
- Formulario de registro: Los usuarios completan los siguientes campos:
  - Nombre del paciente.
  - Nombre del propietario.
  - Email.
  - Fecha de alta.
  - Síntomas.
- Validación de datos: La validacion de campos se hace con react hook form.
- Visualización de registros:
  - Los datos registrados se muestran en tarjetas.
- Edición de registros:
  - Al presionar el boton editar, los datos se rellenan automáticamente en el formulario.
  - Los cambios se guardan y se actualiza la tarjeta correspondiente.
- Eliminación de registros:
  - Al presionar el boton de eliminar, el registro se elimina.
- Persistencia: Todos los datos se almacenan en el Local Storage para mantenerlos después de recargar la página.
  
## Tecnologías utilizadas
- React
- TypeScript: Toda la lógica está implementada mediante clases.
- Tailwind CSS: Los estilos principales están definidos en un archivo output.css.
  
## Uso
1. Abre la página web en tu navegador.
2. Completa todos los campos del formulario de registro y haz clic en el botón Registrar Paciente.
  - Los datos se mostrarán en una tarjeta del lado derecho.
3. Opciones disponibles en las tarjetas:
  - Editar: Haz clic en el boton de editar para modificar los datos del paciente. Los datos se rellenarán automáticamente en el formulario.
  - Eliminar: Haz clic en el boton de eliminar para eliminar el registro. 
4. Los datos se guardarán automáticamente en el Local Storage y estarán disponibles al recargar la página.

## Instalación
1. Clona este repositorio:
git clone https://github.com/Hugo9591/VeterinariaTs.git
2. cd a la carpeta
3. npm install.
4. abrir navegador http://localhost:5173

# Aplicaci-n-de-asistencia
La aplicación de control de asistencia busca registrar de manera eficiente la entrada y salida de los usuarios (estudiantes, empleados o personal autorizado). El sistema debe permitir almacenar los registros de asistencia, consultar historiales y generar reportes básicos. Este proyecto se desarrolla con el propósito de automatizar un proceso que comúnmente se realiza de manera manual y propensa a errores.
## Objetivos
- Registrar la hora de entrada y salida de cada usuario.
- Mantener un historial organizado y accesible de asistencias.
- Reducir errores provocados por el registro manual.
- Facilitar el control para supervisores o docentes.
- Mejorar la eficiencia del proceso de validación de asistencia.

# Requerimientos funcionales 
1. Permitir que el usuario registre entrada.
2. Permitir que el usuario registre salida.
3. Validar que un usuario no registre doble entrada o doble salida consecutiva.
4. Guardar automáticamente la fecha y hora del registro.
5. Permitir la consulta del historial de asistencias.
6. Generar reportes simples por fecha o usuario.
# Requerimientos no funcionales
1. La interfaz debe ser sencilla y fácil de usar.
2. El sistema debe ser confiable en la captura de datos.
3. Se debe almacenar la información de manera segura.
4.  El tiempo de respuesta debe ser mínimo al realizar un registro.
# Tabla de pruebas
| N  | Descripción	| Entrada	|  Resultado esperado |	Estado |
|------|---------------------|-------------------|------------------------------------|-------|
| CP01 | Registro de entrada |	ID Usuario válido	| Se guarda fecha y hora de entrada	| ✔ |
| CP02 | Registro de salida |	ID Usuario válido con entrada | previa	Se guarda fecha y hora de salida |	✔ |
| CP03 | Doble entrada |	ID Usuario sin haber registrado salida |	Se bloquea registro y se muestra advertencia |	✔ |
| CP03 | Consulta de historial | ID Usuario |	Muestra lista de asistencias |	✔ |
| CP05 |	Usuario inexistente |	ID no registrado |	Mensaje de error |	✔ |
## tipo de mantenimiento prupuesto
El tipo de mantenimiento recomendado para esta aplicacion es:
# Mantenimiento Perfectivo
Se selecciona este tipo porque, una vez funcionando el sistema, será necesario mejorar características como:
- Interfaz más intuitiva,
- Nuevos filtros de búsqueda,
- Mejor generación de reportes,
- Incorporación de validaciones adicionales.
- Estas mejoras no corrigen errores, sino que aumentan la calidad y funcionalidad del sistema según las necesidades del usuario.
# Reflexión sobre el control de versiones
El uso de control de versiones (como Git) es fundamental en el desarrollo de esta aplicación porque:
- Permite mantener un historial ordenado de cambios realizados.
- Facilita el trabajo colaborativo entre desarrolladores.
- hace posible revertir errores sin perder avances importantes.
Hace posible revertir errores sin perder avances importantes.
Ayuda a documentar el progreso y comprender la evolución del proyecto.
Gracias al control de versiones, el desarrollo se vuelve más seguro, organizado y eficiente.
Hace posible revertir errores sin perder avances importantes.
Ayuda a documentar el progreso y comprender la evolución del proyecto.
Gracias al control de versiones, el desarrollo se vuelve más seguro, organizado y eficiente.

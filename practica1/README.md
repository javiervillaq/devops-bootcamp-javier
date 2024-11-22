# Practica 1
## Crecacion de pipeline para agregar usuarios de sistema linux y pipeline para elimnar usarios de sistema linux

El pipeline para agregar usuarios al sistema de linux, necesita tres parametros para ejecutarse correctamente.

- LOGIN 
- NOMBRE_COMPLETO
- DEPARTAMENTO

---

Luego realiza las siguientes acciones:

1. Crear variables para almacenar los datos de entrada
2. Generar la contraseña temporal
3. Se creal el grupo en caso de no existir
4. Creo el usuario
5. Añadir el usuario al grupo
6. Forzar cambio de contraseña en el próximo inicio de sesión
7. Configurar permisos del directorio home
8. Salidas de validación almacenadas en un archivo txt

Finalmente retorno en los artifacts el archivo txt con la data.
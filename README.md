Rol de Ansible: Usuarios
========================

Rol de Ansible para configurar usuarios en Debian.

Requerimientos
--------------

Ninguno.

Variables del Rol
-----------------

| Variable | Descripción |
| -------- | ----------- |
| usuarios_administrador | Nombre del usuario con permisos de administrador. |

Dependencias
------------

Ninguna.

Libro de Ejemplo
----------------

```yaml
---
 - hosts: servidores
   roles:
      - cloudcxn.usuarios
```

License
-------

MIT.

Información del Autor
---------------------

El rol fue creado en noviembre del 2022 por Byron Quezada para
[Cloud CxN](https://www.cloudcxn.com).

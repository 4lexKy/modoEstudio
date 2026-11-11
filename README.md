[Versión 0.7.2]: #
# modoEstudio - Notificaciones periódicas para mirar lejos y mantener la salud de los ojos

Se trata de un script que envia notificaciones mediante notify-send (libnotify-bin) cada 15 minutos para recordar mirar lejos unos segundos. Esto evitará la fatiga en los ojos, reducirá el dolor de cabeza y retrasará el deterioro natura de la vista con los años.

---
## Estado del proyecto
Terminado, funciona correctamente.

### Ficheros
- modoEstudio: Fichero con código principal
- LICENSE: contenido de la licencia
- README.md: información del proyecto
- .gitignore: define elementos a ignorar

---
## Instalación
No requiere instalación

### Lenguaje
- Bash
### Dependencias
Sí, tiene dependencias de:
- libnotify-bin (Debian/Ubuntu)
### Sistemas operativos compatibles
Probado en:
- Debian

---
## Uso
Es un script de bash por lo que símplemente se le llama con ./modoEstudio
Se puede modificar añadiendo programas para que se abran al mismo tiempo, como carpetas, páginas webs o programas específicos.

### Ejemplo de uso
**./modoEstudio**
>- Una notificación te recordará cada 15 minutos que mires lejos.
>- Se ejcuta el primer plano, no se puede cerrar la terminal.

**./modoEstudio -d**
>- Se envia la notificación periódica en segundo plano
>- Se puede cerrar la terminal, modo daemon (d)

---
## Recomendación
Para un uso mas ágil se puede crear una carpeta para script de forma que todos los que se añadan se puedan llamar desde la propia terminal como cualquier otro comando.

Esto se puede conseguir añadiendo a ~/.bashrc la línea:

```bash
    export PATH=$PATH:/ruta/a/carpeta/con/scripts
```

---
## Licencia
Este proyecto está licenciado bajo GPLv2 - consulta el archivo LICENSE para más detalles.

---
## Autor
>**Alex**
- Github: [https://github.com/4lexKy](https://github.com/4lexKy)
- Email: [alex.correu@pm.me](mailto:alex.correu@pm.me)

---

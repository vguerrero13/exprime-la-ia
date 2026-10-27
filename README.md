# Taller Exprime la IA — GrowUp

Sitio del taller "Exprime la IA" de GrowUp, pensado para publicarse en GitHub Pages.

## Contenido

- `index.html` — página de inicio con el temario de las 8 sesiones (las sesiones 1 a 7 tienen guía disponible; la 8 aparece como "Próximamente").
- `sesion-01.html` a `sesion-07.html` — guías de las sesiones 1 a 7.
- `practica/` — páginas de práctica de la Sesión 5 (directorio de proveedores y formulario), usadas con Claude en Chrome.

A medida que se construyan las siguientes sesiones, se agregan como `sesion-08.html` y se actualiza `index.html` para des-bloquear la tarjeta.

## Cómo publicarlo en GitHub Pages

1. Entrá a [github.com](https://github.com) y creá un repositorio nuevo (puede ser público o privado — si es privado, GitHub Pages requiere un plan de pago para publicarlo).
2. Subí el contenido de esta carpeta a ese repositorio. Si ya tenés Git configurado en tu computadora, desde esta misma carpeta podés correr:
   ```
   git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
   git branch -M main
   git push -u origin main
   ```
   (Este proyecto ya tiene un repositorio Git inicializado localmente con un primer commit.)
3. En GitHub, entrá a **Settings → Pages** del repositorio.
4. En "Source", elegí la rama `main` y la carpeta `/ (root)`.
5. Guardá. GitHub te va a dar una URL del estilo `https://TU-USUARIO.github.io/TU-REPOSITORIO/` — esa es la que compartís con los estudiantes.

## Notas

- Los archivos HTML son autocontenidos (sin dependencias externas más que las fuentes de Google Fonts), así que no necesitan build ni instalación de nada.
- El logo de GrowUp está incrustado directamente en cada HTML (como imagen en base64), por eso no hay una carpeta de imágenes separada.

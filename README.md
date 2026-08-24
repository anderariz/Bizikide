# Komunitatea

Demo frontend para la gestión sencilla de comunidades de vecinos.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `manifest.json` y `sw.js` a la raíz del repositorio.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/root`.
6. Guarda los cambios.

## Funciones incluidas

- Perfil Vecino / Administrador.
- Alta de problemas con foto.
- Estados de seguimiento.
- Tabla de profesionales.
- Importación CSV.
- Solicitud simulada de presupuestos.
- Bandeja de presupuestos.
- Votaciones.
- Tareas del administrador.
- Diseño responsive y botones grandes para facilitar el uso a personas mayores.
- PWA básica instalable.

## Pendiente para producción

La demo guarda los datos solo en memoria. Para convertirla en una aplicación real hay que conectar:

- Supabase: usuarios, comunidades, incidencias, proveedores, presupuestos, votos y archivos.
- Servicio de correo: envío de solicitudes y recepción de respuestas.
- Autenticación y permisos por comunidad.

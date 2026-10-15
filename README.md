# TESI 1111 · Gestión de Usuarios y Permisos

Presentación web interactiva (Unidad 3, inciso B) con tema de terminal hacker y un laboratorio
con dos terminales simuladas: Linux (bash) y Windows (PowerShell).

- Sitio estático: un solo archivo, `index.html`. Sin build ni dependencias.
- Navegación: `←` `→`, `T` abre el laboratorio, `I` info extra, `F` pantalla completa.

## Ejecutar

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python -m http.server 8080
```

## Publicar

Es un sitio estático: publica la raíz del repositorio, sin comando de build y con `index.html` como entrada.

# TESI 1111 · Gestión de Usuarios y Permisos

Presentación web interactiva (Unidad 3, inciso B) con tema de terminal hacker y un laboratorio
con dos terminales simuladas: Linux (bash) y Windows (PowerShell).

- Sitio estático, sin build ni dependencias. Cada presentación es un solo archivo:
  - `index.html`: Unidad 3, inciso B · Gestión de Usuarios y Permisos.
  - `unidad3C.html`: Unidad 3, inciso C · Seguridad en Sistemas Operativos, con el Laboratorio 3C
    (Seguridad de Windows, PowerShell y una terminal de práctica de ufw).
- Navegación del inciso B: `←` `→`, `T` abre el laboratorio, `I` info extra, `F` pantalla completa.
- Navegación del inciso C: `←` `→`, `I` índice, `F` pantalla completa.

## Ejecutar

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python -m http.server 8080
```

## Publicar

Es un sitio estático: publica la raíz del repositorio, sin comando de build y con `index.html` como entrada.

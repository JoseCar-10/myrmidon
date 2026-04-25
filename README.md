# MYRMIDON Intel Console

Consola web para investigacion de IOCs (IP, dominio, URL, hash y email) con enriquecimiento desde un backend worker.

## Requisitos

- Navegador moderno (Chrome, Edge, Firefox, Safari).
- Conexion a internet (usa Google Fonts y el worker remoto).

## Ejecutar rapido

Como es una app estatica, tienes dos opciones:

1. Abrir directamente `index.html` en el navegador.
2. Levantar un servidor local simple:

```bash
cd /Users/josecarloscabrera/Desktop/IOC
python3 -m http.server 8080
```

Luego abrir:

`http://localhost:8080`

## Archivo principal

- `index.html`: UI + estilos + logica JS completa.

## Notas

- El endpoint backend configurado es:
  `https://myrmidon-api.id24011.workers.dev`
- Si el backend falla, la consola mostrara mensaje de error en la barra roja.

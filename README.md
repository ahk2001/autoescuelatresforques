# Autoescuela Tres Forques — Web Oficial

Sitio web oficial de **Autoescuela Tres Forques** (*Wacker-Legaz, S.L.*, NIF `B40516833`), centro de formación vial con 5 sedes en Valencia y área metropolitana (Tres Forques, José María Mortes Lerma, Torrent, Tavernes Blanques y Rascaña).

## Estructura del Proyecto

- `index.html`: Landing page editorial en HTML5 semántico, CSS moderno y Vanilla JS, con popup modal de triaje inteligente paso a paso hacia WhatsApp (`+34 693 55 22 83`).
- `assets/`: Logotipo oficial, favicon, flota de vehículos, pistas homologadas de moto, equipo y galería de alumnos aprobados.
- `vercel.json`: Cabeceras de seguridad HTTP (`HSTS`, `X-Frame-Options`, `X-Content-Type-Options`, `Permissions-Policy`) y caché optimizada para `/assets/`.
- `robots.txt` y `sitemap.xml`: Configuración SEO para indexación en buscadores.
- `docs/`: Documentación estratégica y datos de referencia internos (excluidos de indexación en `robots.txt`).

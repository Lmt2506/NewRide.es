# Publicación de NewRide.es

Este repositorio público contiene **solo la web estática de NewRide** (HTML, CSS y JavaScript). El código Flutter y el backend de la app permanecen privados en otro repositorio.

## Activar GitHub Pages

1. Abre **Settings → Pages** de este repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige **main** y **/(root)**, y pulsa **Save**.
4. Espera a que GitHub indique que el sitio está publicado.

URL provisional tras activar Pages: `https://lmt2506.github.io/NewRide.es/` (si no tienes un dominio configurado y validado).

## Dominio personalizado

El archivo `CNAME` contiene `newride.es`. Para usar este dominio, primero debes ser propietario de él y configurar sus DNS en tu proveedor:

| Tipo | Nombre | Valor |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | lmt2506.github.io |

En **Settings → Pages**, introduce `newride.es` como dominio personalizado y, tras validar los DNS, activa **Enforce HTTPS**. Los cambios DNS pueden tardar en propagarse. Opcionalmente verifica el dominio desde GitHub antes de asignarlo.

## Antes de anunciar el lanzamiento

- Sustituye los datos entre corchetes en `privacidad.html`, `condiciones.html` y `soporte.html` por el titular y el correo real; los textos son borradores y requieren revisión legal.
- Revisa la descripción de la app, el enlace de Google Play y el estado de Premium.
- Las fotos de las tres tarjetas principales de la portada usan URLs externas de Unsplash como imágenes provisionales. Sustitúyelas por los WebP locales originales si quieres que el resultado gráfico sea idéntico a la web preparada previamente.
- La página web es informativa: no incorpora el cliente Flutter ni accede a bases de datos privadas.

## Procedencia de la web

Adaptación del diseño creado para NewRide. La rama privada `gh-pages` del repositorio original sirvió de fuente de los textos, HTML, estilos y scripts; este repositorio **no contiene** las claves ni el código privado de la aplicación.

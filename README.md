# Inventario y Contabilidad — Joyería

App para llevar el inventario de productos (joyas, pañuelos, cintos, etc.), materiales, packaging, compras/inversiones y ventas de un emprendimiento, con resumen financiero mensual y anual automático.

Los datos se guardan **en el propio dispositivo/navegador de quien la usa** (IndexedDB) — nadie más los ve. No requiere cuenta ni configuración de ningún tipo.

## Usar la app

👉 **[Abrir la app](https://TUUSUARIO.github.io/NOMBRE-DEL-REPO/)** — reemplazá el link una vez publicada (ver guía abajo).

Antes de usarla por primera vez, seguí el manual:

📄 [Manual de Usuario](./manual.html)

## Estructura del repositorio

- `index.html` — la app (autocontenida, sin dependencias externas de ningún tipo).
- `manual.html` — el manual, como página navegable (con link de vuelta a la app).
- `manual.md` — el mismo manual en Markdown, por si preferís editarlo como texto plano.

## Cómo publicarla en GitHub Pages (gratis)

1. Creá un repositorio nuevo en GitHub (podés ponerlo privado o público).
2. Subí estos tres archivos (`index.html`, `manual.html`, `manual.md`) a la raíz del repositorio — **importante:** el archivo de la app tiene que llamarse exactamente `index.html`, para que GitHub Pages lo sirva como página principal.
3. Andá a **Settings → Pages** dentro del repositorio.
4. En "Source", elegí la rama `main` (o `master`) y la carpeta `/ (root)`. Guardá.
5. GitHub te va a dar un link como `https://TUUSUARIO.github.io/NOMBRE-DEL-REPO/` — puede tardar uno o dos minutos en activarse la primera vez.
6. Ese link es el que usás para abrir la app desde cualquier navegador (celular o computadora). Reemplazalo en este README y compartilo con quien vaya a usar la app.

**Importante:** publicarla en GitHub Pages no mueve los datos de nadie — viven en el navegador de cada persona, no en el link. Cada quien sigue viendo lo que ya tenía cargado, siempre que entre desde el mismo dispositivo/navegador de siempre.

## Esta es una primera versión de prueba

Se armó a partir de lo que hoy registra el negocio en Excel, más lo conversado sobre cómo debería funcionar. Es normal que, al usarla en el día a día, aparezcan cosas para ajustar (campos que faltan, un orden que no cierra, un cálculo que hay que revisar) — la idea es que esta prueba sirva justamente para encontrarlas.

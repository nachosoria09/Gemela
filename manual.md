# Manual de Usuario — Inventario y Contabilidad para Joyería

Esta app te ayuda a llevar el inventario de tus productos, tus materiales, el packaging, tus compras/inversiones y tus ventas — y te arma un resumen financiero mensual y anual automáticamente.

Es una primera versión pensada para probar y ajustar. Si algo te resulta confuso, falta un campo, o el orden de las pantallas no te cierra, avisale a quien te armó la app — para eso es esta prueba.

## ¿Dónde se guardan mis datos?

**En este mismo dispositivo, adentro de este mismo navegador.** No hace falta crear ninguna cuenta, ni una planilla, ni nada de Google.

Esto tiene una consecuencia importante:

> ⚠️ Si cargás datos desde el celular y después abrís la app en la computadora, vas a ver dos cosas distintas — no son el mismo lugar. Cada dispositivo (y cada navegador dentro de ese dispositivo) guarda su propia copia.

Por eso te conviene elegir **un solo dispositivo principal** para cargar todo (por ejemplo, siempre desde el celular), y usar la copia de seguridad si necesitás pasar los datos a otro lado.

## Copia de seguridad (muy importante)

Desde el botón **⋮** (arriba a la derecha) → **Más opciones**:

- **⬇ Exportar copia de seguridad**: descarga un archivo con todo lo que cargaste. Guardalo en Google Drive, WhatsApp a vos misma, un pendrive, etc.
- **⬆ Restaurar copia**: si cambiás de dispositivo, o perdés los datos, elegís ese archivo y todo vuelve a aparecer como estaba. **Ojo:** restaurar reemplaza todo lo que tengas cargado en ese momento.

Recomendación: hacé una copia una vez por semana, o cada vez que cargues muchos datos de una sola vez.

## Inventario de productos

Acá van tus piezas para la venta: aros, collares, pulseras, pañuelos, cintos, bandoleras, esclavas, conjuntos, o cualquier categoría que definas.

- **+ Agregar producto**: para una pieza que nunca cargaste (código nuevo). Completás código, categoría, nombre, material, color, proveedor, costo, precio de venta, cantidad que ingresa, ubicación, recompra, calidad y observaciones.
- **+ Sumar stock**: para cuando comprás más unidades de una pieza que **ya existe** (mismo código) — por ejemplo, una recompra al mismo proveedor. Ahí solo cargás cuánto agregaste, y si el costo o el precio cambiaron.
- Si intentás dar de alta un código que ya existe, la app te va a avisar y te va a pedir que uses "+ Sumar stock" en su lugar.
- Cuando el stock disponible llega a 0, la pieza se muestra como **"Vendida / sin stock"**, pero sigue en tu inventario con su historial.
- Al cargar un producto nuevo, por defecto se genera también un registro automático en **Compras / Inversiones** (podés desmarcar esa opción si no querés que se genere).

### Categorías

Podés agregar o quitar categorías desde **⋮ → Más opciones → Categorías de productos**. Vienen algunas cargadas de referencia (Aros, Collares, Pulseras, etc.), pero son totalmente editables.

## Inventario de materiales

Acá van las cosas que comprás para el funcionamiento del emprendimiento, pero que **no se venden** (por ejemplo: un aro de luz, cartulinas de fondo para fotos). Se registra nombre, cantidad, costo total (el costo unitario se calcula solo) y proveedor.

## Packaging

El empaquetado que usás para entregar tus ventas (bolsas, cajas, etc.).

- Cargás el **costo total** de la compra y la **cantidad comprada** — el costo por unidad se calcula solo.
- Si comprás más del mismo packaging más adelante, usá **+ Sumar stock**: la app promedia el costo unitario entre lo que ya tenías y lo nuevo.
- Cuando armás una venta y usás packaging, el stock disponible se descuenta solo.

## Compras / Inversiones

Es el registro general de todo lo que gastaste en el emprendimiento: fecha, proveedor, concepto, monto, envío (agencia y costo), si ya lo recibiste, el costo total invertido, y el **origen de los fondos**.

- **Origen de los fondos**: en cada compra elegís si salió de tu **capital propio (inversión inicial, de tu bolsillo)** o de una **reinversión (con plata que ya generó el emprendimiento)**. Esto se pide en cada lugar donde se genera una compra (producto, material, packaging o compra manual), y después se ve desglosado en el Resumen financiero.

- La mayoría de estos registros **se generan solos** cuando cargás un producto, un material o un packaging nuevo (se marcan como "Automática").
- También podés agregar una compra manual para gastos que no son ni producto, ni material, ni packaging (por ejemplo, un gasto de envío suelto).
- **Importante:** si editás o borrás un registro automático desde acá, eso **no** cambia el producto/material/packaging relacionado — son registros independientes una vez creados. Si el error está en el producto, corregilo desde Inventario de productos.

## Ventas

### Generar venta

1. Cargás el nombre de la clienta (obligatorio), y si querés, cédula, teléfono y ciudad/dirección.
2. **+ Agregar producto**: elegís de la lista de productos con stock disponible, y la cantidad. Podés agregar varios productos a la misma venta.
3. **+ Agregar packaging**: igual que los productos, podés agregar uno o más tipos de packaging.
4. Elegís el medio de pago y si el pago ya fue recibido.
5. Elegís el canal de entrega: **Personal** (en mano) o **Envío** (te pide empresa de envío y número de seguimiento).
6. Vas viendo el costo total y el monto de venta calculados abajo, en tiempo real.
7. **Confirmar venta**: guarda la venta y descuenta el stock automáticamente. Si a un producto le quedaba 1 unidad, pasa a "vendida"; si tenía más, se descuenta la cantidad vendida.

### Historial de ventas

Lista todas las ventas hechas, con filtro por mes. Podés eliminar una venta — al hacerlo, el stock de los productos y el packaging usados **se repone automáticamente** (por si la cargaste por error).

*(Por ahora no se puede editar una venta ya guardada — si hay un error, eliminala y volvela a cargar; es seguro porque el stock se repone solo.)*

## Resumen financiero

- **Este mes**: total invertido, total vendido, invertido de tu capital propio, **reinvertido** (toda compra que hayas marcado como pagada con dinero del emprendimiento), packaging usado, ganancia neta, cantidad de pedidos y de productos vendidos, y productos en stock hoy — todo calculado automáticamente a partir de tus compras y ventas cargadas.
- **Ganancia embolsable**: se calcula sola, como un porcentaje de la ganancia neta del mes (por defecto 25%, editable si tu criterio cambia). Con los botones **"Sí, la retiré" / "No, quedó en el emprendimiento"** marcás si efectivamente sacaste esa plata o la dejaste en el negocio.
- **Notas del mes**: un espacio libre para observaciones.
- **Balance anual**: elegís el año y ves la suma de todos los meses — incluida la ganancia embolsable total, cuánta ya retiraste y cuánta todavía no.

## Si varias personas van a usar esta app

Como cada dispositivo guarda sus propios datos por separado, si más de una persona la usa (por ejemplo, la dueña y una empleada), **cada una debería usar su propio dispositivo**, y después juntar la información a mano o por copia de seguridad — esta versión no sincroniza datos en tiempo real entre dispositivos.

## Privacidad

Tus datos nunca salen de tu dispositivo. No se mandan a ningún servidor, a ninguna nube, ni a Anthropic (Claude) ni a nadie. La única forma en que "salen" es si vos misma exportás la copia de seguridad y la compartís con alguien.

## Cosas para revisar en esta primera prueba

Esta es una primera versión para que la pruebes y me digas qué le falta o qué te resulta raro. Algunas decisiones que se tomaron y que capaz hay que ajustar según cómo lo uses en la práctica:

- Los registros automáticos en Compras/Inversiones no se sincronizan si después editás el producto original.
- El packaging descuenta stock igual que los productos al usarse en una venta.
- Los materiales no descuentan stock al "usarse" — quedan solo como un registro de compra.
- No hay, por ahora, edición de una venta ya guardada (solo eliminar y volver a cargar).

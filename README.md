# LLEGA — App de repartidores

App completa en un solo archivo HTML, sin servidor ni backend. Pensada como app de teléfono, estilo Dasher / DoorDash, con estilo propio.

## Abrirla

Abre `index.html` en el navegador del teléfono o del ordenador. No necesita instalar nada.

Para publicarla en GitHub Pages: sube `index.html` a un repositorio y activa Pages (rama `main`, carpeta raíz). La app se sirve tal cual.

## Qué incluye

- **Inicio:** interruptor En línea / Fuera de línea, mapa simulado (Westheimer Rd, Montrose Blvd, Main St, Kirby Dr), zona caliente Midtown +$3 y ganancias de hoy.
- **Ofertas:** 8 pedidos reales de Houston (Torchy's Tacos, Uchi Houston, The Breakfast Klub, Velvet Taco, Pappasito's, Shake Shack Galleria, Chipotle Montrose, Pinkerton's Barbecue). Filtros todos / cerca / mejor pago, temporizador de 30 s, Aceptar / Rechazar. Solo 1 pedido activo a la vez.
- **Flujo en 4 pasos:** en camino al restaurante → recogida con código 4821 y checklist → en camino al cliente con llamar / mensaje / chat rápido → entrega con PIN o foto y resumen con ganancia.
- **Ganancias:** hoy y semana, desglose base / propinas / bonos, gráfico de 7 días, botón Retirar ahora, retos (+$12, +$8, +$5) y niveles Novato → Diamante con XP (+100 por entrega).
- **Turnos:** programar día, hora inicio/fin y zona; lista guardada.
- **Historial:** entregadas, canceladas y rechazadas, con filtro.
- **Perfil:** Darel Vega, Honda Civic 2019 gris, placa TX-4821-K, rating 4.9, 1,247 entregas. Nombre, vehículo, placa, zona y teléfono editables. Reseñas.
- **Notificaciones:** toasts arriba y centro de notificaciones con campana.

## Datos

Todo se guarda en `localStorage` bajo la clave `llega_v1`. Al entregar, suma el total a ganancias, +100 XP, verifica retos y nivel, y guarda el historial.

## Estilo

Fondo cálido `#FAF7F3`, tarjetas blancas, acento único coral `#E8402A`, tinta `#1C1917`. Tipografías Sora (títulos/cifras) e Inter (cuerpo). Sin degradados, sin morado/azul de IA, iconos SVG de trazo.

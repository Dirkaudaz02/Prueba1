# Metro Ahora — prueba de contingencia

Prototipo experimental para validar un flujo de evacuación:

1. Usuario escanea QR o abre el acceso directo.
2. La web pregunta a qué estación iba.
3. Pide GPS.
4. Busca un paradero RED cercano.
5. Cruza recorridos del GTFS con una consulta puntual de llegadas.
6. Muestra un máximo de 3 micros útiles.
7. Al elegir la micro genera una tarjeta sencilla para captura.
8. Google Maps se usa como respaldo para el punto de bajada y la ruta final.

## Prueba de incidente
La interfaz incluye un switch para simular un corte de L2 centro:
Patronato, Puente Cal y Canto y Santa Ana.

## Datos
- Red Metro y GTFS bus: metrovivo-santiago / datos construidos desde GTFS DTPM.
- Llegadas: consulta puntual por código de paradero mediante api.xor.cl.
- Google Maps: Maps URLs, sin API key.

## Importante
Es un prototipo, no un sistema operacional. No debe presentarse como información oficial de Metro o RED.

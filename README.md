# Costos Industriales

Prototipo inicial de la aplicación personal para calcular costos de productos por litro o kilogramo y costos de packaging.

## Qué incluye
- Alta y baja de productos a granel (L o kg).
- Alta y baja de materiales de packaging.
- Cálculo por presentación: contenido + materiales.
- Historial con copia de los costos utilizados.
- Exportación de datos en JSON e historial en CSV.

## Cómo probar
Abrir `index.html` en un navegador moderno.

## Limitaciones de esta primera versión
Los datos se guardan en `localStorage` del navegador. No se sincronizan entre computadoras ni tienen autenticación. Antes de usarlo como aplicación web privada multi-equipo, conectar una base de datos (por ejemplo Supabase), habilitar autenticación y reglas de acceso por usuario, y desplegar el sitio.

Los gastos indirectos quedan fuera de esta etapa.

# Costos Industriales

Aplicación personal para calcular costos de productos por litro o kilogramo y materiales de packaging.

## Funciones del prototipo
- Alta, edición y eliminación de productos a granel y materiales de packaging.
- Costos unitarios ingresados en dólares (USD), con fecha del costo.
- Aviso en rojo cuando un costo tiene más de 30 días o no tiene fecha.
- Pestaña para ingresar la cotización ARS por USD y su fecha.
- Calculadora por presentación que muestra costos en USD y equivalencia en ARS.
- Historial que conserva los precios, fechas y tipo de cambio utilizados al calcular.
- Exportación de datos en JSON e historial en CSV.

## Cómo probar
Abrir `index.html` en un navegador moderno.

## Limitaciones
Los datos se guardan en `localStorage` del navegador. No se sincronizan entre computadoras ni tienen autenticación. Para usarlo como aplicación web privada desde varios equipos, conectar una base de datos, habilitar autenticación y reglas de acceso por usuario, y desplegar el sitio.

Los gastos indirectos quedan fuera de esta etapa. Los registros anteriores sin fecha aparecerán como vencidos; conviene revisar y corregir su costo y fecha.

# Gestión del Gimnasio

Aplicación web de un solo archivo (`index.html`) para llevar los clientes del gimnasio.
No necesita instalación ni internet: abre `index.html` en cualquier navegador (PC, tablet o móvil).

## Funciones
- **Clientes**: alta, edición, búsqueda y filtro por estado (activo / por vencer / vencido).
- **Membresías**: planes configurables (días y precio). Al renovar, si la membresía sigue activa se suma desde el vencimiento actual.
- **Pagos**: registro con método de pago, historial por cliente, resumen e ingresos por mes, exportación a CSV.
- **Asistencia**: registro de entradas del día, con aviso si la membresía está vencida.
- **Panel**: totales, ingresos del mes y listas de quién vence pronto o ya venció.
- **Recordatorios por WhatsApp** con mensaje listo para enviar.
- **Copias de seguridad**: descarga y restauración en JSON.

## Importante
Los datos se guardan en el navegador donde se usa (localStorage). Si se borran los datos del
navegador o se cambia de dispositivo, se pierden: descarga una copia desde "Planes y datos" con regularidad.

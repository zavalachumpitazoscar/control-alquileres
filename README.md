# Mis Alquileres

Sistema sencillo para administrar locales alquilados, clientes y pagos mensuales. Está diseñado con letras legibles, botones claros y pocos pasos.

## Primera versión

- Resumen de clientes pendientes, pagados y total cobrado.
- Filtros rápidos y búsqueda por nombre, DNI, teléfono o local.
- Registro y edición de clientes.
- Registro de pagos y referencia del comprobante.
- Historial de pagos por cliente.
- Diseño adaptable a computadora y celular.
- Datos de demostración almacenados en el navegador mientras se configura Firebase.

## Probar

Abra `index.html` o active GitHub Pages desde **Settings → Pages → Deploy from a branch → main / root**.

## Conectar Firebase

El repositorio incluye `firebase.json`, reglas iniciales de Firestore y Storage, y un ejemplo de configuración. La siguiente etapa sustituirá el almacenamiento local por Firebase Authentication, Firestore y Storage.

> Importante: las reglas incluidas son una base inicial. Antes de producción se agregarán roles y separación de datos por propietario.

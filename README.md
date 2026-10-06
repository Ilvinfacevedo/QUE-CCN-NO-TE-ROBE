# Que CCN no te robe

Calculadora de horas extras, contadas al minuto, con cortes los días 8 y 23.
Creada por Ilvinf Acevedo.

## Cómo usarla

Abre `index.html` en el navegador (o publícala con GitHub Pages). Anota la fecha,
las horas y minutos extra y el tipo; la app suma el tiempo, el bruto y el neto
aproximado de cada corte. Los datos se guardan en el navegador del dispositivo.

## Cómo se calcula

- Salario diario = salario mensual ÷ 23.83
- Hora normal = salario diario ÷ 8
- Hora extra normal = hora normal × 1.35
- Más de 68 h en la semana, feriado o día libre = hora normal × 2
- Neto aprox. = bruto − AFP (2.87 %) − SFS (3.04 %). No incluye ISR.

## Cortes y pagos

| Corte      | Se paga |
|------------|---------|
| 9 al 23    | día 30 (o el último día del mes) |
| 24 al 8    | día 15 |

Es un estimado: la empresa puede redondear distinto.

## Instalarla en el celular

La app es instalable (PWA): tiene ícono propio, abre en pantalla completa y
funciona sin internet después de la primera visita.

1. Abre https://ilvinfacevedo.github.io/QUE-CCN-NO-TE-ROBE/ en el celular, o escanea el QR:

   <img src="qr.png" alt="QR de la app" width="240">

2. **iPhone (Safari):** botón Compartir → *Agregar a pantalla de inicio*.
   **Android (Chrome):** menú ⋮ → *Instalar app* (o *Agregar a la pantalla principal*).

Los registros se guardan en ese celular. Si borras los datos del navegador o
desinstalas la app, se pierden.

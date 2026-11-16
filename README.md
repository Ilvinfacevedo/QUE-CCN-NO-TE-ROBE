# Que CCN no te robe

Calculadora de horas extras, contadas al minuto, con cortes los días 8 y 23.
Creada por Ilvinf Acevedo.

## Cómo usarla

Abre `index.html` en el navegador (o publícala con GitHub Pages). Anota la fecha,
las horas y minutos extra y el tipo; la app suma el tiempo, el bruto y el neto
aproximado de cada corte. Los datos se guardan en el navegador del dispositivo.

También puedes:

- **Comparar con tu recibo:** anota cada línea "Horas Extras" del recibo (horas y
  monto) y la app te dice si cuadra o cuánto te falta.
- **Calcular por hora de salida:** pones a qué hora saliste y la app resta tu hora
  normal de salida.
- **Editar** registros, ver el **resumen del año** y **descargar/cargar un respaldo**.

## Cómo se calcula

Se redondea igual que el recibo de CCN:

- Salario diario = salario mensual ÷ 23.83, a 2 decimales (30,000 → 1,258.92)
- Hora normal = salario diario ÷ 8, a 2 decimales (→ 157.37)
- Hora extra normal = hora normal × 1.35 (→ 212.45)
- Lo que pase de 68 h en la semana (lunes a domingo) pasa solo a × 2; feriado o día libre = × 2
- Cada registro guarda la tarifa del día en que se anotó: un aumento de salario no cambia lo ya ganado.
- El recibo muestra horas en decimal (7.74 h = 7 h 44 min).
- Neto: por defecto sin descuentos, porque en el recibo los descuentos de AFP y SFS
  no se aplicaron a las horas extras. En ajustes se pueden restar AFP (2.87 %) y SFS (3.04 %). No incluye ISR.

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
desinstalas la app, se pierden: usa **Respaldo de tus datos → Descargar respaldo**
de vez en cuando.

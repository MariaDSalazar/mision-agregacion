# Misión Agregación

Simulación laboral de SQL: una semana como analista de datos junior en Banco Quindé, un banco ficticio, usando funciones de agregación y agrupación.

## La semana

Cada día el jugador apoya a un área del banco y la dificultad sube:

| Día | Área | Tema | Datos |
|---|---|---|---|
| Lunes | Operaciones | COUNT | Transferencias del core bancario |
| Martes | Tesorería | SUM y AVG | Depósitos en ventanilla |
| Miércoles | Canales Digitales | MIN y MAX | Retiros en cajeros automáticos |
| Jueves | Gerencia Comercial | GROUP BY | Pagos de servicios por agencia |
| Viernes | Riesgo Operativo | HAVING | Pagos con tarjeta en comercios |
| Fin de mes | Comité de Gerencia | Todo junto | Transacciones por canal |

Los compañeros de trabajo envían sus pedidos por mensaje, y los datos traen las inconsistencias típicas de producción.

En cada pedido se ve la tabla completa. Si la respuesta no cuadra, se explica por qué esa elección no sirve, sin mostrar la correcta, y se vuelve a intentar. Al acertar se muestran la respuesta del compañero, la consulta SQL, una animación de cómo la resuelve SQL fase por fase (FROM, WHERE, GROUP BY, HAVING, SELECT) y el resultado real. Todas las consultas se ejecutaron en SQL Server para obtener esos resultados.

Todo el contenido va cifrado y en cadena: cada pedido se abre solo después de resolver bien el anterior.

Al terminar la semana, el jugador descarga un certificado con su nombre, sus aciertos al primer intento y el cargo alcanzado. Solo se pide nombre y apellido; el progreso se guarda en el propio dispositivo.

El banco, las personas, los clientes y los comercios son ficticios.

## Ejecutar en local

Es un sitio estático. Desde la carpeta del repositorio:

```
python -m http.server 8000
```

y abrir `http://localhost:8000`.

# Casos de prueba

| N.º | Caso | Entrada | Resultado esperado | Resultado obtenido | Evidencia |
|---|---|---|---|---|---|
| 1 | settickets válido | settickets(10) | Retorna 0 | [completar] | [captura] |
| 2 | settickets inválido | settickets(0), settickets(-5) | Retorna -1 | [completar] | [captura] |
| 3 | Dos procesos 1:3 | lotterytest 10 30 | ~25% y ~75% | [completar] | pruebas/capturas/02_prueba_1_3.png |
| 4 | Tres procesos 3:2:1 | lotterytest 30 20 10 | ~50%, ~33%, ~17% | [completar] | [captura] |
| 5 | Herencia en fork | hijo de proceso con 20 boletos | Hijo con 20 boletos | [completar] | [captura] |
| 6 | Sin inanición | lotterytest 1 100 | Proceso de 1 boleto con ticks > 0 | [completar] | [captura] |
| 7 | Boletos iguales | lotterytest 10 10 10 | ~33% cada uno | [completar] | [captura] |

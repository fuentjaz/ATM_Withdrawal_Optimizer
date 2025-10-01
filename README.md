# ATM Withdrawal Optimizer 
## Descripción del Problema
En muchos cajeros automáticos, cuando un cliente solicita un monto de dinero, el sistema debe calcular cuántos billetes entregar y de qué denominaciones, buscando optimizar el número de billetes.

Este programa implementa una solución en Java que, dado un monto n, determina cuántos billetes son necesarios para completar la transacción.
Si el monto no es múltiplo de 10 (lo cual suele ser una restricción real en cajeros), se devuelve -1 como error.

### Características
- Simula la lógica de un cajero automático real.
- Optimiza la entrega de dinero con la menor cantidad de billetes posibles.
- Maneja casos de error si el monto no es múltiplo de 10.

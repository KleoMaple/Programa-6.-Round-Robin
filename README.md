# Programa-6.-Round-Robin
## Requerimientos

1. **Cumplimiento de Especificaciones del Programa 4:**
   - Excepción: Se utilizará el algoritmo de planificación Round-Robin.

2. **Preguntas Iniciales:**
   a. Número de Procesos Inicial (n procesos).
   b. Valor del Quantum.

3. **Algoritmo RR con Ráfagas de Tiempo:**
   - El Quantum determina la ráfaga de tiempo.
   - Cuando el Quantum ha transcurrido, el proceso sale del procesador y se coloca al final de la cola de listos.

4. **Teclas para Utilizar:**

   | Tecla | ¿Qué Indica?                             | ¿Qué Hace?                                                  |
   |-------|------------------------------------------|------------------------------------------------------------|
   | I     | Interrupción por Entrada/Salida           | Proceso en ejecución sale del procesador y va a la cola de Bloqueados. Vuelve a la cola de listos después de un tiempo de 8. |
   | E     | Error                                    | Proceso en ejecución termina por error, se muestra en procesos terminados. Se libera espacio en memoria. |
   | P     | Pausa                                    | Detiene la ejecución momentáneamente, se reanuda con la tecla "C". |
   | C     | Continuar                                | Reanuda el programa pausado previamente con "P".            |
   | N     | Nuevo                                    | Genera un nuevo proceso con datos aleatorios. Planificador a largo plazo define su ingreso al sistema. |
   | B     | Tabla de Procesos (BCP de cada proceso) | Pausa el programa y muestra la tabla de procesos (BCP). Tecla "C" continúa la simulación en el punto donde quedó. |

5. **Visualización en Pantalla:**
   a. Número de Procesos en Estado Nuevo.
   b. Valor del Quantum.
   c. Cola de Listos:
      - Identificador de Proceso.
      - Tiempo Máximo Estimado.
      - Tiempo Transcurrido.
      - Avance del carrusel.
   d. Proceso en Ejecución:
      - Todos los datos del proceso.
      - Tiempo transcurrido en ejecución.
      - Tiempo restante por ejecutar.
      - Tiempo transcurrido del quantum.
   e. Cola de Bloqueados:
      - Identificador de Proceso.
      - Tiempo transcurrido en bloqueado.
   f. Procesos Terminados:
      - Identificador de Proceso.
      - Operación.
      - Resultado de la operación o "ERROR" en caso de terminación con error.
   g. Reloj (Contador General): Tiempo total transcurrido desde el inicio de la simulación.

6. **Fin del Programa:**
   - Se presiona la tecla "ESC".

7. **Datos al Finalizar:**
   - Todos los datos de cada proceso, incluyendo la tabla de procesos.

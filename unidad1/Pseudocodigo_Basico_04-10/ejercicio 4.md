## Control de encendido por paridad de pulso
Investigación / Supuesto técnico: Para determinar la paridad de un número entero se utilizó el operador módulo o residuo (% o MOD), considerando que un número es par si su residuo al dividirse entre 2 es igual a 0.

Pseudocódigo:

Inicio

    Escribir "Ingrese el número total de pulsos/activaciones del botón:"
    Leer totalPulsos
    
    Si (totalPulsos MOD 2) == 0 Entonces
        Escribir "El total de pulsos es PAR."
    Sino
        Escribir "El total de pulsos es IMPAR."
    FinSi
Fin
[archivodfd](./ejercicio%204.dfd)
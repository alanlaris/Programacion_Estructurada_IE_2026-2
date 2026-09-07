## 10. Inversor de señal digital (Compuerta NOT
)Investigación / Supuesto técnico: Se utilizó la tabla de verdad de la función lógica NOT, la cual invierte cualquier estado binario válido ($1 \rightarrow 0$ y $0 \rightarrow 1$).

Pseudocódigo:

Inicio

    Escribir "Ingrese la señal digital de entrada (0 o 1):"
    Leer senalEntrada
    
    Si senalEntrada == 1 Entonces
        senalInvertida <- 0
        Escribir "Señal original:", senalEntrada, "-> Señal invertida:", senalInvertida
    SinoSi senalEntrada == 0 Entonces
        senalInvertida <- 1
        Escribir "Señal original:", senalEntrada, "-> Señal invertida:", senalInvertida
    Sino
        Escribir "Error: La señal de entrada debe ser un valor binario válido (0 o 1)."
    FinSi
Fin

[archivodfd](./ejercicio%2010.dfd)
## 8. Conversión de tiempo de ejecución
Investigación / Supuesto técnico: Se aplicó la división entera para calcular los minutos ($minutos = segundos \div 60$) y el operador residuo (MOD) para obtener los segundos sobrantes ($segundosRestantes = segundos \pmod{60}$).

Pseudocódigo

Inicio

    Escribir "Ingrese la cantidad total de segundos:"
    Leer segundosTotales
    
    minutos <- segundosTotales DIV 60
    segundosRestantes <- segundosTotales MOD 60
    
    Escribir segundosTotales, "segundos equivalen a:", minutos, "minutos y", segundosRestantes, "segundos."
Fin
## 2. Monitoreo de sobrecalentamiento de un motor

Investigación / Supuesto técnico: Se investigó un umbral estándar de operación para motores industriales, fijando el límite de sobrecalentamiento crítico en 85 °C (a partir del cual se activa el apagado por seguridad).

Pseudocódigo:

Inicio

    UMBRAL_LIME <- 85.0
    Escribir "Ingrese la temperatura actual del motor en °C:"
    Leer temperaturaActual
    
    Si temperaturaActual >= UMBRAL_LIME Entonces
        Escribir "¡ALERTA! Sobrecalentamiento detectado. Estado: APAGAR MOTOR."
    Sino
        Escribir "Temperatura dentro del rango normal. Estado: MOTOR OPERATIVO."
    FinSi
Fin

[Archivodfd](./Ejercicio%202.dfd)
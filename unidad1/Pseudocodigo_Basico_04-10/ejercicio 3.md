## 3. Validación de nivel lógico TTL

Investigación / Supuesto técnico: Según la especificación técnica de la tecnología TTL (Transistor-Transistor Logic), un estado lógico ALTO (HIGH) válido se encuentra en el rango de 2.0 V a 5.0 V.

Pseudocódigo:
Inicio

    Escribir "Ingrese el voltaje de entrada (V):"
    Leer voltajeEntrada
    
    Si voltajeEntrada >= 2.0 Y voltajeEntrada <= 5.0 Entonces
        Escribir "El voltaje ingresado corresponde a un estado lógico ALTO (HIGH) válido."
    Sino
        Escribir "El voltaje ingresado NO es un estado lógico ALTO válido según el estándar TTL."
    FinSi
Fin


[Archivo dfd](./Ejercicio%203.dfd)
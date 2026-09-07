## 7. Sistema automatizado de iluminación exterior
Investigación / Supuesto técnico: Se utilizó una evaluación condicional con la compuerta lógica AND (Y). Para encender la lámpara, ambas condiciones deben ser verdaderas simultáneamente: nivelLuzBajo == Verdadero Y movimientoDetectado == Verdadero.

Pseudocódigo:


Inicio

    Escribir "¿El nivel de luz ambiental es bajo? (1: Sí / 0: No):"
    Leer entradaLuz
    Escribir "¿El sensor de presencia detectó movimiento? (1: Sí / 0: No):"
    Leer entradaMovimiento
    
    luzBaja <- (entradaLuz == 1)
    presenciaDetectada <- (entradaMovimiento == 1)
    
    Si luzBaja Y presenciaDetectada Entonces
        Escribir "Estado de la lámpara: ENCENDIDA"
    Sino
        Escribir "Estado de la lámpara: APAGADA"
    FinSi
Fin

[ejerciciodfd](./ejercicio%207.dfd)
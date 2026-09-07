## 5. Sistema de alarma con múltiples sensores
Investigación / Supuesto técnico: Se implementó una tabla de verdad con lógica Booleana mediante el operador relacional/lógico OR (O), donde la alerta se activa si el Sensor 1 O el Sensor 2 son verdaderos (abiertos).

Pseudocódigo:


Inicio

    Escribir "¿El sensor de la ventana 1 está activado/abierto? (1: Sí / 0: No):"
    Leer sensorVentana1
    Escribir "¿El sensor de la ventana 2 está activado/abierto? (1: Sí / 0: No):"
    Leer sensorVentana2
    
    // Se interpretan 1 como Verdadero y 0 como Falso
    sensor1Activado <- (sensorVentana1 == 1)
    sensor2Activado <- (sensorVentana2 == 1)
    
    Si sensor1Activado O sensor2Activado Entonces
        Escribir "¡ALERTA DE SEGURIDAD! Se ha detectado apertura en al menos una ventana."
    Sino
        Escribir "Sistema seguro. No se detectan aperturas."
    FinSi
Fin

[Archivo dfd](./Ejercicio%205.dfd)
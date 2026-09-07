## 9. Descuento por volumen en componentes
Investigación / Supuesto técnico: Se fijó un supuesto de venta al mayoreo donde la "cantidad considerable" equivale a 100 unidades o más, aplicando un 15% de descuento sobre el total.

Pseudocódigo:


Inicio

    PRECIO_UNITARIO <- 2.50  // Precio regular por resistencia
    Escribir "Ingrese la cantidad de resistencias a comprar:"
    Leer cantidadComprada
    
    subtotal <- cantidadComprada * PRECIO_UNITARIO
    
    Si cantidadComprada >= 100 Entonces
        descuento <- subtotal * 0.15
        totalPagar <- subtotal - descuento
        Escribir "Se aplicó un descuento del 15% por volumen ($", descuento, ")."
    Sino
        totalPagar <- subtotal
        Escribir "No aplica descuento por volumen."
    FinSi
    
    Escribir "El total a pagar es: $", totalPagar
Fin
[archivodfd](./Ejercicio%201.dfd)
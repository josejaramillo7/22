1. El usuario ingresa una medida en metros, y debe imprimir el equivalente en pulgadas

# Solucion:

## Variables de entrada:
*numerica:* metros;

## Variables de salida:
*numerica:* pulgadas;

## Proceso
pulgadas = metros(39.3701)
*imprimir*(pulgadas);

2. El usuario ingresa su edad y debe devolverle si es menor de edad o mayor de edad.

# Solucion:

## Variables de entrada:
*booleana:* resultado;

## Proceso:
si (num >= 18){
    resultado = verdadero;
} si no {
    resultado = falso;
}
*imprimir:* (resultado);



3. Dado un número decir si es positivo o negativo.
# solucion:
# Variables de entrada
*numerica:* numero;

# Variables de salida
*numerica:* es_positivo;

# Proceso
si numero >= 0 entonces
    es_positivo = 1
    imprimir "El número es positivo"
sino
    es_positivo = 0
    imprimir "El número es negativo"

4. Devolver el número mayor de dos números ingresados.

# solucion:

# Variables de entrada
*numerica:* numero1;
*numerica:* numero2;

# Variables de salida
*numerica:* mayor;

# Proceso
si numero1 > numero2 entonces
    mayor = numero1
sino
    mayor = numero2

imprimir "El número mayor es:", mayor;
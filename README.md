Este repositorio recoge la forma de sumar todos los valores de un campo para cada página de un formulario

Para que el código funcione, tener en cuenta los siguientes aspectos:
- El código debe ir siempre en la ventanta *Initialize*
- Tener cuidado con los nombres de los campos, si hay dos con el mismo nombre, aunque estén diferentes subformularios, los sumará ambos
- Todos los campos que se quieren sumar son tipo string, en el código está puesta la forma de pasarlo a numérico para que no de error
- CUIDADO CON LAS MAYÚSCULAS
- Si la suma resultante es un número entero, no mostrará los decimales
- En el ejemplo, se ha sumado el valor de los siguientes campos: Importe, Valor, Flete, Seguro y Otros

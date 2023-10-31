# Desafio14 - Bootcamp - Calculadora

## Imagen "Calculadora"

La aplicación es una calculadora creada en HTML. Es una calculadora simple, le ingresamos dos valores, elegimos la operación que deseamos (suma, resta, multiplicar y dividir), hacemos clic en el botón “calcular” y nos devolverá el resultado de la cuenta. En la siguiente imagen se observará un ejemplo, donde sumaremos los valores 25 y 50.

![Calculadora](https://github.com/PabloMinio/desafio14/assets/81270459/853c4ecd-f1b4-4fdf-bbd4-8ced39dc8fe1)

## Instalar imagen

Para instalar la imagen ejecutamos los siguentes comandos:

  •	*docker build -t calculadora .*: Creamos la imagen con el nombre "calculadora"
  •	*docker run -dp 8080:80 calculadora*: Ejecutamos la imagen en segundo plano (“d”) y en los puertos 8080:80 (“p”).
  •	*docker ps*: Verificamos si la imagen está ejecutándose.

 ## Funcionamiento de la imagen

 Para usar la aplicación, escribimos en nuestro navegador "localhost:8080".

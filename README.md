# Sensor Barométrico BMP180
## *¿Qué es el BMP180?*
El sensor BMP180 es un sensor diseñado para leer la presión atmosférica y de esta forma estimar indirectamente la Altura sobre el nivel del mar. Lo que mide el sensor BMP180 es la presión absoluta (Barométrica) y la temperatura; al sensar la temperatura podemos compensar su influencia en la presión y asi determinar con mayor exactitud la altitud.

> ![Sensor BMP180](https://geekbotelectronics.com/wp-content/uploads/2021/06/BMP180-1.jpg)

## *Presión atmosférica*
La presión atmosférica es la fuerza que ejerce el aire (atmósfera) sobre la superficie de la tierra. La presión atmosférica se debe al peso de la columna de aire sobre determinada área, es por esta razón que al medir la presión atmosférica en puntos con mayor altitud, el valor de la presión es menor por ser menor la cantidad de aire. La presión atmosférica también varía con el clima, principalmente con la temperatura, pues esta hace cambiar la densidad del aire, que se ve reflejado en un cambio en el peso y por consiguiente en un cambio de presión.

> ![Ilustración de la compensación de presión atmosférica](https://sailandtrip.com/wp-content/uploads/2016/01/Presion-atmosferica-everest-LOW.jpg)

## *Descripción del BMP180*
El BMP180 es el  reemplazo de BMP085, posee alta precisión y de bajo consumo de energía. Ofrece un rango de medición desde 300 a 1100 hPa, con una precisión absoluta de hasta 0,03 hPa. Diseñado para ser conectado directamente a un microcontrolador a través de I2C utilizando solo 2 lineas.

## *Utilización*
Este tipo de sensores pueden ser utilizados para calcular la altitud con gran precisión, por lo que es un sensor muy utilizado en sistemas de Autopiloto para Drones (UAVs). 

>![Dron UAV](https://www.identifiedtech.com/wp-content/uploads/2016/04/blog_drone-vs-uav2.jpg)

En proyectos biológicos tiende a ser de gran utilidad debido a la medición de la presión dentro de sistemas controlados. Sin embargo, hay mejores alternativas para este tipo de tareas.

>![Ejemplo de utilización de BMP180](https://i.pinimg.com/originals/80/b0/68/80b0681d244dadb6a16ea1e816eb57bf.jpg)

Otras utilizaciones del BMP180 es en el prónostico del tiempo, la monitorización de la calidad del aire, sistemas de navegación GPS, sistemas de control de clima en edificios, entre otros proyectos de tecnología.

## *Ventajas y desventajas*
  *Ventajas*
  + Precisión: El BMP180 es conocido por su precisión en la medición de la presión atmosférica y la temperatura, lo que lo hace adecuado para aplicaciones que requieren datos precisos.
  + Bajo consumo de energía: El sensor BMP180 consume muy poca energía, lo que es beneficioso para aplicaciones con restricciones de energía, como dispositivos alimentados por batería.
  + Compatibilidad: El BMP180 se comunica fácilmente con microcontroladores y otros dispositivos a través de interfaces estándar como I2C y SPI, lo que facilita su integración en proyectos electrónicos.
  + Amplia gama de aplicaciones: Puede utilizarse en una amplia variedad de aplicaciones, desde pronóstico del tiempo hasta control de drones y automatización industrial.
  + Costo asequible: Es relativamente económico en comparación con sensores más avanzados, lo que lo hace accesible para proyectos con presupuestos limitados.

  *Desventajas*
  + Altitud limitada: El BMP180 es más adecuado para aplicaciones a altitudes moderadas. No es la mejor opción para mediciones precisas en altitudes extremadamente altas o por debajo del nivel del mar.
  + No apto para aplicaciones submarinas: Debido a sus limitaciones de presión, el BMP180 no es adecuado para aplicaciones submarinas en las que se requieran mediciones de presión a grandes profundidades. 
  + Calibración requerida: Para obtener mediciones precisas, el sensor BMP180 debe calibrarse correctamente, lo que puede requerir equipo y procedimientos específicos.
  + Disponibilidad limitada: Dado que el BMP180 es un modelo más antiguo de sensor de presión de Bosch Sensortec, su disponibilidad puede ser limitada en comparación con sensores más nuevos y avanzados.
  + Resistencia ambiental limitada: El BMP180 no está diseñado para soportar condiciones ambientales extremas, como temperaturas muy altas o bajas, o alta humedad. En entornos adversos, es posible que sea necesario proteger el sensor adecuadamente.

## *Especificaciones técnicas*
+ Voltaje de Operación: 3.3V - 5V DC
+ Interfaz de comunicación: I2C (3.3V)
+ Rango de Presión: 300 a 1100 hPa (0.3-1.1bar)
+ Resolución: 1 Pa
+ Precisión absoluta: 1 hPa
+ Medición de temperatura incluida
+ Resolución de temperatura: 0.1°C
+ Precisión Temperatura: 1°C
+ Frecuencia de Muestreo: 120 Hz (máx.)
+ Rango de altura medible: 0-9100 metros
+ Ultra-bajo consumo de energía
+ Completamente calibrado

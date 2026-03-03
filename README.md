# AIR_MONITOR
Se busca crear un dispositivo que monitoree la calidad del aire en cuanto a temperatura, pH y CO2. éste dispositivo compacto con pantalla oled, dénde me muestre los datos y también se envíen a un dispositivo móvil mediante software. 

**REQUERIMIENTOS**
1. Componentes principales
  - Esp32 wroom 32
  - Sensor BME280
  - Sensor MQ-135
  - OLED 0.96" (I2C)
  - Bateria LiPo 500mAh
2. Se requiere que el diseño del dispositivo sea compacto y ligero al ser portátil, además, que en su diseño sea cilindrico para la mejor circulación del aire y con rejillas para que los sensores actuen mejor.
3. Se requiere de un puerto USB-C para programación y carga del mismo dispositivo.
4. En cuanto al diseño en el PCB se debe tener en cuenta la disposicion del sensore de temperatura para que no afecte las lecturas cuando se eleve la temperatura interna de los componentes del msimo. ej el procesador o reistencias, etc.
5. REgulador de tensión AMS1117-3.3. 


**RESTRICCIONES**
1. Físicas: Debe pesar al rededor de 300 a 400 gramos. Radio de 3cm, altura de 10cm.
2.  Ambientales: Debe resistir un gran rango de temperaturas y soportar vibraciones y resitir al agua.
3.  Logísticas y de mercado: No existe como tal la restricción pues la mayoria de componentes son económicos y faciles de conseguir en Bogotá. La restricción es en cuanto a la disponibilidad de las maquinas que impriman PCB´s e impresoras 3D.
4.  Seguridad y usuario: Se debe tener en espacios aislados de manipulaciones para mejor funcionamiento. 








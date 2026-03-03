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
5. 

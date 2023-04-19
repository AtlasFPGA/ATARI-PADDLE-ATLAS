# ATARI-PADDLE-ATLAS
   Adaptador para poder usar joysticks resistivos en las FPGAs que no han previsto usar el esquema original de ATARI.

   En los sistemas de 8bit se usa el 558 para convertir con 4 monestables una lectura de resistencia en señales digitales, el problema surje con las fpgas que no están preparadas para admitir tensiones de más de +3V3, así que la primera tarea es encontar un multibibrador monoestable que pueda ser alimentado a +3V3. 
   
   Hay que escoger un chip que tenga existencias en el almacén, y hay que recalcular todas las fórmulas y luego pensar de forma inversa y hacer que coincida la formula con el nuevo monoestable alimentado a +3V3.
   
   La formula viene en la página 206 del libro de especificaciones del PC-XT de 1983.
   
#   Tiempo = 24,2_microsegundos + 0,011(Dependiente de la resistencia)_microsengundos

Nota se sube la versión fecha 19-04-2023.

---

   Esquema básico de un joystick analógico:

![Esquema básico de un joystick analógico](https://github.com/AtlasFPGA/ATARI-PADDLE-ATLAS/blob/main/FOTOS/INFORMACI%C3%93N_JOY_ANAL%C3%93GICO_IBM.png)

---

   Formula temporal asociada a la descarga de un multibribrador monoestable en la creación de un mando de juegos.

![Formula temporal asociada a la descarga de un multibribrador monoestable en la creación de un mando de juegos](https://github.com/AtlasFPGA/ATARI-PADDLE-ATLAS/blob/main/FOTOS/INFORMACI%C3%93N_JOY_ANAL%C3%93GICO_IBM_FORMULA_TEMPORAL.png)

---

   Visión huellas 3D.

![Visión huellas 3D](https://github.com/AtlasFPGA/ATARI-PADDLE-ATLAS/blob/main/FOTOS/COMUNICACI%C3%93N_ATARI_PADDLE_ATLAS.jpg)

---

   VISION DERECHA.

![VISION DERECHA](https://github.com/AtlasFPGA/ATARI-PADDLE-ATLAS/blob/main/FOTOS/COMUNICACI%C3%93N_ATARI_PADDLE_ATLAS_DERECHA.jpg)

---

   VISION FRONTAL INCLINADA.
   
![VISION FRONTAL INCLINADA](https://github.com/AtlasFPGA/ATARI-PADDLE-ATLAS/blob/main/FOTOS/COMUNICACI%C3%93N_ATARI_PADDLE_ATLAS_FRONTAL_INCLINADA.jpg)

---

   Plateamiento de huellas PCB.

![Plateamiento de huellas PCB](https://github.com/AtlasFPGA/ATARI-PADDLE-ATLAS/blob/main/FOTOS/INICIO_PCB_ATARI-PADDLE-ATLAS.png)

---



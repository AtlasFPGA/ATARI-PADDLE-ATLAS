# ATARI-PADDLE-ATLAS
   Adaptador para poder usar joysticks resistivos en las FPGAs que no han previsto usar el esquema original de ATARI.

   En los sistemas de 8bit se usa el 558 para convertir con 4 monestables una lectura de resistencia en señales digitales, el problema surje con las fpgas que no están preparadas para admitir tensiones de más de +3V3, así que la primera tarea es encontar un multibibrador monoestable que pueda ser alimentado a +3V3. 
   
   

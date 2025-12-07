## Memoria y Rendimiento de disco

**Comandos 1:**  
`free | free -h | free -s 3`

**Explicación rápida:**  
Nos enseñan el estado de la memoria RAM y la swap, el comando del tirón lo da en KB, el -h lo que hace es traducir las cifras a unidades legibles cómo MB y GB y -s 3 nos actualiza los datos en pantalla cada 3 segundos.

**Captura:**  
![PS1](img/free.png)

**Comandos 2:**  
`df -h | df -hT | df -h /`

**Explicación rápida:**  
Nos dan información sobre el espacio disponible en las particiones que están montadas, -h usará unidades legibles, -hT nos añade una columna con el tipo de sistema de archivos (ntfs, ext4..) y -h / nos dará un filtro para mostrar únicamente la info de la partición raíz.

**Captura:**  
![PS1](img/df.png)

**Comandos 3:**  
`du -hs /home | du -hs /home/*`

**Explicación rápida:**  
Nos enseñan el almacenamiento de forma distina, du nos calcula el peso real de los contenidos de las carpetas, df nos enseñará la capacidad y el espacio libre de la partición del disco donde estarán esos archivos

**Captura:**  
![PS1](img/du.png)

**Comando 4:**  
`iostat -x nombre_del_disco 5`

**Explicación rápida:**  
Este comando monitorizará el rendimiento de entrada y salida del disco que indiquemos con estadísitcas extendidas (el -x), refrescando la información cada 5 segundos.

**Captura:**  
![PS1](img/iostat.png)

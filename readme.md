Instálalo usando dpkg -i y verifica que funcione correctamente.


![Captura desde 2024-08-25 13-09-12](https://github.com/user-attachments/assets/0549ba6d-80c8-459c-926d-5a6b12550bc1)

![Captura desde 2024-08-25 13-17-01](https://github.com/user-attachments/assets/350fc9dc-ffee-4438-bd70-1585818c5c35)



 Construir el Paquete .deb
Ahora puedes construir el paquete .deb usando dpkg-deb:

dpkg-deb --build uptime-display


Este comando generará un archivo uptime-display.deb que puedes instalar en cualquier sistema compatible con Debian/Ubuntu.

Instala el paquete en un sistema de prueba para verificar que todo funciona correctamente:

sudo dpkg -i uptime-display.deb


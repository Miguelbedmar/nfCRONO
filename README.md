# nfCRONO

2. El proyecto.
ntfCRONOS es una solución tecnológica multiplataforma diseñada para gestionar y automatizar el control horario de entrada y salida de los trabajadores mediante una aplicación móvil y tarjetas de identificación inteligente (NFC/NFT). El sistema sustituye los tradicionales relojes de fichar de pared o hojas de firmas en papel por un terminal móvil ágil, económico y seguro.

Objetivos principales

- Cumplimiento normativo. Garantizar el registro diario y veraz de la jornada laboral de forma sencilla para empresas y empleados.
- Agilidad en el fichaje. Reducir los tiempos de espera en los accesos mediante lectura instantánea por proximidad (NFC) o validación de credencial única.
- Integridad de los datos. Evitar la manipulación horaria sincronizando cada registro con la hora oficial del servidor (protocolo NTP) en lugar de confiar en el reloj local del dispositivo.
- Trazabilidad y reportes. Facilitar a los responsables de Recursos Humanos la consulta en tiempo real de asistencia, retrasos y horas trabajadas.

Arquitectura y funcionamiento básico

1. Identificación: Cada empleado dispone de una tarjeta personal asociada de forma única a su perfil en el sistema.
2. Captura (App Móvil): Un dispositivo móvil (en modo quiosco en la entrada o el propio smartphone corporativo) lee la tarjeta y envía el identificador al servidor.
3. Procesamiento y almacenamiento: El backend valida al empleado, determina automáticamente si el movimiento es una entrada o una salida y guarda la marca de tiempo exacta en la base de datos. 

# Vehículo Polifuncional con Arduino

Este proyecto consiste en el desarrollo de un vehículo polifuncional utilizando Arduino, un MotorShield, motores reductores, servomotores, módulos RF y sensores para detectar líneas negras. El vehículo puede ser controlado tanto a través de un control remoto como mediante la detección de líneas negras.

## Características principales

- **Control remoto:** El vehículo puede ser controlado de forma inalámbrica utilizando un módulo RF y un control remoto. Esto permite al usuario controlar la dirección y la velocidad del vehículo de manera intuitiva.

- **Detección de líneas negras:** El vehículo está equipado con sensores especializados que permiten detectar y seguir líneas negras en una superficie. Utilizando algoritmos de seguimiento de líneas, el vehículo puede moverse de manera autónoma siguiendo una ruta predefinida.

- **MotorShield y motores reductores:** El MotorShield se encarga de controlar los motores reductores, proporcionando un control preciso de la velocidad y dirección del vehículo. Esto permite una amplia gama de maniobras y movimientos fluidos.

- **Servomotores:** Se han incorporado servomotores al vehículo para permitir el control de otros componentes, como brazos mecánicos o cámaras. Esto ofrece la posibilidad de expandir las capacidades del vehículo y realizar tareas adicionales según las necesidades del usuario.

## Instrucciones de instalación

1. Clona o descarga este repositorio en tu computadora.
2. Conecta el MotorShield a la placa Arduino según las especificaciones del fabricante.
3. Conecta los motores reductores y los servomotores a los puertos correspondientes en el MotorShield.
4. Conecta los módulos RF y los sensores de línea negra a los pines adecuados en la placa Arduino.
5. Abre el archivo principal del programa, `vehiculo_polifuncional.ino`, en el entorno de desarrollo de Arduino.
6. Selecciona la placa y el puerto serial correctos en el entorno de desarrollo.
7. Compila y carga el programa en la placa Arduino.
8. ¡Listo! El vehículo polifuncional está listo para ser utilizado.

## Uso

El repositorio incluye varios ejemplos de código que puedes utilizar como punto de partida para desarrollar tus propias funcionalidades. Asegúrate de revisar los archivos de ejemplo y las funciones disponibles en el código fuente.

Si deseas controlar el vehículo a través del control remoto, sigue las instrucciones proporcionadas por el fabricante del módulo RF para emparejar el control remoto con el receptor RF del vehículo.

Si deseas utilizar la detección de líneas negras, asegúrate de calibrar los sensores y ajustar los parámetros del algoritmo de seguimiento de líneas según tus necesidades.

## Contribuciones

Si deseas contribuir a este proyecto, eres bienvenido(a) a enviar tus propuestas a través de pull requests. También puedes reportar problemas o sugerir mejoras mediante la creación de issues en el repositorio.

## Licencia

Este proyecto se distribuye bajo la licencia [MIT

](https://opensource.org/licenses/MIT). Para obtener más detalles, consulta el archivo [LICENSE](LICENSE).

## Contacto

Si tienes alguna pregunta o comentario sobre el proyecto, no dudes en ponerte en contacto conmigo a través de mi dirección de correo electrónico: [miguela.hernandez@udea.edu.co](mailto:tu-email@example.com).



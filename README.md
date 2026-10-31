## Trabajo práctico final de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Prof. Ing. Daniel Márquez
* Título corto del trabajo: Placa carrier para ESP32-S3 DevKit
* Descripción: placa base (carrier) para la placa de desarrollo ESP32-S3 DevKit de 44 pines, pensada para su uso en las cátedras de la universidad. Expande todos los pines de la DevKit en dos tiras hembra rotuladas y agrega los periféricos que se usan en las prácticas: entrada de alimentación de 12 V con regulador a 5 V (la placa funciona sin necesidad de conectar el USB), dos LEDs, dos pulsadores, una salida a relé inversor de 220 V con LED indicador, una entrada analógica de 0–10 V protegida y un transceptor CAN (MCP2562) con terminación de 120 Ω seleccionable por jumper. PCB de dos capas con componentes solo en la cara superior.
* Cursada: OCT-NOV-DIC 2026


## Licencia de este trabajo ##
Este diseño de hardware se distribuye bajo la licencia **GNU General Public License v3.0 o posterior** (GPL-3.0-or-later). El texto completo está en el archivo [LICENSE](LICENSE).

Para este diseño, el "código fuente" en el sentido de la licencia son los archivos del proyecto KiCad que están en el directorio [pcb](pcb) (`.kicad_pro`, `.kicad_sch` y `.kicad_pcb`).

Las hojas de datos del directorio [info](info) son de sus respectivos fabricantes y no están alcanzadas por esta licencia.

## Estructura del repositorio ##

* [doc](doc): documentación propia del trabajo. En [doc/propuesta](doc/propuesta) está la propuesta presentada a la cátedra.
* [info](info): hojas de datos de los componentes principales (relé, transistor, regulador y transceptor CAN) y pinout de la placa ESP32-S3.
* [pcb](pcb): proyecto KiCad con el esquemático y el PCB.

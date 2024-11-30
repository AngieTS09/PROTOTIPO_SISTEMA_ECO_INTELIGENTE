# SISTEMA ECO INTELIGENTE 
## DESCRIPCIÓN DEL PROTOTIPO 

El prototipo surge como solución a la necesidad de monitorear y controlar condiciones ambientales en tiempo real, especialmente en entornos interiores donde es crucial obtener información precisa de temperatura, humedad y luminosidad para garantizar un ambiente adecuado o automatizar procesos. El sistema, diseñado para ser compacto, autónomo y de fácil acceso, enfrenta desafíos como la integración eficiente de sensores, la transmisión de datos a plataformas en la nube y la visualización interactiva de información.

Funciona a partir de una batería recargable que alimenta el sistema a través de un regulador 7805, convirtiendo el voltaje a 5V, y un switch que controla el encendido del ESP32. Una vez activado, el ESP32 recopila datos de un sensor DHT11, que mide temperatura y humedad, y de una fotorresistencia, que detecta la intensidad lumínica. Los datos son procesados y enviados a la pantalla OLED para su visualización en tiempo real, además de ser transmitidos mediante WiFi a la plataforma ThingSpeak, donde se almacenan y pueden consultarse de forma remota. Adicionalmente, una aplicación interactiva desarrollada en Streamlit utiliza los datos de ThingSpeak para generar gráficos dinámicos y análisis históricos accesibles desde cualquier navegador. Todos los componentes trabajan sincronizados para ofrecer un monitoreo eficiente y práctico de las condiciones ambientales.

## COMPONTENES 

En la siguiente figura se presentan los componentes principales utilizados para el sistema eco inteligente.

![Prototipo Completo](https://github.com/user-attachments/assets/f5f37829-1957-47bf-aa1a-ff8224fe7dac)

## DESARROLLO DEL PROTOTIPO

El paso a paso que realizamos con este proyecto lo puedes encontrar en el siguiente documento.

[Desarrollo del prototipo.pdf](https://github.com/user-attachments/files/17961601/Desarrollo.del.prototipo.pdf)

## MANUAL DE USUARIO

Si deseas saber cúal es su funcionamiento puedes guiarte por este manual 

[Manual de Usuario.pdf](https://github.com/user-attachments/files/17961608/Manual.de.Usuario.pdf)

## ANEXOS

### CÓDIGOS

[Uploading PCB_Digitales.ino…]()

[Uploading ThingSpeak_Sistema_Eco_Inteligente.ino…]()

### REGISTRO DE PROTOTIPO

[Registro_de_Prototipos_Digital.pdf](https://github.com/user-attachments/files/17963392/Registro_de_Prototipos_Digital.pdf)

## EXPLICACIÓN DEL PROTOTIPO

Link: https://www.youtube.com/shorts/mJnIRZn1CGk

## PAGINA WEB
 https://repositorio-esp32-tjs-sxfpatsk95uvxacfxpp47j.streamlit.app/


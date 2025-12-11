*This project has been created as part of the 42 curriculum by rhiguita

# NetPractice

## Descripción
NetPractice es un proyecto general de práctica diseñado para descubrir los fundamentos de las redes informáticas. El objetivo principal es configurar redes de pequeña escala simuladas, asegurando la comunicación entre dispositivos mediante la manipulación precisa de direcciones IP, máscaras de subred y tablas de enrutamiento.

A través de 10 niveles progresivos, este proyecto pone a prueba la comprensión lógica del direccionamiento TCP/IP y la resolución de problemas de conectividad (troubleshooting) en arquitecturas que van desde LANs simples hasta topologías jerárquicas con múltiples routers.

## Instrucciones

### Instalación y Ejecución
1.  Clona este repositorio o descarga los archivos fuente.
2.  Abre el archivo `index.html` en tu navegador web preferido (Chrome, Firefox, etc.).
3.  Ingresa tu **login** de 42 en el campo de texto para generar tu semilla única de ejercicios.

### Cómo Exportar y Entregar
1.  Resuelve cada nivel hasta que todos los objetivos estén en verde ("Status: OK").
2.  Haz clic en el botón **"Get my config"** para descargar la configuración en formato JSON (ej. `level1.json`).
3.  Asegúrate de tener los 10 archivos (del `level1.json` al `level10.json`) en la raíz de tu repositorio Git antes de hacer el push.

## Recursos y Conceptos

### Conceptos de Red Estudiados
Para completar este proyecto, ha sido necesario dominar los siguientes conceptos fundamentales:
* **TCP/IP Addressing:** Comprensión de las clases de direcciones y direccionamiento sin clases (CIDR).
* **Subnet Mask:** Cálculo de rangos de red, direcciones de broadcast y segmentación lógica.
* **Default Gateway:** Configuración de puertas de enlace para el tráfico fuera de la red local.
* **Routers & Switches:** Diferenciación entre conmutación de capa 2 (Switch) y enrutamiento de capa 3 (Router).
* **OSI Layers:** Comprensión práctica de las capas de Red (IP) y Enlace de Datos.

### Uso de IA y Metodología de Aprendizaje
Se utilizó Inteligencia Artificial (Gemini) como mentor técnico para profundizar en la lógica detrás de cada configuración, evitando el "prueba y error" en favor de la ingeniería de precisión.

**Áreas de asistencia:**
1.  **Cálculo de Subnetting (VLSM):** Análisis detallado de máscaras críticas como `/30` para enlaces punto a punto (WAN) y `/26` o `/27` para segmentación de LANs, entendiendo el tamaño de bloque y los saltos de red.
2.  **Análisis de Topología:** Desglose de niveles complejos (como el Nivel 10) en zonas lógicas: Borde, Distribución y Acceso.
3.  **Aplicación al Mundo Real:** Se extrapolaron los conocimientos del simulador para optimizar una red real (Tethering iPhone-Linux), aplicando conceptos como:
    * **TTL Spoofing** (Manejo del *Time To Live* en paquetes IP).
    * **DNS Override** (Configuración de servidores de nombres de baja latencia).
    * **Priorización de Interfaces** (Ethernet over USB vs Wi-Fi).

### Referencias Clásicas
* [Cisco Networking Academy - Subnetting Practice](https://www.cisco.com/)
* [RFC 1918 - Address Allocation for Private Internets](https://datatracker.ietf.org/doc/html/rfc1918)
* [Calculadora de Subredes IP](https://www.calculator.net/ip-subnet-calculator.html)

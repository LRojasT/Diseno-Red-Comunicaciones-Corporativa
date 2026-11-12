# 🌐 Diseño de Red de Comunicaciones Corporativa

Este proyecto detalla el diseño lógico y físico de una red de comunicaciones corporativa (LAN/WAN) para una empresa farmacéutica distribuida en tres sedes geográficas (Cuenca, Cáceres y Madrid), implementado y simulado en **Cisco Packet Tracer**.

La arquitectura está diseñada para soportar y priorizar tres flujos de trabajo críticos: monitorización IoT industrial (telemetría UDP), centralización de datos y servicios multimedia en la nube.

## ⚙️ Arquitectura y Tecnologías Implementadas

### Diseño Lógico y Enrutamiento
* **Segmentación Avanzada (VLSM):** Diseño de subredes para optimizar el espacio de direccionamiento IP y separar entornos críticos.
* **VLANs Independientes:** Aislamiento total del tráfico corporativo frente al tráfico de formación y de la nave industrial.
* **Enrutamiento Dinámico:** Configuración del protocolo **OSPF** para automatizar las tablas de enrutamiento, garantizar rutas alternativas ante fallos de fibra y gestionar de forma eficiente las máscaras de subred ajustadas.

### Análisis de Rendimiento (QoS y Cronogramas)
* **Cálculo de Latencias:** Análisis matemático de tiempos de propagación y transmisión entre sedes (enlaces de fibra óptica a 1 Gbps y conexiones WAN).
* **Calidad de Servicio (QoS):** Estrategia de priorización para el tráfico continuo de los sensores IoT y las videoconferencias frente a la navegación estándar.

## 📂 Contenido del Repositorio
* `*.pkt`: Archivo de simulación ejecutable en Cisco Packet Tracer con la topología completa.
* `Memoria.pdf`: Documento técnico exhaustivo con el detalle del subnetting (VLSM), cálculos de latencia, esquema físico/lógico y justificación de decisiones.
* `Cronogramas.jpg`: Diagramas de flujo de paquetes y cálculo de retardos en distintos escenarios de red.

---
*Proyecto académico desarrollado en la Universidad Politécnica de Madrid (UPM).*

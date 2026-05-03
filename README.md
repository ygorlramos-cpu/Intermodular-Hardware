# FitLife Gym - Infraestructura de Hardware

Este repositorio contiene la documentación técnica y el análisis de la infraestructura física diseñada para el gimnasio **FitLife Gym**, realizada para el módulo de **Fundamentos de Hardware (0371)**.

## 📋 Descripción del Proyecto
El objetivo es analizar y diseñar la infraestructura tecnológica necesaria para un entorno real (un gimnasio), asegurando un equilibrio entre rendimiento, coste y escalabilidad.

## 🏗️ Arquitectura del Sistema
La infraestructura se basa en un modelo de red local con un núcleo centralizado:

* **1 Servidor Dedicado:** Centraliza la base de datos de socios, gestiona la seguridad y garantiza disponibilidad 24/7.
* **3 Equipos Cliente:**
    * 1 puesto en Recepción (gestión de entradas y pagos).
    * 2 puestos para Entrenadores (diseño de rutinas y seguimiento).
* **Periféricos Especializados:** Control de acceso biométrico/RFID, impresoras multifunción y electrónica de red (Switch/Router).

## 💾 Especificaciones de Almacenamiento
Se ha optado por una solución 100% basada en **SSD** para maximizar la velocidad de respuesta:
* **Servidor:** 512 GB SSD NVMe (Alta velocidad para bases de datos).
* **Clientes:** 256 GB SSD SATA III (Agilidad en tareas administrativas).

## 🚀 Justificación Técnica
La importancia de esta configuración radica en:
1.  **Centralización:** Evita la dispersión de datos y asegura copias de seguridad íntegras.
2.  **Baja Latencia:** Los discos SSD permiten que el acceso de los socios por los tornos sea instantáneo.
3.  **Escalabilidad:** El sistema permite añadir más memoria RAM o almacenamiento si el gimnasio crece en el futuro.

## 🛠️ Tecnologías y Componentes
* **Procesadores:** Intel Core i5 / Ryzen 5 (Servidor) e Intel Core i3 / Ryzen 3 (Clientes).
* **Memoria:** 16GB RAM (Servidor) / 8GB RAM (Clientes).
* **Red:** Conectividad Ethernet Gigabit para mínima latencia.

---
**Autor:** [Tu Nombre]
**Módulo:** Fundamentos de Hardware (0371)
**Proyecto:** Proyecto Intermodular - PROMETΞΟ

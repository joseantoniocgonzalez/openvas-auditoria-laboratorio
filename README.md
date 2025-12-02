# Auditoría de vulnerabilidades con OpenVAS (laboratorio)

Este repositorio recoge un trabajo práctico de auditoría de vulnerabilidades realizado con **OpenVAS/Greenbone** en un **entorno de laboratorio**. El objetivo es documentar de forma ordenada el proceso completo: instalación de la herramienta, configuración inicial, realización de escaneos, análisis de resultados, demostración de parcheo y configuración de alertas y monitorización continua.

Todo el trabajo se ha realizado sobre sistemas Linux y redes controladas, con fines exclusivamente formativos.

---

## Objetivos del proyecto

- Instalar y poner en marcha OpenVAS/Greenbone en un entorno de pruebas.
- Realizar escaneos de vulnerabilidades sobre equipos y redes de laboratorio.
- Analizar los informes generados e interpretar los resultados.
- Demostrar el proceso de **parcheo de vulnerabilidades** detectadas.
- Configurar **monitorización continua** de objetivos.
- Configurar **alertas por correo electrónico** ante cambios en el estado de las vulnerabilidades.

---

## Estructura del repositorio

```text
openvas-auditoria-laboratorio
├── Escaneres de vulnerabilidades
│   ├── Análisis detallado informes obtenidos.md
│   ├── Configuración de alertas de correo. Demostración.md
│   ├── Configuración inicial.md
│   ├── Demostración parcheo de vulnerabilidad.md
│   ├── Instalación.md
│   ├── Monitorización continua. Demostración.md
│   ├── Prueba uso en equipo individual.md
│   ├── Prueba uso en red.md
│   └── img/
└── README.md



 **`Análisis detallado informes obtenidos.md`**  
  Revisión y explicación de los informes generados: tipos de vulnerabilidad, criticidad, clasificación, ejemplos de hallazgos.

- **`Demostración parcheo de vulnerabilidad.md`**  
  Ejemplo práctico de ciclo completo: detección → parcheo/mitigación → reescaneo para verificar la corrección.

- **`Monitorización continua. Demostración.md`**  
  Configuración de tareas recurrentes de escaneo y revisión de los resultados en el tiempo.

- **`Configuración de alertas de correo. Demostración.md`**  
  Configuración de alertas por correo electrónico para recibir notificaciones cuando cambian los resultados de los escaneos (nuevas vulnerabilidades, cambios de estado, etc.).


## Capturas de pantalla (`Escaneres de vulnerabilidades/img/`)

La carpeta `img/` contiene capturas de pantalla que ilustran los distintos pasos del trabajo:

- Proceso de instalación y configuración.
- Paneles de OpenVAS/Greenbone.
- Informes y listados de vulnerabilidades.
- Configuración de tareas, monitorización y alertas de correo.

Estas imágenes se pueden referenciar desde los documentos Markdown para facilitar la lectura visual del proceso.


## Tecnologías y conceptos trabajados

En este trabajo se han utilizado y reforzado los siguientes conocimientos:

- **OpenVAS / Greenbone** como plataforma de análisis de vulnerabilidades.
- **Sistemas Linux** como base del entorno de laboratorio.
- Conceptos de **escaneo de red** y descubrimiento de servicios.
- Identificación y análisis de **vulnerabilidades** según su criticidad.
- **Parcheo y mitigación** de vulnerabilidades detectadas.
- **Monitorización continua** de objetivos.
- Configuración de **alertas por correo electrónico**.
- Buenas prácticas básicas en **ciberseguridad a nivel de sistemas y redes**.

---

## Alcance y uso

- Este repositorio está orientado a mostrar **trabajo práctico real** en un entorno de laboratorio, con fines didácticos.
- No se incluyen datos de empresas ni información sensible.
- Cualquier uso de OpenVAS/Greenbone u otras herramientas de auditoría sobre sistemas de terceros debe hacerse **siempre con autorización expresa** y cumpliendo la legislación vigente.

---

## Autor

Trabajo realizado por **Jose Antonio Canalo Gonzalez**  
Junior Cloud & DevOps Engineer | SysAdmin & Cybersecurity Oriented

Puedes encontrar más información sobre mi perfil profesional y otros proyectos en mi perfil de LinkedIn:

- [linkedin.com/in/joseantoniocgonzalez](https://www.linkedin.com/in/joseantoniocgonzalez/)


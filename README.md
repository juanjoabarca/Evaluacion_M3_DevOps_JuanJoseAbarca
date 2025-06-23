# 🚛 Informe DevOps - TransChile

Este repositorio contiene el informe y entregable correspondiente a la **Evaluación del Módulo 3 (EV-M3)** del BootCamp DevOps TD 2025, desarrollado por **Juan José Abarca**.

El proyecto simula un caso real en el que una empresa ficticia —TransChile— requiere mejorar su ciclo de desarrollo de software incorporando herramientas de control de versiones, integración continua y análisis de seguridad.

## 🌐 Visualización en línea

Puedes ver el informe completo alojado en GitHub Pages aquí:

🔗 **[Ver informe web](https://juanjoabarca.github.io/Evaluacion_M3_DevOps_JuanJoseAbarca)**

---

## 📁 Contenido del informe

El informe se encuentra estructurado en formato web responsive utilizando [Pico.css](https://picocss.com/) y está dividido en las siguientes secciones:

- **🎯 Contexto:** Presentación del caso y problemática de la empresa TransChile.
- **📋 Análisis del estado actual:** Diagnóstico técnico del entorno actual de desarrollo.
- **🔁 Propuesta de control de versiones:** Implementación de Git con flujos basados en `main`, `staging` y `develop`.
- **🚀 CI/CD:** Automatización del ciclo de vida con GitHub Actions, pruebas, escaneo de seguridad y despliegues por entorno.
- **🛡️ Seguridad:** Integración de herramientas como SonarQube, Safety, Bandit y Trivy para mantener un código seguro.
- **📦 Conclusión:** Cierre y reflexiones finales sobre los beneficios implementados.

---

## ⚙️ Automatización del proyecto

Se integró un pipeline CI/CD usando **GitHub Actions**, que contempla:

- Lint y formato con `black` y `flake8`
- Pruebas unitarias con Django
- Análisis de seguridad en código (`bandit`) y dependencias (`safety`)
- Escaneo de contenedores Docker (`trivy`)
- Análisis estático de código con **SonarQube**
- Despliegue simulado en `staging` y `main`

El archivo `.github/workflows/django.yml` contiene toda la configuración y puede adaptarse fácilmente a proyectos reales.

---

## 🧾 Autor

**Juan José Abarca**  
Bootcamp DevOps TD 2025 – Módulo 3

---

## 📄 Licencia

Este repositorio tiene fines educativos y no representa una solución oficial de TransChile ni refleja datos reales de la empresa.

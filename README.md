🦷 OdontoGest

OdontoGest es una aplicación web desarrollada como proyecto final de Arquitectura Cloud (AWS Women in Cloude BA), diseñada para simplificar la gestión diaria de un consultorio odontológico mediante una solución simple, confiable y preparada para crecer.
---
 ✨ Funcionalidades
- 🏠 Landing Page institucional
- 🔐 Inicio de sesión
- 📅 Agenda diaria
- 📝 Notas rápidas para continuidad operativa
- 🚪 Cierre de sesión
- 🐳 Dockerizado
---
🛠 Tecnologías utilizadas
- Python
- Flask
- HTML5
- CSS3
- Bootstrap
- Docker
---
☁️ Arquitectura AWS
La solución fue diseñada utilizando los siguientes servicios:
- Amazon EC2
- Amazon RDS PostgreSQL (Multi-AZ)
- Amazon S3
- AWS IAM
- Amazon CloudWatch
- Amazon SNS
- Amazon Route 53
La documentación completa de la arquitectura se encuentra en la carpeta **docs/**.
---

🚀 Ejecutar el proyecto
Clonar el repositorio:
```bash
git clone https://github.com/kat-perdomo/OdontoGest.git
```
Ingresar a la carpeta:
```bash
cd OdontoGest
```
Levantar la aplicación:
```bash
docker compose up
```
Abrir en el navegador:
```
http://localhost:5000
```
---
 📁 Documentación
El proyecto incluye documentación sobre:
- Descripción de la aplicación
- Arquitectura Local
- Arquitectura AWS
- AWS Well-Architected Framework
- Estimación de costos
- Plan de Disaster Recovery
---
🚀 Roadmap
Próximas funcionalidades previstas:
- 👥 Gestión de pacientes
- 📋 Historia clínica
- 💳 Gestión de pagos
- 📲 Progressive Web App (PWA)
- ☁️ Despliegue en Amazon EC2
- 🔄 CI/CD con GitHub Actions
---
💜 Sobre el proyecto

OdontoGest nació a partir de una necesidad real: ayudar a digitalizar la gestión de un consultorio odontológico que actualmente trabaja con agendas físicas y procesos manuales.
El objetivo del proyecto fue diseñar una solución simple, intuitiva y escalable, priorizando la experiencia del profesional y la continuidad del servicio.
---

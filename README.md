# SledgeSecurity


<p align="center"><img src="logosledgesecurity.jpg" alt="drawing" style="width:500px;"/></p>

<p align="center">Proyecto fin de grado de Luis Miguel Miras Díaz y Rafael Jiménez Burgos.</p>

# Checkpoint
[Video CheckPoint](https://youtu.be/CTjzCZpz3cc)

# Video final
[Video final de grado](https://youtu.be/rcl0OyXX8Us)

### Software Utilizado y versiones:
- Jenkins 2.452.1
- Docker 24.0.5
- SonarQube Community Edition v9.9.5 (Bajo Docker)
- Prometheus 2.52.0 y Grafana 11.0.0
- Email Notification

# Histórico de cambios
Inicio de proyecto hasta 03/06/2024
- Se ha creado dos instancias EC2, Jenkins-Master y Jenkins-Agent.
- Se ha añadido la funcionalidad de notificación por Email en Jenkins.
- Se ha levantado y configurado SonarQube bajo Docker.
- Se ha configurado Prometheus (Sistema de monitorización y alertas), junto a Grafana.

## Direcciones URL de las instancias EC2 creadas en AWS
* Jenkins: https://proyectoasirjenkins.ddns.net/
* SonarQube: http://54.85.121.151:9000/
* Grafana: http://44.223.163.86:3000/
* Prometheus: http://44.223.163.86:9090/

### Bibliografía
- [Instalar Jenkins en Linux](https://www.jenkins.io/doc/book/installing/linux/)
- [SonarQube con Docker Compose](https://medium.com/@denis.verkhovsky/sonarqube-with-docker-compose-complete-tutorial-2aaa8d0771d4)
- [Instalar Prometheus en Linux](https://prometheus.io/docs/prometheus/latest/getting_started/)
- [Instalar Grafana en Linux](https://grafana.com/docs/grafana/latest/setup-grafana/installation/debian/)
- [Instalar SonarQube con Docker](https://docs.sonarsource.com/sonarqube/latest/setup-and-upgrade/install-the-server/installing-sonarqube-from-docker/)

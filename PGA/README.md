# 📊 PGA Stack (Prometheus + Grafana + Alertmanager)

Este repositorio contiene un stack de monitorización listo para usar con **Prometheus**, **Grafana** y **Alertmanager** conocido como el **PGA Stack**.

Con este stack puedes recolectar métricas, visualizar datos en tiempo real y generar alertas para mantener el control de tu infraestructura o aplicaciones.

---

## ✅ Requisitos

Antes de desplegar el stack PGA, asegúrate de tener instaladas las siguientes versiones mínimas:

- **Docker**: `>= 27.5.1`  
  Verifica con:
  ```bash
  docker --version
  ```

- **Docker Compose**: `>=  2.33.1`  
  Verifica con:
  ```bash
  docker compose version
  ```
- Sistema operativo: Probado en Linux (ej. Fedora, Ubuntu), pero debería funcionar en cualquier sistema compatible con Docker.

- Acceso a internet: Necesario para descargar las imágenes de Docker en el primer despliegue.

+ Puertos requeridos:

  + 9090 → Prometheus

  + 9093 → Alertmanager

  + 3000 → Grafana

## 📦 Componentes

- **Prometheus**: Sistema de recolección y consulta de métricas basado en series temporales.
- **Alertmanager**: Enrutamiento, agrupamiento y envío de alertas de Prometheus.
- **Grafana**: Visualización de métricas a través de dashboards interactivos.


## 🚀 Despliegue
  ```bash
docker compose up -d
  ```

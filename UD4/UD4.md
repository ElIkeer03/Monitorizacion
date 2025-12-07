# Puertos

![Status](https://img.shields.io/badge/Estado-Finalizado-success) ![Curso](https://img.shields.io/badge/Curso-2º_ASIR-blue) ![Sistema](https://img.shields.io/badge/OS-Ubuntu_Linux-orange)

Documentación técnica de los comandos utilizados para el análisis de sockets, descubrimiento de hosts y tablas ARP.

---

## 1. Monitorización de Sockets

### 📊 Conexiones detalladas (con timers)
Muestra todas las conexiones TCP establecidas sin resolver nombres de dominio (para mayor velocidad).

```bash
sudo ss -ntop

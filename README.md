# CambioTrack — Detección de Cambios Web como Servicio

Monitoreo inteligente de páginas web con alertas instantáneas. Basado en [Changedetection.io](https://github.com/dgtlmoon/changedetection.io) (Apache 2.0 License).

## Stack
- **Changedetection.io** — motor de detección de cambios (1 contenedor)
- **Dokploy** — orquestación, proxy inverso y SSL automático

## Despliegue en Dokploy

1. Crear proyecto tipo **Compose**
2. Pegar el `docker-compose.yml`
3. Asignar dominio al servicio `changedetection` → puerto **5000**

## Planes
| Plan | Monitores | Precio/mes |
|------|-----------|------------|
| Starter | 10 | $9 |
| Pro | 50 | $19 |
| Business | 200 | $39 |

## Complementario con MonitorPro
- **MonitorPro** → ¿está caído tu sitio?
- **CambioTrack** → ¿cambió algo en la web que te importa?

Vendelos juntos: $18/mes por ambos servicios.

## Licencia
Changedetection.io: Apache 2.0. Código propio de CambioTrack: MIT.

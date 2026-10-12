<div align="center">

# Finanzi

**Gestión de finanzas personales con lectura automática de facturas**

App móvil (Android) + aplicación web, conectadas a los mismos datos.

[![Google Play](https://img.shields.io/badge/Google_Play-Disponible-2E7D32?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.waranitech.finanziapp)
[![Web](https://img.shields.io/badge/Web-finanzi.waranitech.com-1B5E20?logo=googlechrome&logoColor=white)](https://finanzi.waranitech.com)
![Estado](https://img.shields.io/badge/Estado-En_producción-success)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white)

<img src="assets/videos/flujo-ocr.gif" alt="Registro de una factura con OCR en la app" width="280">

</div>

> **Nota:** este repositorio es una **vitrina del producto**. El código fuente de Finanzi es privado. Aquí se muestran el alcance y las funcionalidades, con capturas y videos de la app y de la web. Todos los datos que se ven son de demostración.

---

## Contenido

- [¿Qué es Finanzi?](#qué-es-finanzi)
- [Funcionalidades](#funcionalidades)
- [Capturas: app móvil](#capturas-app-móvil)
- [Capturas: aplicación web](#capturas-aplicación-web)
- [Videos](#videos)
- [Tecnologías](#tecnologías)
- [Autor](#autor)

---

## ¿Qué es Finanzi?

Finanzi ayuda a las personas a **registrar sus gastos e ingresos sin cargar datos a mano**. El usuario saca una foto o sube el PDF de una factura, Finanzi extrae automáticamente el emisor, el número de identificación fiscal, la fecha, el total y los impuestos, y la registra después de que el usuario revisa los datos.

A partir de esos registros, la app muestra el balance del mes o del año, límites de gasto por mes, reportes por categoría y exportaciones listas para compartir.

**Producto en producción**, con planes gratuito y pagos, publicado en Google Play y disponible en la web.

## Funcionalidades

### Registro de gastos e ingresos
- **OCR de facturas** desde la cámara, la galería o un PDF.
- **Facturas largas** en dos fotos para comprobantes que no entran en una sola imagen.
- **Revisión previa:** el usuario confirma o corrige los datos detectados antes de guardar.
- Verificación de que el comprobante está a nombre del usuario.
- **Gasto rápido** para consumos pequeños sin factura y transferencias.
- Registro, edición y eliminación de ingresos fijos, variables y extraordinarios.

### Análisis y reportes
- Dashboard con balance, ingresos, gastos y actividad reciente por mes, mes anterior o año.
- **Límite mensual de gasto** con seguimiento del porcentaje usado.
- Historial con filtros por fecha y categoría.
- Reportes con gráficos de evolución y distribución por categoría.
- **Exportación a PDF, Excel y CSV.**

### Cuenta, planes y operación
- Inicio de sesión con correo y contraseña o con Google; recuperación y reactivación de cuenta.
- Planes gratuito, básico y premium.
- **Suscripciones** desde la app y **pagos** desde la web.
- Notificaciones push y avisos de renovación.

## Capturas: app móvil

| Control del mes | Comprobantes | Facturas largas |
|:---:|:---:|:---:|
| <img src="assets/app/02-control-del-mes.jpg" width="260"> | <img src="assets/app/03-comprobantes.jpg" width="260"> | <img src="assets/app/04-facturas-largas.jpg" width="260"> |
| **Límite mensual** | **Reportes** | **Exportación** |
| <img src="assets/app/05-limite-mensual.jpg" width="260"> | <img src="assets/app/06-reportes-claros.jpg" width="260"> | <img src="assets/app/07-exportacion.jpg" width="260"> |

## Capturas: aplicación web

| Página principal | Dashboard |
|:---:|:---:|
| <img src="assets/web/01-landing.jpg" width="420"> | <img src="assets/web/02-dashboard.jpg" width="420"> |
| **Movimientos** | **Registrar factura con OCR** |
| <img src="assets/web/03-movimientos.jpg" width="420"> | <img src="assets/web/05-registrar-factura-ocr.jpg" width="420"> |
| **Historial por período** | **Ingresos** |
| <img src="assets/web/06-historial.jpg" width="420"> | <img src="assets/web/07-ingresos.jpg" width="420"> |
| **Reportes** | **Gráficos por categoría** |
| <img src="assets/web/08-reportes.jpg" width="420"> | <img src="assets/web/09-reportes-graficos.jpg" width="420"> |

## Videos

| Recorrido general | Factura con OCR | Nueva versión |
|:---:|:---:|:---:|
| <img src="assets/videos/demo-1.gif" width="240"> | <img src="assets/videos/demo-2.gif" width="240"> | <img src="assets/videos/demo-3.gif" width="240"> |
| Gastos rápidos, historial, reportes y exportación | De la foto de la factura al registro en el historial | Límites mensuales, facturas largas y transferencias |

## Tecnologías

Flutter · Django · FastAPI · Python · Firebase · Google Cloud

¿Te interesa conocer la arquitectura y las decisiones técnicas detrás de Finanzi? Te lo cuento en una llamada: [escríbeme por LinkedIn](https://linkedin.com/in/oscar-ramirez-franco).

## Autor

**Oscar David Ramírez Franco** — Fundador de [WaraniTech](https://waranitech.com) · Flutter Senior & Full Stack (Python · Django · FastAPI)

[LinkedIn](https://linkedin.com/in/oscar-ramirez-franco) · [GitHub](https://github.com/odafra) · [Web personal](https://odafra.waranitech.com)

¿Necesitas una app o una plataforma similar? Escríbeme por LinkedIn o desde [waranitech.com](https://waranitech.com).

---

<sub>© WaraniTech. Todos los derechos reservados. Las imágenes y los videos de este repositorio no pueden reutilizarse sin autorización. Ver [LICENSE](LICENSE).</sub>

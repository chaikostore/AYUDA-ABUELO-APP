# 👴 Ayuda Abuelo App

Una aplicación móvil desarrollada en **Kotlin y Jetpack Compose** diseñada especialmente para adultos mayores. Su objetivo principal es facilitar la gestión diaria de su salud, recordándoles de forma visual y auditiva sus medicamentos y turnos médicos, además de permitirles llevar un control de su presión arterial de manera muy sencilla.

---

## 🚀 Características Principales

- **💊 Mis Medicinas:** 
  - Registro de medicamentos con foto real de la caja o pastilla (capturada desde la cámara).
  - Ingreso de dosis personalizada (ej: `1`, `1/2`, `2`).
  - Sistema de alarmas automáticas exactas (`AlarmManager`) calculadas según las horas y días indicados.
  - Interfaz de alto contraste y botones grandes pensados para una fácil lectura.
- **🩺 Control de Presión Arterial:** 
  - Anotación diaria dividida por momentos (Mañana, Tarde, Noche).
  - Historial ordenado con la posibilidad de compartir los reportes fácilmente.
- **📅 Turnos Médicos:** 
  - Agenda de consultas médicas con alertas programables de anticipación.
  - Botón directo de llamadas de emergencia o al médico de cabecera.
- **📢 Accesibilidad y Avisos:** 
  - Tonos adaptados, notificaciones push interactivas y soporte para pantallas ajustables.
- **💵 Monetización:** 
  - Integración con Google AdMob (`BannerAd`) para la visualización de anuncios en la parte superior.

---

## 🛠️ Tecnologías y Librerías Utilizadas

- **UI:** [Jetpack Compose](https://developer.android.com/jetpack/compose) (Material Design 3)
- **Lenguaje:** Kotlin
- **Base de Datos Local:** Room Database
- **Gestión de Fechas y Tiempos:** Kotlinx-datetime / Java Calendar
- **Alarmas y Sistema:** Android `AlarmManager` y `BroadcastReceiver`
- **Permisos:** Accompanist Permissions / Activity Result Contracts
- **Publicidad:** Google Mobile Ads SDK (AdMob)

---

## 📱 Capturas de Pantalla / Vistas
*(Aquí puedes subir más adelante algunas capturas de las pantallas principales de tu app)*

---

## 📦 Instalación y Ejecución

1. Clona este repositorio o descarga el archivo ZIP:
   ```bash
   git clone [https://github.com/tu-usuario/AyudaAbueloApp.git](https://github.com/tu-usuario/AyudaAbueloApp.git)
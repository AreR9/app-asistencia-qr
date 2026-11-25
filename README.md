<div align="center">

# 📱 Asistencia QR

### App móvil para tomar asistencia con códigos QR, con vista de alumno y de profesor

<br>

![Thunkable](https://img.shields.io/badge/Thunkable-0A6CFF?style=for-the-badge)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![QR](https://img.shields.io/badge/QR-Asistencia-8B5CF6?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Versión](https://img.shields.io/badge/versión-2.0-2563eb?style=for-the-badge)

<br>

[![Descargar APK](https://img.shields.io/badge/⬇️_Descargar_APK-v2.0-2ea44f?style=for-the-badge)](https://github.com/AreR9/app-asistencia-qr/releases/latest)

</div>

---

## ✨ ¿Qué es?

Una aplicación Android desarrollada en **Thunkable** que digitaliza el pase de lista. Tiene **dos vistas en la misma app**, una para alumnos y otra para profesores, cada una con su propia cuenta. El alumno muestra un QR único y el profesor lo escanea para registrar la asistencia, que queda guardada **en tiempo real** en una hoja de Excel.

## 🎯 Características

| | Característica |
|:---:|:---|
| 👥 | **Dos vistas** en una sola app: alumno y profesor |
| 🔐 | **Cuentas de usuario** para cada rol |
| 🧾 | **QR generado automáticamente** para el alumno, con día, fecha y datos de la sesión |
| 📷 | **Escáner de QR** con la cámara del teléfono del profesor |
| 📝 | **Cuestionario de Forms** para verificar la fecha, la hora y la clase |
| 📊 | **Registro en tiempo real** en una hoja de Excel |

## 🔄 Cómo funciona

```mermaid
flowchart LR
    A[🎓 Alumno inicia sesión] --> B[🧾 Se genera su QR]
    B --> C[👨‍🏫 Profesor escanea el QR]
    C --> D[📝 Llena el cuestionario: fecha, hora y clase]
    D --> E[📊 Se registra en Excel en tiempo real]
```

### 🎓 Vista del alumno
1. Inicia sesión con su cuenta.
2. La app genera automáticamente su QR con el día, la fecha y los datos de la sesión.
3. Le muestra el QR al profesor desde su teléfono.

### 👨‍🏫 Vista del profesor
1. Inicia sesión con su cuenta.
2. Abre la cámara y escanea el QR en el teléfono del alumno.
3. Llena el cuestionario para confirmar la fecha, la hora y la clase.
4. La asistencia se guarda al instante en la hoja de Excel.

## 📸 Capturas

<div align="center">

| Vista del alumno | Vista del profesor |
|:---:|:---:|
| <img src="capturas/alumno.png" width="250"> | <img src="capturas/profesor.png" width="250"> |

</div>

## 📥 Instalación

1. Entra a [**Releases**](https://github.com/AreR9/app-asistencia-qr/releases/latest).
2. Descarga el **APK** en tu celular Android.
3. Permite la instalación de orígenes desconocidos si el sistema lo pide.
4. Abre el archivo e instala la app.

## 🛠️ Tecnologías

- **Thunkable**: desarrollo de la app con bloques
- **Generación y lectura de códigos QR**
- **Formulario (Forms)** para la verificación de la sesión
- **Excel** como registro de asistencia en tiempo real

## 📄 Documentación

- [Documentación final](docs/Documentación%20Final%20app%20Asistencia.pdf)
- [Proyecto App Asistencia](docs/Proyecto%20App_Asistencia%206.pdf)

---

<div align="center">

### 👩‍💻 Desarrollado por **Areli Reynoso**

[![GitHub](https://img.shields.io/badge/GitHub-AreR9-181717?style=flat-square&logo=github)](https://github.com/AreR9)

</div>

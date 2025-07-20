# 🔐 SSH Tunnel App by CrisDEV

<p align="center">
  <img src="cris.png" alt="CrisDEV Logo" width="100" height="100">
</p>

<p align="center">
  <strong>Aplicación SSH Tunnel con múltiples protocolos de conexión segura</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Platform-Android-orange.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Developer-CrisDEV-purple.svg" alt="Developer">
</p>

## 📱 Descripción

SSH Tunnel App es una aplicación avanzada que permite establecer conexiones SSH seguras utilizando múltiples protocolos de túnel. Diseñada para ofrecer máxima flexibilidad y seguridad en tus conexiones de red.

## ✨ Características Principales

- 🔒 **7 Protocolos de Túnel Soportados**
- 🚀 **Conexiones Rápidas y Estables**
- 🛡️ **Cifrado End-to-End**
- 📊 **Monitoreo de Conexión en Tiempo Real**
- 🎯 **Interfaz Intuitiva**
- 🌐 **Soporte Multiplataforma**

## 🔧 Protocolos Soportados

La aplicación implementa los siguientes tipos de túnel:

| Protocolo | Tipo | Descripción |
|-----------|------|-------------|
| **SSH_DIRECT** | `1` | Conexión SSH directa estándar |
| **SSH_PROXY** | `2` | SSH a través de proxy |
| **SSH_SSL** | `3` | SSH con capa SSL adicional |
| **PAY_SSL** | `4` | SSL de pago premium |
| **SLOWDNS** | `5` | Túnel DNS lento para evasión |
| **UDP** | `6` | Protocolo UDP para velocidad |
| **V2RAY** | `7` | Protocolo V2Ray avanzado |

## 🚀 Instalación

### Requisitos del Sistema
- Android 5.0+ (API 21)
- 50MB de espacio libre
- Conexión a internet

### Pasos de Instalación
1. Descarga el archivo APK desde [Releases](../../releases)
2. Habilita "Fuentes desconocidas" en la configuración de Android
3. Instala la aplicación
4. Concede los permisos necesarios

## 📖 Uso

### Configuración Básica
1. **Abrir la aplicación**
2. **Seleccionar tipo de protocolo** (SSH_DIRECT, SSH_PROXY, etc.)
3. **Configurar datos del servidor**:
   - Host/IP del servidor
   - Puerto de conexión
   - Usuario y contraseña
4. **Establecer conexión**

### Configuración Avanzada
- **Proxy Settings**: Para SSH_PROXY
- **SSL Certificates**: Para SSH_SSL y PAY_SSL
- **DNS Configuration**: Para SLOWDNS
- **V2Ray Config**: Para protocolo V2Ray

## 🛠️ Configuración de Desarrollo

### Estructura del Proyecto
```
ssh-tunnel-app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── res/
│   │   └── AndroidManifest.xml
│   └── test/
├── assets/
│   └── logo.png
└── build.gradle
```

### Tecnologías Utilizadas
- **Android SDK**: Desarrollo nativo Android
- **SSH Libraries**: Para conexiones SSH seguras
- **OpenSSL**: Cifrado y certificados
- **V2Ray Core**: Implementación del protocolo V2Ray

## 📊 Características Técnicas

### Seguridad
- ✅ Cifrado AES-256
- ✅ Autenticación por clave pública
- ✅ Verificación de certificados SSL
- ✅ Protección contra ataques MITM
- ✅ Logs cifrados localmente

### Rendimiento
- ⚡ Conexiones optimizadas
- 📈 Monitoreo de latencia
- 💾 Uso eficiente de memoria
- 🔄 Reconexión automática
- 📱 Optimizado para dispositivos móviles

## 💰 Modelo de Monetización

La aplicación es **gratuita** y se mantiene a través de:
- 📢 **Anuncios no intrusivos**
- ☕ **Donaciones voluntarias**
- 🏆 **Versión Premium** (sin anuncios)

Los ingresos se destinan a:
- 🖥️ Mantenimiento de servidores
- 🔧 Desarrollo y mejoras
- 🛡️ Actualizaciones de seguridad
- 📞 Soporte técnico

## 🔒 Privacidad y Seguridad

- 📋 **[Política de Privacidad Completa](index.html)**
- 🚫 **No recopilamos datos personales sensibles**
- 🔐 **Datos de conexión cifrados localmente**
- 🌐 **Cumplimiento con GDPR y regulaciones locales**

## 🐛 Reporte de Bugs

¿Encontraste un bug? ¡Ayúdanos a mejorarlo!

1. **Verifica** que no esté ya reportado en [Issues](../../issues)
2. **Crea un nuevo issue** con:
   - Descripción detallada del problema
   - Pasos para reproducir
   - Capturas de pantalla (si aplica)
   - Información del dispositivo

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Para contribuir:

1. **Fork** el repositorio
2. **Crea** una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. **Abre** un Pull Request

## 📞 Soporte y Contacto

### 🆘 Soporte Técnico
- 📧 **Email**: [soportecrisdev@gmail.com](mailto:soportecrisdev@gmail.com)
- ⏰ **Tiempo de respuesta**: 24-48 horas
- 🗣️ **Idiomas**: Español, Inglés

### 👨‍💻 Desarrollador
- **Nombre**: CrisDEV
- **Especialidad**: Desarrollo de aplicaciones de red y seguridad
- **GitHub**: [@soportecrisdev](https://github.com/soportecrisdev)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

```
MIT License

Copyright (c) 2025 CrisDEV

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🏆 Características Próximas

- [ ] 🌙 Modo oscuro
- [ ] 📊 Dashboard de estadísticas
- [ ] 🔄 Sincronización en la nube
- [ ] 🌍 Más idiomas
- [ ] 📱 Versión iOS
- [ ] 🎮 Modo gaming (baja latencia)

## ⭐ Agradecimientos

- A la comunidad de código abierto
- A los beta testers
- A todos los usuarios que reportan bugs
- A los contribuidores del proyecto

---

<p align="center">
  <strong>Desarrollado con ❤️ por CrisDEV</strong>
</p>

<p align="center">
  <a href="mailto:soportecrisdev@gmail.com">📧 Contacto</a> •
  <a href="privacy-policy.html">🔒 Privacidad</a> •
  <a href="../../releases">📱 Descargas</a>
</p>

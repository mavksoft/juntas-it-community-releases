<p align="center">
  <img src="https://it-community.online/assets/logo.png" alt="IT-Community" width="96">
</p>

<h1 align="center">Juntas — IT-Community</h1>

<p align="center">La app de juntas de vecinos del ecosistema IT-Community.<br>Convocatorias, documentación y acceso al portal de tu comunidad — en Android, iOS, Windows y macOS.</p>

<p align="center">
  <a href="https://it-community.online"><img src="https://img.shields.io/badge/website-it--community.online-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/juntas-it-community-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/juntas-it-community-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-Android%20%C2%B7%20iOS%20%C2%B7%20Windows%20%C2%B7%20macOS-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/juntas-it-community-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/juntas-it-community-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <strong>🇪🇸 Español</strong> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Este repositorio publica únicamente releases oficiales** — el código fuente es privado. Descargas firmadas, checksums y feeds de auto-actualización.

## Descarga

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/juntas-it-community-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **macOS** | [Juntas-<versión>.dmg](https://github.com/mavksoft/juntas-it-community-releases/releases/latest) en cada release |
| <img src='https://raw.githubusercontent.com/mavksoft/juntas-it-community-releases/main/icons/android.svg' width='15' style='vertical-align:-2px' alt='android'><img src='https://raw.githubusercontent.com/mavksoft/juntas-it-community-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **Móvil** | Android e iOS — desde las tiendas o los enlaces de [it-community.online](https://it-community.online) |
| <img src='https://raw.githubusercontent.com/mavksoft/juntas-it-community-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Windows** | Instalador disponible en cada release |
| <img src='https://it-community.online/assets/logo.png' width='15' style='vertical-align:-2px'> **Web oficial** | [it-community.online](https://it-community.online) |

## Qué es

Juntas es la aplicación de asambleas del ecosistema IT-Community: conecta con el portal de tu comunidad de propietarios para recibir convocatorias, consultar la documentación de cada junta y seguir la vida de tu comunidad desde cualquier dispositivo. Este repositorio distribuye los binarios públicos y los feeds de auto-actualización.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funciones

- **Conexión con tu portal** — la app se enlaza al portal IT-Community de tu comunidad vía el directorio `portals.json`.
- **Multi-plataforma** — builds para Android, iOS, Windows y macOS.
- **Auto-actualización** — `version.json` y `appcast.xml` alimentan el actualizador integrado.
- **Documentación de juntas** — convocatorias, actas y anexos del portal, en el móvil y el escritorio.

## Cómo se usa

1. Descarga la build de tu plataforma desde la última release (o instala la app móvil desde tu tienda).
2. Abre la app y localiza tu comunidad en el directorio de portales.
3. Accede con las credenciales que te dio tu administrador de fincas.
4. Consulta convocatorias, actas y documentación de cada junta desde la app.

## Requisitos

Android, iOS, Windows 10+ o macOS reciente · Requiere que tu comunidad tenga portal IT-Community (lo gestiona tu administrador de fincas).

## Qué contiene este repositorio

- `Juntas-<versión>.dmg` — instalador macOS firmado
- `Juntas-<versión>.zip` — build empaquetada / auto-actualización
- `version.json` — feed de versión para el actualizador de la app
- `appcast.xml` — feed Sparkle para macOS
- `portals.json` — directorio de portales IT-Community que consume la app
- El código fuente vive en el repo privado `mavksoft/juntas-it-community`.

[Última release](https://github.com/mavksoft/juntas-it-community-releases/releases/latest)

## Preguntas frecuentes

**¿Puedo usar la app sin que mi comunidad tenga portal?**  
La app necesita un portal IT-Community activo — lo configura el administrador de fincas de tu comunidad.

**¿Dónde está el código fuente?**  
Es software privado: este repositorio solo publica los binarios y los feeds de actualización.

## Soporte

- Web: [it-community.online](https://it-community.online)
- Email: [hola@it-community.online](mailto:hola@it-community.online)

---
<p align="center"><sub>Juntas — IT-Community · © MavkSoft / IT-Systems</sub></p>

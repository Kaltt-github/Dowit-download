<div align="center">

# 🗓️ Dowit

**Organizá tus eventos, tareas y rutinas — sin cuentas, sin Internet, sin vueltas.**

Tus datos quedan guardados y encriptados **en tu propio dispositivo**. 100% en español.

`Versión actual: 1.24.0`

<br>

[![Descargar para Windows](https://img.shields.io/badge/Descargar_para_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Descargar para Windows (portable)](https://img.shields.io/badge/Descargar_para_Windows_%28portable%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Descargar para Android](https://img.shields.io/badge/Descargar_para_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Descargar para macOS](https://img.shields.io/badge/Descargar_para_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Descargar para iPhone](https://img.shields.io/badge/Descargar_para_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Abrir en Web](https://img.shields.io/badge/Abrir_en_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Versiones Apple sin validar:** los artefactos de macOS y iPhone se compilan automáticamente en un runner macOS, pero todavía no se han probado manualmente en una Mac ni en un iPhone físicos. Considéralos experimentales y conserva una copia de tus datos.

---

## 🪟 Windows

### Instalador EXE — recomendado

1. Tocá **Descargar para Windows** y abrí `Dowit-windows-x64.exe`.
2. Si SmartScreen muestra una advertencia porque Dowit no tiene un certificado comercial, elegí **Más información → Ejecutar de todas formas**.
3. Elegí **Instalar**. No requiere permisos de administrador. Para actualizar, instalá el EXE nuevo encima; tus datos se conservan.

Esta variante registra Dowit como aplicación de Windows, agrega su desinstalador y habilita el protocolo y las acciones rápidas de la barra de tareas.

### Windows portable — ZIP

1. Tocá **Windows portable** y descargá `Dowit-windows-x64.zip`.
2. Hacé clic derecho sobre el ZIP y elegí **Extraer todo…**.
3. Abrí la carpeta extraída y ejecutá `dowit.exe`.

La edición portable no se instala ni registra el protocolo de Dowit. Para actualizarla, cerrá Dowit y extraé el ZIP nuevo en una carpeta nueva.

## 🤖 Android

1. Desde tu celular, tocá el botón **Descargar Android** de arriba.
2. Abrí el archivo descargado.
3. Si el sistema pregunta, permití **instalar apps desconocidas** para el navegador o gestor de archivos que usaste.
4. Si Google Play Protect avisa: **Más detalles → Instalar de todas formas**.

> ⚠️ Ese aviso también es normal: la app no está publicada en Play Store, pero es la misma y firmada siempre.

## 🍎 macOS

1. Tocá el botón **Descargar macOS** de arriba.
2. Abrí **`Dowit-macos.dmg`** y arrastrá Dowit a **Aplicaciones**.
3. En el primer inicio, si Gatekeeper la bloquea, abrí **Ajustes del Sistema → Privacidad y seguridad** y elegí **Abrir igualmente**.

El DMG contiene una compilación Release optimizada con firma ad hoc, pero no está notarizado ni publicado en la Mac App Store.

## 📱 iPhone

1. Descargá **`Dowit-ios.ipa`** en la PC.
2. Conectá el iPhone, activá **Modo desarrollador** y abrí tu instalador lateral, por ejemplo [MobAI](https://mobai.run/download).
3. Pedile que firme e instale el IPA con tu cuenta Apple y aceptá la confianza del desarrollador en el iPhone si aparece.

El IPA es una compilación **Release/AOT**, sin listeners ni servicio de debug. Se publica sin una firma personal para no incluir certificados ni dispositivos registrados en una descarga pública; el instalador lateral la firma para tu iPhone. Con una cuenta Apple gratuita, iOS exige renovar esa firma periódicamente.

## ✅ Qué necesitás

| | |
|---|---|
| 🪟 Windows | 10 u 11 (64 bits) · nada más |
| 🤖 Android | 6.0 o superior |
| 🍎 macOS | Una versión compatible con la edición actual de Flutter |
| 📱 iPhone | iOS 15 o superior · Modo desarrollador · instalador lateral |

Windows, Android y macOS traen todo lo necesario. iPhone requiere firmar el IPA para el dispositivo durante la instalación.

## ❓ Preguntas frecuentes

<details>
<summary><b>¿Necesito Internet?</b></summary>
Dowit funciona sin conexión. Solo necesitás Internet para descargarla y, en iPhone, para el aprovisionamiento inicial o la renovación de la firma.
</details>

<details>
<summary><b>¿Mis eventos salen de mi dispositivo?</b></summary>
Nunca. Se guardan cifrados localmente. No hay servidores, cuentas ni sincronización.
</details>

<details>
<summary><b>¿Cómo actualizo a una versión nueva?</b></summary>
Descargá la versión nueva e instalala encima: <b>tus datos se conservan</b>. En Windows, abrí el EXE nuevo; en macOS reemplazá la aplicación; en iPhone firmá e instalá el IPA nuevo con el mismo identificador.
</details>

<details>
<summary><b>¿Cómo la desinstalo?</b></summary>
Desinstalala como cualquier otra app. Si usaste el ZIP portable en Windows, borrá su carpeta; si además querés eliminar sus datos, borrá <code>Dowit</code> dentro de <code>%APPDATA%</code>.
</details>

<details>
<summary><b>¿Cómo verifico que mi descarga es la original?</b></summary>
Cada archivo publicado muestra su hash <b>SHA-256</b> en la página de la <a href="../../releases">versión</a>. En Windows, abrí una terminal en la carpeta de descarga y ejecutá:<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
Si el resultado coincide con el hash publicado, tu copia es idéntica a la original. En Android, además, el sistema rechaza cualquier Dowit que no esté firmado con la clave original: ninguna versión intervenida puede instalarse encima.
</details>

<details>
<summary><b>¿Es gratis? ¿Tiene anuncios?</b></summary>
Gratis, sin anuncios, sin compras y sin límites artificiales.
</details>

## 🛟 Si algo falla

Si un antivirus o el navegador bloquea la descarga, igual podés abrirla desde tus descargas recientes. Para cualquier otro problema, abrí un [**Issue**](../../issues) contando qué pasó.

---

<div align="center">
<sub>Hecho con Flutter · offline primero · tus datos son tuyos</sub>
<br>
<sub>Licencia <a href="LICENSE">MIT</a> · <a href="../../releases">Versiones anteriores</a></sub>
</div>

<div align="center">

# 🗓️ Dowit

**Organizá tus eventos, tareas y rutinas — sin cuentas, sin Internet, sin vueltas.**

Tus datos quedan guardados y encriptados **en tu propio dispositivo**. 100% en español.

`Versión actual: 1.7.0`

<br>

[![Descargar para Windows](https://img.shields.io/badge/⬇%20Descargar-Windows_10/11-0078D6?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Descargar para Android](https://img.shields.io/badge/⬇%20Descargar-Android-3DDC84?style=for-the-badge&logo=android&logoColor=black)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Usar online](https://img.shields.io/badge/🌐%20Usar_online-Sin_instalar-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

> 🌐 También podés probarla directo acá, sin instalar nada: **[dowit en tu navegador](https://kaltt-github.github.io/Dowit-download/)**. Los datos quedan guardados y cifrados en ese navegador (no se sincronizan con otras dispositivos) y, al no haber sistema de notificaciones en la web, los recordatorios solo avisan con la pestaña abierta. Después de la primera visita funciona incluso sin conexión.

</div>

---

## 🪟 Windows

1. Tocá el botón **Descargar Windows** de arriba.
2. Click derecho sobre el ZIP → **Extraer todo…**
3. Abrí la carpeta nueva y ejecutá **`dowit.exe`** (doble clic).

> ⚠️ Si aparece *"Windows protegió tu PC"*: tocá **Más información → Ejecutar de todas formas**. Es normal en apps que no pasan por la tienda de Microsoft.

## 🤖 Android

1. Desde tu celular, tocá el botón **Descargar Android** de arriba.
2. Abrí el archivo descargado.
3. Si el sistema pregunta, permití **instalar apps desconocidas** para el navegador o gestor de archivos que usaste.
4. Si Google Play Protect avisa: **Más detalles → Instalar de todas formas**.

> ⚠️ Ese aviso también es normal: la app no está publicada en Play Store, pero es la misma y firmada siempre.

## ✅ Qué necesitás

| | |
|---|---|
| 🪟 Windows | 10 u 11 (64 bits) · nada más |
| 🤖 Android | 6.0 o superior |

No hace falta instalar nada previo: cada versión trae todo incluido.

## ❓ Preguntas frecuentes

<details>
<summary><b>¿Necesito Internet?</b></summary>
No. Dowit funciona 100% sin conexión, siempre.
</details>

<details>
<summary><b>¿Mis eventos salen de mi dispositivo?</b></summary>
Nunca. Se guardan cifrados localmente. No hay servidores, cuentas ni sincronización.
</details>

<details>
<summary><b>¿Cómo actualizo a una versión nueva?</b></summary>
Descargá la versión nueva e instalala encima: <b>tus datos se conservan</b>. En Windows, extraé la carpeta nueva y usá ese <code>dowit.exe</code>.
</details>

<details>
<summary><b>¿Cómo la desinstalo?</b></summary>
Android: desinstalala como cualquier app. Windows: borrá la carpeta; si querés dejarla impecable, borrá también la carpeta <code>Dowit</code> dentro de <code>%APPDATA%</code> (ahí viven tus datos).
</details>

<details>
<summary><b>¿Cómo verifico que mi descarga es la original?</b></summary>
Cada archivo publicado muestra su hash <b>SHA-256</b> en la página de la <a href="../../releases">versión</a>. En Windows, abrí una terminal en la carpeta de descarga y ejecutá:<br>
<code>certutil -hashfile Dowit-windows-x64.zip SHA256</code><br>
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

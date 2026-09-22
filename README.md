<div align="center">

# 🗓️ Dowit

`Versión actual: 1.24.0`

</div>

<details>
<summary><b>Español</b></summary>

<div align="center">

**Organizá tus eventos, tareas y rutinas — sin cuentas, sin Internet, sin vueltas.**

Tus datos quedan guardados y encriptados **en tu propio dispositivo**. Al primer arranque elegís el idioma; después lo cambiás en Configuración.

<br>

[![Descargar para Windows](https://img.shields.io/badge/Descargar_para_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Descargar para Windows (portable)](https://img.shields.io/badge/Descargar_para_Windows_%28portable%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Descargar para Android](https://img.shields.io/badge/Descargar_para_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Descargar para macOS](https://img.shields.io/badge/Descargar_para_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Descargar para iPhone](https://img.shields.io/badge/Descargar_para_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Abrir en Web](https://img.shields.io/badge/Abrir_en_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Versiones Apple sin validar:** los artefactos de macOS y iPhone se compilan automáticamente en un runner macOS, pero todavía no se han probado manualmente en una Mac ni en un iPhone físicos. Considéralos experimentales y conserva una copia de tus datos.

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

<div align="center">
<sub>Hecho con Flutter · offline primero · tus datos son tuyos</sub>
<br>
<sub>Licencia <a href="LICENSE">MIT</a> · <a href="../../releases">Versiones anteriores</a></sub>
</div>

</details>

<details>
<summary><b>English</b></summary>

<div align="center">

**Organize your events, tasks and routines — no accounts, no Internet, no fuss.**

Your data stays saved and encrypted **on your own device**. Pick the language at first launch; change it later in Settings.

<br>

[![Download for Windows](https://img.shields.io/badge/Download_for_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Download for Windows (portable)](https://img.shields.io/badge/Download_for_Windows_%28portable%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Download for Android](https://img.shields.io/badge/Download_for_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Download for macOS](https://img.shields.io/badge/Download_for_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Download for iPhone](https://img.shields.io/badge/Download_for_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Open on the Web](https://img.shields.io/badge/Open_on_the_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Unverified Apple builds:** the macOS and iPhone files are compiled on a macOS runner, but they have not been tested by hand on a physical Mac or iPhone. Treat them as experimental and keep a copy of your data.

## 🪟 Windows

### EXE installer — recommended

1. Tap **Download for Windows** and open `Dowit-windows-x64.exe`.
2. If SmartScreen warns because Dowit has no commercial certificate, choose **More info → Run anyway**.
3. Choose **Install**. It does not need administrator rights. To update, install the new EXE over the old one; your data is kept.

This edition registers Dowit as a Windows app, adds its uninstaller, and enables the protocol and taskbar quick actions.

### Portable Windows — ZIP

1. Tap **Windows portable** and download `Dowit-windows-x64.zip`.
2. Right-click the ZIP and choose **Extract All…**.
3. Open the extracted folder and run `dowit.exe`.

The portable edition is not installed and does not register the Dowit protocol. To update it, close Dowit and extract the new ZIP into a new folder.

## 🤖 Android

1. On your phone, tap the **Download Android** button above.
2. Open the downloaded file.
3. If asked, allow **installing unknown apps** for the browser or file manager you used.
4. If Google Play Protect warns: **More details → Install anyway**.

> ⚠️ That warning is expected: the app is not on the Play Store, but it is the same app and always signed with the same key.

## 🍎 macOS

1. Tap the **Download macOS** button above.
2. Open **`Dowit-macos.dmg`** and drag Dowit to **Applications**.
3. On first launch, if Gatekeeper blocks it, open **System Settings → Privacy & Security** and choose **Open Anyway**.

The DMG is an optimized Release build with ad hoc signing. It is not notarized and is not on the Mac App Store.

## 📱 iPhone

1. Download **`Dowit-ios.ipa`** on your computer.
2. Connect the iPhone, turn on **Developer Mode**, and open your sideloading installer, for example [MobAI](https://mobai.run/download).
3. Have it sign and install the IPA with your Apple account, and trust the developer on the iPhone if asked.

The IPA is a **Release/AOT** build, with no debug listeners or debug service. It is published unsigned by us so a public download does not include personal certificates or device lists; the sideloading installer signs it for your iPhone. With a free Apple account, iOS requires that signature to be renewed from time to time.

## ✅ What you need

| | |
|---|---|
| 🪟 Windows | 10 or 11 (64-bit) · nothing else |
| 🤖 Android | 6.0 or later |
| 🍎 macOS | A version compatible with the current Flutter edition |
| 📱 iPhone | iOS 15 or later · Developer Mode · sideloading installer |

Windows, Android and macOS include everything you need. iPhone requires signing the IPA for that device at install time.

## ❓ Frequently asked questions

<details>
<summary><b>Do I need the Internet?</b></summary>
Dowit works offline. You only need the Internet to download it and, on iPhone, for the first provisioning or to renew the signature.
</details>

<details>
<summary><b>Do my events leave my device?</b></summary>
Never. They are stored encrypted locally. There are no servers, accounts or sync.
</details>

<details>
<summary><b>How do I update to a new version?</b></summary>
Download the new version and install it over the old one: <b>your data is kept</b>. On Windows, open the new EXE; on macOS replace the app; on iPhone sign and install the new IPA with the same identifier.
</details>

<details>
<summary><b>How do I uninstall it?</b></summary>
Uninstall it like any other app. If you used the portable ZIP on Windows, delete its folder; to remove its data as well, delete <code>Dowit</code> inside <code>%APPDATA%</code>.
</details>

<details>
<summary><b>How do I check that my download is the original?</b></summary>
Each published file shows its <b>SHA-256</b> hash on the <a href="../../releases">release</a> page. On Windows, open a terminal in the download folder and run:<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
If it matches the published hash, your copy is identical to the original. On Android, the system also rejects any Dowit not signed with the original key: a tampered build cannot be installed over it.
</details>

<details>
<summary><b>Is it free? Does it have ads?</b></summary>
Free, with no ads, no purchases and no artificial limits.
</details>

## 🛟 If something goes wrong

If an antivirus or the browser blocks the download, you can still open it from your recent downloads. For anything else, open an [**Issue**](../../issues) and say what happened.

<div align="center">
<sub>Made with Flutter · offline first · your data stays yours</sub>
<br>
<sub><a href="LICENSE">MIT</a> license · <a href="../../releases">Previous releases</a></sub>
</div>

</details>

<details>
<summary><b>Français</b></summary>

<div align="center">

**Organisez vos événements, tâches et routines — sans comptes, sans Internet, sans détours.**

Vos données restent enregistrées et chiffrées **sur votre appareil**. Choisissez la langue au premier lancement ; vous pourrez la changer dans Configuration.

<br>

[![Telecharger pour Windows](https://img.shields.io/badge/Telecharger_pour_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Telecharger pour Windows (portable)](https://img.shields.io/badge/Telecharger_pour_Windows_%28portable%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Telecharger pour Android](https://img.shields.io/badge/Telecharger_pour_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Telecharger pour macOS](https://img.shields.io/badge/Telecharger_pour_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Telecharger pour iPhone](https://img.shields.io/badge/Telecharger_pour_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Ouvrir sur le Web](https://img.shields.io/badge/Ouvrir_sur_le_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Versions Apple non validées :** les fichiers macOS et iPhone sont compilés sur un runner macOS, mais n’ont pas encore été testés à la main sur un Mac ni un iPhone physiques. Considérez-les comme expérimentaux et gardez une copie de vos données.

## 🪟 Windows

### Installateur EXE — recommandé

1. Appuyez sur **Telecharger pour Windows** et ouvrez `Dowit-windows-x64.exe`.
2. Si SmartScreen affiche un avertissement parce que Dowit n’a pas de certificat commercial, choisissez **Plus d’informations → Exécuter quand même**.
3. Choisissez **Installer**. Aucun droit administrateur n’est requis. Pour mettre à jour, installez le nouvel EXE par-dessus ; vos données sont conservées.

Cette édition enregistre Dowit comme application Windows, ajoute son désinstalleur et active le protocole et les actions rapides de la barre des tâches.

### Windows portable — ZIP

1. Appuyez sur **Windows portable** et téléchargez `Dowit-windows-x64.zip`.
2. Clic droit sur le ZIP, puis **Extraire tout…**.
3. Ouvrez le dossier extrait et lancez `dowit.exe`.

L’édition portable ne s’installe pas et n’enregistre pas le protocole de Dowit. Pour la mettre à jour, fermez Dowit et extrayez le nouveau ZIP dans un nouveau dossier.

## 🤖 Android

1. Sur votre téléphone, appuyez sur le bouton **Telecharger Android** ci-dessus.
2. Ouvrez le fichier téléchargé.
3. Si le système le demande, autorisez **l’installation d’apps inconnues** pour le navigateur ou le gestionnaire de fichiers utilisé.
4. Si Google Play Protect avertit : **Plus de détails → Installer quand même**.

> ⚠️ Cet avertissement est normal : l’app n’est pas sur le Play Store, mais c’est la même, toujours signée avec la même clé.

## 🍎 macOS

1. Appuyez sur le bouton **Telecharger macOS** ci-dessus.
2. Ouvrez **`Dowit-macos.dmg`** et glissez Dowit vers **Applications**.
3. Au premier lancement, si Gatekeeper la bloque, ouvrez **Réglages Système → Confidentialité et sécurité** et choisissez **Ouvrir quand même**.

Le DMG est une compilation Release optimisée avec signature ad hoc. Il n’est pas notarié et n’est pas sur le Mac App Store.

## 📱 iPhone

1. Téléchargez **`Dowit-ios.ipa`** sur l’ordinateur.
2. Branchez l’iPhone, activez le **Mode développeur** et ouvrez votre installateur latéral, par exemple [MobAI](https://mobai.run/download).
3. Faites signer et installer l’IPA avec votre compte Apple, et acceptez la confiance du développeur sur l’iPhone si elle apparaît.

L’IPA est une compilation **Release/AOT**, sans listeners ni service de debug. Elle est publiée sans signature personnelle pour ne pas inclure de certificats ni d'appareils dans un téléchargement public ; l’installateur latéral la signe pour votre iPhone. Avec un compte Apple gratuit, iOS exige de renouveler cette signature périodiquement.

## ✅ Ce qu’il vous faut

| | |
|---|---|
| 🪟 Windows | 10 ou 11 (64 bits) · rien d’autre |
| 🤖 Android | 6.0 ou plus |
| 🍎 macOS | Une version compatible avec l’édition actuelle de Flutter |
| 📱 iPhone | iOS 15 ou plus · Mode développeur · installateur latéral |

Windows, Android et macOS fournissent tout le nécessaire. iPhone exige de signer l’IPA pour l’appareil lors de l’installation.

## ❓ Questions fréquentes

<details>
<summary><b>Ai-je besoin d’Internet ?</b></summary>
Dowit fonctionne hors ligne. Internet n’est nécessaire que pour le télécharger et, sur iPhone, pour le premier provisionnement ou le renouvellement de la signature.
</details>

<details>
<summary><b>Mes événements quittent-ils mon appareil ?</b></summary>
Jamais. Ils sont enregistrés chiffrés localement. Pas de serveurs, de comptes ni de synchronisation.
</details>

<details>
<summary><b>Comment mettre à jour ?</b></summary>
Téléchargez la nouvelle version et installez-la par-dessus : <b>vos données sont conservées</b>. Sur Windows, ouvrez le nouvel EXE ; sur macOS, remplacez l’application ; sur iPhone, signez et installez le nouvel IPA avec le même identifiant.
</details>

<details>
<summary><b>Comment la désinstaller ?</b></summary>
Désinstallez-la comme n’importe quelle app. Si vous avez utilisé le ZIP portable sous Windows, supprimez son dossier ; pour supprimer aussi ses données, supprimez <code>Dowit</code> dans <code>%APPDATA%</code>.
</details>

<details>
<summary><b>Comment vérifier que le fichier est l’original ?</b></summary>
Chaque fichier publié affiche son hash <b>SHA-256</b> sur la page de la <a href="../../releases">version</a>. Sous Windows, ouvrez un terminal dans le dossier de téléchargement et exécutez :<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
S’il correspond au hash publié, votre copie est identique à l’originale. Sous Android, le système refuse aussi tout Dowit qui n’est pas signé avec la clé d’origine : une version altérée ne peut pas s’installer par-dessus.
</details>

<details>
<summary><b>Est-ce gratuit ? Y a-t-il des publicités ?</b></summary>
Gratuit, sans publicités, sans achats et sans limites artificielles.
</details>

## 🛟 En cas de problème

Si un antivirus ou le navigateur bloque le téléchargement, vous pouvez tout de même l’ouvrir depuis vos téléchargements récents. Pour tout autre problème, ouvrez une [**Issue**](../../issues) en expliquant ce qui s’est passé.

<div align="center">
<sub>Fait avec Flutter · hors ligne d’abord · vos données restent les vôtres</sub>
<br>
<sub>Licence <a href="LICENSE">MIT</a> · <a href="../../releases">Versions précédentes</a></sub>
</div>

</details>

<details>
<summary><b>Italiano</b></summary>

<div align="center">

**Organizza eventi, attività e routine — senza account, senza Internet, senza giri.**

I tuoi dati restano salvati e crittografati **sul tuo dispositivo**. Scegli la lingua al primo avvio; poi la cambi in Configurazione.

<br>

[![Scarica per Windows](https://img.shields.io/badge/Scarica_per_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Scarica per Windows (portable)](https://img.shields.io/badge/Scarica_per_Windows_%28portable%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Scarica per Android](https://img.shields.io/badge/Scarica_per_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Scarica per macOS](https://img.shields.io/badge/Scarica_per_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Scarica per iPhone](https://img.shields.io/badge/Scarica_per_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Apri sul Web](https://img.shields.io/badge/Apri_sul_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Versioni Apple non verificate:** i file per macOS e iPhone vengono compilati su un runner macOS, ma non sono ancora stati provati a mano su un Mac o un iPhone fisici. Considerali sperimentali e conserva una copia dei tuoi dati.

## 🪟 Windows

### Installer EXE — consigliato

1. Tocca **Scarica per Windows** e apri `Dowit-windows-x64.exe`.
2. Se SmartScreen avvisa perché Dowit non ha un certificato commerciale, scegli **Ulteriori informazioni → Esegui comunque**.
3. Scegli **Installa**. Non servono diritti di amministratore. Per aggiornare, installa il nuovo EXE sopra il precedente; i tuoi dati restano.

Questa edizione registra Dowit come app di Windows, aggiunge il disinstallatore e attiva il protocollo e le azioni rapide della barra delle applicazioni.

### Windows portable — ZIP

1. Tocca **Windows portable** e scarica `Dowit-windows-x64.zip`.
2. Clic destro sullo ZIP e **Estrai tutto…**.
3. Apri la cartella estratta ed esegui `dowit.exe`.

L’edizione portable non si installa e non registra il protocollo di Dowit. Per aggiornarla, chiudi Dowit ed estrai il nuovo ZIP in una cartella nuova.

## 🤖 Android

1. Dal telefono, tocca il pulsante **Scarica Android** qui sopra.
2. Apri il file scaricato.
3. Se il sistema lo chiede, consenti **l’installazione di app sconosciute** per il browser o il gestore file usato.
4. Se Google Play Protect avvisa: **Altri dettagli → Installa comunque**.

> ⚠️ L’avviso è normale: l’app non è sul Play Store, ma è la stessa e sempre firmata con la stessa chiave.

## 🍎 macOS

1. Tocca il pulsante **Scarica macOS** qui sopra.
2. Apri **`Dowit-macos.dmg`** e trascina Dowit in **Applicazioni**.
3. Al primo avvio, se Gatekeeper la blocca, apri **Impostazioni di Sistema → Privacy e sicurezza** e scegli **Apri comunque**.

Il DMG è una compilazione Release ottimizzata con firma ad hoc. Non è notarizzato e non è sul Mac App Store.

## 📱 iPhone

1. Scarica **`Dowit-ios.ipa`** sul computer.
2. Collega l’iPhone, attiva la **Modalità sviluppatore** e apri il tuo installer laterale, ad esempio [MobAI](https://mobai.run/download).
3. Faglielo firmare e installare con il tuo account Apple e accetta la fiducia dello sviluppatore sull’iPhone se compare.

L’IPA è una compilazione **Release/AOT**, senza listener né servizio di debug. Viene pubblicata senza una firma personale per non includere certificati o dispositivi in un download pubblico; l’installer laterale la firma per il tuo iPhone. Con un account Apple gratuito, iOS chiede di rinnovare quella firma periodicamente.

## ✅ Cosa ti serve

| | |
|---|---|
| 🪟 Windows | 10 o 11 (64 bit) · nient’altro |
| 🤖 Android | 6.0 o successivo |
| 🍎 macOS | Una versione compatibile con l’edizione attuale di Flutter |
| 📱 iPhone | iOS 15 o successivo · Modalità sviluppatore · installer laterale |

Windows, Android e macOS includono tutto il necessario. iPhone richiede di firmare l’IPA per il dispositivo in installazione.

## ❓ Domande frequenti

<details>
<summary><b>Serve Internet?</b></summary>
Dowit funziona offline. Internet serve solo per scaricarla e, su iPhone, per il primo provisioning o per rinnovare la firma.
</details>

<details>
<summary><b>I miei eventi escono dal dispositivo?</b></summary>
Mai. Sono salvati cifrati in locale. Non ci sono server, account né sincronizzazione.
</details>

<details>
<summary><b>Come aggiorno a una versione nuova?</b></summary>
Scarica la versione nuova e installala sopra: <b>i tuoi dati restano</b>. Su Windows apri il nuovo EXE; su macOS sostituisci l’app; su iPhone firma e installa il nuovo IPA con lo stesso identificatore.
</details>

<details>
<summary><b>Come la disinstallo?</b></summary>
Disinstallala come qualsiasi altra app. Se hai usato lo ZIP portable su Windows, elimina la sua cartella; per cancellare anche i dati, elimina <code>Dowit</code> dentro <code>%APPDATA%</code>.
</details>

<details>
<summary><b>Come verifico che il file sia l’originale?</b></summary>
Ogni file pubblicato mostra il suo hash <b>SHA-256</b> nella pagina della <a href="../../releases">versione</a>. Su Windows, apri un terminale nella cartella di download ed esegui:<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
Se coincide con l’hash pubblicato, la copia è identica all’originale. Su Android il sistema rifiuta anche qualsiasi Dowit non firmato con la chiave originale: una versione alterata non può installarsi sopra.
</details>

<details>
<summary><b>È gratis? Ci sono pubblicità?</b></summary>
Gratis, senza pubblicità, senza acquisti e senza limiti artificiali.
</details>

## 🛟 Se qualcosa non va

Se un antivirus o il browser blocca il download, puoi comunque aprirlo dai download recenti. Per qualsiasi altro problema, apri una [**Issue**](../../issues) e racconta cosa è successo.

<div align="center">
<sub>Fatto con Flutter · prima di tutto offline · i tuoi dati restano tuoi</sub>
<br>
<sub>Licenza <a href="LICENSE">MIT</a> · <a href="../../releases">Versioni precedenti</a></sub>
</div>

</details>

<details>
<summary><b>Português</b></summary>

<div align="center">

**Organize seus eventos, tarefas e rotinas — sem contas, sem Internet, sem rodeios.**

Seus dados ficam salvos e criptografados **no seu próprio dispositivo**. Escolha o idioma na primeira abertura; depois mude em Configuração.

<br>

[![Baixar para Windows](https://img.shields.io/badge/Baixar_para_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Baixar para Windows (portatil)](https://img.shields.io/badge/Baixar_para_Windows_%28portatil%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Baixar para Android](https://img.shields.io/badge/Baixar_para_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Baixar para macOS](https://img.shields.io/badge/Baixar_para_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Baixar para iPhone](https://img.shields.io/badge/Baixar_para_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Abrir na Web](https://img.shields.io/badge/Abrir_na_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Versões Apple sem validação:** os arquivos de macOS e iPhone são compilados num runner macOS, mas ainda não foram testados à mão num Mac nem num iPhone físicos. Trate-os como experimentais e guarde uma cópia dos seus dados.

## 🪟 Windows

### Instalador EXE — recomendado

1. Toque em **Baixar para Windows** e abra `Dowit-windows-x64.exe`.
2. Se o SmartScreen avisar porque o Dowit não tem certificado comercial, escolha **Mais informações → Executar mesmo assim**.
3. Escolha **Instalar**. Não precisa de permissões de administrador. Para atualizar, instale o EXE novo por cima; os seus dados conservam-se.

Esta edição regista o Dowit como aplicação do Windows, adiciona o desinstalador e ativa o protocolo e as ações rápidas da barra de tarefas.

### Windows portátil — ZIP

1. Toque em **Windows portátil** e descarregue `Dowit-windows-x64.zip`.
2. Clique com o botão direito no ZIP e escolha **Extrair tudo…**.
3. Abra a pasta extraída e execute `dowit.exe`.

A edição portátil não se instala nem regista o protocolo do Dowit. Para atualizá-la, feche o Dowit e extraia o ZIP novo numa pasta nova.

## 🤖 Android

1. No telemóvel, toque no botão **Baixar Android** acima.
2. Abra o ficheiro descarregado.
3. Se o sistema perguntar, permita **instalar aplicações desconhecidas** no navegador ou no gestor de ficheiros que usou.
4. Se o Google Play Protect avisar: **Mais detalhes → Instalar mesmo assim**.

> ⚠️ Esse aviso também é normal: a app não está na Play Store, mas é a mesma e está sempre assinada com a mesma chave.

## 🍎 macOS

1. Toque no botão **Baixar macOS** acima.
2. Abra **`Dowit-macos.dmg`** e arraste o Dowit para **Aplicações**.
3. Na primeira abertura, se o Gatekeeper a bloquear, abra **Definições do Sistema → Privacidade e segurança** e escolha **Abrir mesmo assim**.

O DMG contém uma compilação Release otimizada com assinatura ad hoc. Não está notarizado nem publicado na Mac App Store.

## 📱 iPhone

1. Descarregue **`Dowit-ios.ipa`** no computador.
2. Ligue o iPhone, ative o **Modo de programador** e abra o seu instalador lateral, por exemplo [MobAI](https://mobai.run/download).
3. Peça-lhe que assine e instale o IPA com a sua conta Apple e aceite a confiança do programador no iPhone se aparecer.

O IPA é uma compilação **Release/AOT**, sem listeners nem serviço de debug. Publica-se sem uma assinatura pessoal para não incluir certificados nem dispositivos numa descarga pública; o instalador lateral assina-o para o seu iPhone. Com uma conta Apple gratuita, o iOS exige renovar essa assinatura periodicamente.

## ✅ O que precisa

| | |
|---|---|
| 🪟 Windows | 10 ou 11 (64 bits) · nada mais |
| 🤖 Android | 6.0 ou superior |
| 🍎 macOS | Uma versão compatível com a edição atual do Flutter |
| 📱 iPhone | iOS 15 ou superior · Modo de programador · instalador lateral |

Windows, Android e macOS trazem tudo o necessário. O iPhone exige assinar o IPA para o dispositivo na instalação.

## ❓ Perguntas frequentes

<details>
<summary><b>Preciso de Internet?</b></summary>
O Dowit funciona sem ligação. Só precisa de Internet para o descarregar e, no iPhone, para o provisionamento inicial ou a renovação da assinatura.
</details>

<details>
<summary><b>Os meus eventos saem do dispositivo?</b></summary>
Nunca. Guardam-se cifrados localmente. Não há servidores, contas nem sincronização.
</details>

<details>
<summary><b>Como atualizo para uma versão nova?</b></summary>
Descarregue a versão nova e instale-a por cima: <b>os seus dados conservam-se</b>. No Windows, abra o EXE novo; no macOS substitua a aplicação; no iPhone assine e instale o IPA novo com o mesmo identificador.
</details>

<details>
<summary><b>Como a desinstalo?</b></summary>
Desinstale-a como qualquer outra app. Se usou o ZIP portátil no Windows, apague a pasta; para apagar também os dados, apague <code>Dowit</code> dentro de <code>%APPDATA%</code>.
</details>

<details>
<summary><b>Como verifico que a descarga é a original?</b></summary>
Cada ficheiro publicado mostra o seu hash <b>SHA-256</b> na página da <a href="../../releases">versão</a>. No Windows, abra um terminal na pasta de descarga e execute:<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
Se coincidir com o hash publicado, a cópia é idêntica à original. No Android, o sistema também rejeita qualquer Dowit que não esteja assinado com a chave original: uma versão alterada não pode instalar-se por cima.
</details>

<details>
<summary><b>É grátis? Tem anúncios?</b></summary>
Grátis, sem anúncios, sem compras e sem limites artificiais.
</details>

## 🛟 Se algo falhar

Se um antivírus ou o navegador bloquear a descarga, ainda a pode abrir nas descargas recentes. Para qualquer outro problema, abra uma [**Issue**](../../issues) a contar o que aconteceu.

<div align="center">
<sub>Feito com Flutter · offline primeiro · os seus dados são seus</sub>
<br>
<sub>Licença <a href="LICENSE">MIT</a> · <a href="../../releases">Versões anteriores</a></sub>
</div>

</details>

<details>
<summary><b>Deutsch</b></summary>

<div align="center">

**Organisiere deine Termine, Aufgaben und Routinen — ohne Konten, ohne Internet, ohne Umwege.**

Deine Daten bleiben gespeichert und verschlüsselt **auf deinem Gerät**. Die Sprache wählst du beim ersten Start; später änderst du sie in den Einstellungen.

<br>

[![Fur Windows herunterladen](https://img.shields.io/badge/Fur_Windows_herunterladen-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Fur Windows herunterladen (portabel)](https://img.shields.io/badge/Fur_Windows_herunterladen_%28portabel%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Fur Android herunterladen](https://img.shields.io/badge/Fur_Android_herunterladen-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Fur macOS herunterladen](https://img.shields.io/badge/Fur_macOS_herunterladen-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Fur iPhone herunterladen](https://img.shields.io/badge/Fur_iPhone_herunterladen-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Im Web offnen](https://img.shields.io/badge/Im_Web_offnen-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Ungeprüfte Apple-Versionen:** die macOS- und iPhone-Dateien werden auf einem macOS-Runner gebaut, wurden aber noch nicht von Hand auf einem echten Mac oder iPhone getestet. Behandle sie als experimentell und behalte eine Kopie deiner Daten.

## 🪟 Windows

### EXE-Installer — empfohlen

1. Tippe auf **Fur Windows herunterladen** und öffne `Dowit-windows-x64.exe`.
2. Wenn SmartScreen warnt, weil Dowit kein kommerzielles Zertifikat hat, wähle **Weitere Informationen → Trotzdem ausführen**.
3. Wähle **Installieren**. Es sind keine Administratorrechte nötig. Zum Aktualisieren installierst du die neue EXE darüber; deine Daten bleiben erhalten.

Diese Variante trägt Dowit als Windows-App ein, fügt die Deinstallation hinzu und aktiviert das Protokoll und die Schnellaktionen der Taskleiste.

### Portables Windows — ZIP

1. Tippe auf **Windows portable** und lade `Dowit-windows-x64.zip` herunter.
2. Rechtsklick auf die ZIP-Datei und **Alle extrahieren…**.
3. Öffne den entpackten Ordner und starte `dowit.exe`.

Die portable Ausgabe wird nicht installiert und registriert das Dowit-Protokoll nicht. Zum Aktualisieren Dowit schließen und die neue ZIP-Datei in einen neuen Ordner entpacken.

## 🤖 Android

1. Tippe auf dem Handy oben auf **Fur Android herunterladen**.
2. Öffne die heruntergeladene Datei.
3. Falls gefragt, erlaube **unbekannte Apps installieren** für den Browser oder Dateimanager.
4. Wenn Google Play Protect warnt: **Weitere Details → Trotzdem installieren**.

> ⚠️ Die Warnung ist normal: die App ist nicht im Play Store, aber es ist dieselbe App und immer mit demselben Schlüssel signiert.

## 🍎 macOS

1. Tippe oben auf **Fur macOS herunterladen**.
2. Öffne **`Dowit-macos.dmg`** und ziehe Dowit nach **Programme**.
3. Beim ersten Start, wenn Gatekeeper blockiert, öffne **Systemeinstellungen → Datenschutz & Sicherheit** und wähle **Trotzdem öffnen**.

Die DMG ist ein optimierter Release-Build mit Ad-hoc-Signatur. Sie ist nicht notarisiert und nicht im Mac App Store.

## 📱 iPhone

1. Lade **`Dowit-ios.ipa`** am Computer herunter.
2. Verbinde das iPhone, aktiviere den **Entwicklermodus** und öffne deinen Sideloading-Installer, zum Beispiel [MobAI](https://mobai.run/download).
3. Lass die IPA mit deinem Apple-Account signieren und installieren und vertraue dem Entwickler auf dem iPhone, falls danach gefragt wird.

Die IPA ist ein **Release/AOT**-Build ohne Debug-Listener oder Debug-Dienst. Sie wird ohne persönliche Signatur veröffentlicht, damit ein öffentlicher Download keine Zertifikate oder Gerätelisten enthält; der Sideloading-Installer signiert sie für dein iPhone. Mit einem kostenlosen Apple-Account verlangt iOS, diese Signatur regelmäßig zu erneuern.

## ✅ Was du brauchst

| | |
|---|---|
| 🪟 Windows | 10 oder 11 (64-Bit) · sonst nichts |
| 🤖 Android | 6.0 oder neuer |
| 🍎 macOS | Eine Version, die zur aktuellen Flutter-Ausgabe passt |
| 📱 iPhone | iOS 15 oder neuer · Entwicklermodus · Sideloading-Installer |

Windows, Android und macOS bringen alles Nötige mit. Beim iPhone muss die IPA bei der Installation für das Gerät signiert werden.

## ❓ Häufige Fragen

<details>
<summary><b>Brauche ich Internet?</b></summary>
Dowit funktioniert offline. Internet brauchst du nur zum Herunterladen und auf dem iPhone für die erste Bereitstellung oder die Erneuerung der Signatur.
</details>

<details>
<summary><b>Verlassen meine Termine das Gerät?</b></summary>
Nie. Sie werden lokal verschlüsselt gespeichert. Es gibt keine Server, Konten oder Synchronisierung.
</details>

<details>
<summary><b>Wie aktualisiere ich?</b></summary>
Lade die neue Version herunter und installiere sie darüber: <b>deine Daten bleiben erhalten</b>. Unter Windows die neue EXE öffnen; unter macOS die App ersetzen; auf dem iPhone die neue IPA mit derselben Kennung signieren und installieren.
</details>

<details>
<summary><b>Wie deinstalliere ich sie?</b></summary>
Deinstalliere sie wie jede andere App. Wenn du die portable ZIP unter Windows genutzt hast, lösche den Ordner; um auch die Daten zu löschen, lösche <code>Dowit</code> in <code>%APPDATA%</code>.
</details>

<details>
<summary><b>Wie prüfe ich, dass der Download original ist?</b></summary>
Jede veröffentlichte Datei zeigt ihren <b>SHA-256</b>-Hash auf der <a href="../../releases">Versionsseite</a>. Unter Windows öffne ein Terminal im Download-Ordner und führe aus:<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
Stimmt er mit dem veröffentlichten Hash überein, ist deine Kopie identisch mit dem Original. Unter Android lehnt das System außerdem jedes Dowit ab, das nicht mit dem Originalschlüssel signiert ist: eine veränderte Version lässt sich nicht darüber installieren.
</details>

<details>
<summary><b>Ist sie kostenlos? Gibt es Werbung?</b></summary>
Kostenlos, ohne Werbung, ohne Käufe und ohne künstliche Grenzen.
</details>

## 🛟 Wenn etwas schiefgeht

Wenn ein Antivirus oder der Browser den Download blockiert, kannst du ihn trotzdem über die letzten Downloads öffnen. Für alles andere öffne ein [**Issue**](../../issues) und beschreibe, was passiert ist.

<div align="center">
<sub>Gemacht mit Flutter · zuerst offline · deine Daten bleiben deine</sub>
<br>
<sub><a href="LICENSE">MIT</a>-Lizenz · <a href="../../releases">Frühere Versionen</a></sub>
</div>

</details>

<details>
<summary><b>Català</b></summary>

<div align="center">

**Organitza els teus esdeveniments, tasques i rutines — sense comptes, sense Internet, sense voltes.**

Les teves dades queden desades i encriptades **al teu propi dispositiu**. A la primera arrencada tries l'idioma; després el canvies a Configuració.

<br>

[![Descarrega per a Windows](https://img.shields.io/badge/Descarrega_per_a_Windows-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.exe)

[![Descarrega per a Windows (portable)](https://img.shields.io/badge/Descarrega_per_a_Windows_%28portable%29-2563EB?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDMuNSAxMC41IDIuM3Y4LjJIMnptOS41LTEuM0wyMiAuN3Y5LjhIMTEuNXpNMiAxMS41aDguNXY4LjJMMiAxOC41em05LjUgMEgyMnY5LjhsLTEwLjUtMS41eiIvPjwvc3ZnPg%3D%3D)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-windows-x64.zip)

[![Descarrega per a Android](https://img.shields.io/badge/Descarrega_per_a_Android-2563EB?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-android.apk)

[![Descarrega per a macOS](https://img.shields.io/badge/Descarrega_per_a_macOS-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-macos.dmg)

[![Descarrega per a iPhone](https://img.shields.io/badge/Descarrega_per_a_iPhone-2563EB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Kaltt-github/Dowit-download/releases/latest/download/Dowit-ios.ipa)

[![Obre al Web](https://img.shields.io/badge/Obre_al_Web-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kaltt-github.github.io/Dowit-download/)

</div>

> ⚠️ **Versions Apple sense validar:** els artefactes de macOS i iPhone es compilen en un runner macOS, però encara no s'han provat a mà en un Mac ni en un iPhone físics. Considera'ls experimentals i conserva una còpia de les teves dades.

## 🪟 Windows

### Instal·lador EXE — recomanat

1. Toca **Descarrega per a Windows** i obre `Dowit-windows-x64.exe`.
2. Si SmartScreen mostra un avís perquè Dowit no té un certificat comercial, tria **Més informació → Executa de totes maneres**.
3. Tria **Instal·la**. No calen permisos d'administrador. Per actualitzar, instal·la l'EXE nou a sobre; les teves dades es conserven.

Aquesta variant registra Dowit com a aplicació de Windows, afegeix el desinstal·lador i activa el protocol i les accions ràpides de la barra de tasques.

### Windows portable — ZIP

1. Toca **Windows portable** i descarrega `Dowit-windows-x64.zip`.
2. Clic dret sobre el ZIP i **Extreu-ho tot…**.
3. Obre la carpeta extreta i executa `dowit.exe`.

L'edició portable no s'instal·la ni registra el protocol de Dowit. Per actualitzar-la, tanca Dowit i extreu el ZIP nou en una carpeta nova.

## 🤖 Android

1. Des del mòbil, toca el botó **Descarrega Android** de dalt.
2. Obre el fitxer descarregat.
3. Si el sistema ho demana, permet **instal·lar apps desconegudes** per al navegador o el gestor de fitxers que has fet servir.
4. Si Google Play Protect avisa: **Més detalls → Instal·la de totes maneres**.

> ⚠️ Aquest avís també és normal: l'app no és a Play Store, però és la mateixa i sempre va signada amb la mateixa clau.

## 🍎 macOS

1. Toca el botó **Descarrega macOS** de dalt.
2. Obre **`Dowit-macos.dmg`** i arrossega Dowit a **Aplicacions**.
3. A la primera obertura, si Gatekeeper la bloqueja, obre **Configuració del Sistema → Privadesa i seguretat** i tria **Obre igualment**.

El DMG conté una compilació Release optimitzada amb signatura ad hoc. No està notariat ni publicat a la Mac App Store.

## 📱 iPhone

1. Descarrega **`Dowit-ios.ipa`** a l'ordinador.
2. Connecta l'iPhone, activa el **Mode desenvolupador** i obre el teu instal·lador lateral, per exemple [MobAI](https://mobai.run/download).
3. Fes que signi i instal·li l'IPA amb el teu compte Apple i accepta la confiança del desenvolupador a l'iPhone si apareix.

L'IPA és una compilació **Release/AOT**, sense listeners ni servei de debug. Es publica sense una signatura personal per no incloure certificats ni dispositius en una descàrrega pública; l'instal·lador lateral la signa per al teu iPhone. Amb un compte Apple gratuït, iOS exigeix renovar aquesta signatura periòdicament.

## ✅ Què et cal

| | |
|---|---|
| 🪟 Windows | 10 o 11 (64 bits) · res més |
| 🤖 Android | 6.0 o superior |
| 🍎 macOS | Una versió compatible amb l'edició actual de Flutter |
| 📱 iPhone | iOS 15 o superior · Mode desenvolupador · instal·lador lateral |

Windows, Android i macOS porten tot el necessari. L'iPhone exigeix signar l'IPA per al dispositiu durant la instal·lació.

## ❓ Preguntes freqüents

<details>
<summary><b>Necessito Internet?</b></summary>
Dowit funciona sense connexió. Només cal Internet per descarregar-la i, a l'iPhone, per al provisionament inicial o la renovació de la signatura.
</details>

<details>
<summary><b>Els meus esdeveniments surten del dispositiu?</b></summary>
Mai. Es desen xifrats localment. No hi ha servidors, comptes ni sincronització.
</details>

<details>
<summary><b>Com actualitzo a una versió nova?</b></summary>
Descarrega la versió nova i instal·la-la a sobre: <b>les teves dades es conserven</b>. A Windows, obre l'EXE nou; a macOS substitueix l'aplicació; a l'iPhone signa i instal·la l'IPA nou amb el mateix identificador.
</details>

<details>
<summary><b>Com la desinstal·lo?</b></summary>
Desinstal·la-la com qualsevol altra app. Si has fet servir el ZIP portable a Windows, esborra'n la carpeta; si també vols eliminar-ne les dades, esborra <code>Dowit</code> dins de <code>%APPDATA%</code>.
</details>

<details>
<summary><b>Com verifico que la descàrrega és l'original?</b></summary>
Cada fitxer publicat mostra el seu hash <b>SHA-256</b> a la pàgina de la <a href="../../releases">versió</a>. A Windows, obre un terminal a la carpeta de descàrrega i executa:<br>
<code>certutil -hashfile Dowit-windows-x64.exe SHA256</code><br>
Si coincideix amb el hash publicat, la còpia és idèntica a l'original. A Android, el sistema també rebutja qualsevol Dowit que no estigui signat amb la clau original: cap versió alterada no es pot instal·lar a sobre.
</details>

<details>
<summary><b>És de franc? Té anuncis?</b></summary>
De franc, sense anuncis, sense compres i sense límits artificials.
</details>

## 🛟 Si alguna cosa falla

Si un antivirus o el navegador bloqueja la descàrrega, igual la pots obrir des de les descàrregues recents. Per a qualsevol altre problema, obre una [**Issue**](../../issues) explicant què ha passat.

<div align="center">
<sub>Fet amb Flutter · offline primer · les teves dades són teves</sub>
<br>
<sub>Llicència <a href="LICENSE">MIT</a> · <a href="../../releases">Versions anteriors</a></sub>
</div>

</details>

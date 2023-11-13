# `🐢𝖈𝖍𝖆𝖗𝖑𝖎𝖊-𝖇𝖔𝖙🐢`

<a href="https://www.facebook.com/charlie.rios.71216/">
<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">
</a>

</a>
<a href="https://instagram.com/maquinadefuego_gg">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
  
#### DISPONIBLE EN:
> - [x] TERMUX, REPLIT, WINDOWS, ZIPPONODES, BOXMINE-HOST


[`👾 App Termux`](https://f-droid.org/es/packages/com.termux/)
### 🍂 INSTALACIÓN AUTOMÁTICA 🍂
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget && wget -O - https://raw.githubusercontent.com/CHARLIEPPP/Charlie-Bot/master/gatalite.sh | bash
```

### 🥀 INSTALACIÓN MANUAL - TERMUX 🥀
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
git clone https://CHARLIEPPP/Charlie-Bot 
cd Charlie-Bot
yarn install
npm install
npm start
```

### 🍁 TERMUX 24/7 🍁 
> Comandos para realizar una ejecución 24/7
- INICIAR
> Use estos comandos dentro de la carpeta GataBotLite-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
```
- DETENER PM2
> Detener todos los procesos del bot
```bash
pm2 stop all && pm2 unstartup
```
- REANUDAR 
> Reanudar los procesos, usar dentro de la carpeta GataBotLite-MD 
```bash
pm2 start index.js 
```
- VISUALIZAR EL PROCESO
> Usar dentro de la carpeta GataBotLite-MD para ver en tiempo real
```bash
pm2 logs 
```
- ELIMINAR PROCESOS PM2
> Eliminar todos los procesos del bot. Para volver a usar PM2 debe volver a usar los comandos de INICIAR
```bash
pm2 delete all
```
> **Note** Demanda consumo de RAM y CPU, el resultado mejora mientras las especificaciones del dispositivo sean moderadas

### 🌹 INSTALACIÓN EN REPLIT 🌹
<a target="_blank" href="https://replit.com/github/CHARLIEPPP/Charlie-Bot"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a>
> **Notita** Agregue estos comandos en Shell para empezar la instalación automática por Replit:
```bash
npm install -g ffmpeg imagemagick git yarn && npm i && node --no-warnings index.js
```
## 🗡️ INSTALACIÓN PARA WINDOWS/VPS/RDP 🗡️

* Descargar e instala Git [`Aquí`](https://git-scm.com/downloads)
* Descargar e instala NodeJS [`Aquí`](https://nodejs.org/en/download)
* Descargar e instala FFmpeg [`Aquí`](https://ffmpeg.org/download.html) (**No olvide agregar FFmpeg a la variable de entorno PATH**)
* Descargar e instala ImageMagick [`Aquí`](https://imagemagick.org/script/download.php)
```bash
git clone https://github.com/CHARLIEPPP/Charlie-Bot
cd Charlie-Bot
npm install -g yarn
yarn
npm install 
npm start
```
### Instalación de FFmpeg para Windows 
* Descarga la siguiente versión de FFmpeg [`Aquí`](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z).
* Extraer FFmpeg con [`7-Zip`](https://www.7-zip.org/download.html)
* Cambie el nombre de la carpeta extraída a `FFmpeg`.
* Mover archivos a `C:\` path.
* Agregar la ruta ejemplo: `C:\ffmpeg\bin` al entorno de variable
* Ejecute el símbolo del sistema como administrador.
* Ejecute el siguiente comando:
```cmd
setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Si tiene éxito, le dará un mensaje como: `SUCCESS: specified value was saved`.
* Ahora que tiene FFmpeg instalado, verifique que funcionó ejecutando este comando para ver la versión:
```cmd
> ffmpeg -version
```
### Error en usar yarn en PowerShell
* Si usa la consola PowerShell y recibe este mensaje `No se puede cargar el archivo yarn.ps1 o yarn porque la ejecución de scripts está deshabilitada en este sistema.` al intentar usar `yarn` dentro de la carpeta del Bot puede usar estos comandos para cambiar la Política de ejecución de PowerShell en su sistema:
> Debe de ejecutar la consola como Administrador
```cmd
Get-ExecutionPolicy
Set-ExecutionPolicy RemoteSigned
```
> Aparecerá un mensaje de advertencia preguntando si deseas cambiar la Política de ejecución. Confirma con "Y" y presiona Enter. Luego ya puede volver a ejecutar el comando `yarn`

### 💠 [`IDIOMAS DISPONIBLES PARA CHARLIEBOT`](https://github.com/CHARLIEPPP/Charlie-Bot/blob/f406e0f1bba1ca7cd6ee4ef3208e156135a24dce/config.js#L31) 
> Multi Lenguaje Dinámico GB: Disponibilidad de usar varios idiomas simultáneamente.
#### ✨ Español  [`Editar Idioma`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/espanol.js)
#### ✨ Inglés (English) [`Edit Language`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/ingles.js)
#### ✨ Portugués (Português) [`Idioma de Edição`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/portugues.js)
#### ✨ Indonesio (Bahasa Indonesia) [`Mengedit Bahasa`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/indonesio.js) 
#### ✨ Árabe (عرب) [`عدل اللغة`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/arabe.js)
----
> **Note** The translations are not perfect, it is only a reference, if you want to collaborate with the language or with another that is not on the list, contact me [`Contact me`](https://wa.me/5219516124971?text=Hola%20❤️%20Gata%20Dios,%20deseo%20colaborar%20con%20las%20traducciones%20de%20GataBot.%20Hello%20Gata%20Dios,%20I%20want%20to%20collaborate%20with%20the%20translations%20of%20GataBot%20😻.)


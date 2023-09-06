<p align="center">
</p>

<div align="center">
<a href="https://instagram.com/benja.exe7">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>

> ¡ Al acceder a la plataforma, obtendrás acceso a todos los enlaces oficiales de BenjaExe-Bot !

[`♻️ App Termux`](https://f-droid.org/es/packages/com.termux/)
### INSTALACIÓN AUTOMÁTICA - TERMUX

```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBotLite-MD/master/gatalite.sh | bash
```
### INSTALACIÓN MANUAL - TERMUX
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
git clone https://github.com/GataNina-Li/GataBotLite-MD 
cd GataBotLite-MD
yarn install
npm install
npm start
```

### TERMUX 24/7
> Comandos para realizar una ejecución 24/7
- INICIAR
> Use estos comandos dentro de la carpeta BenjaExe-Bot
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
```
- DETENER PM2
> Detener todos los procesos del bot
```bash
pm2 stop all && pm2 unstartup
```
- REANUDAR 
> Reanudar los procesos, usar dentro de la carpeta BenjaExe-Bot
```bash
pm2 start index.js 
```
- VISUALIZAR EL PROCESO
> Usar dentro de la carpeta BenjaExe-Bot para ver en tiempo real
```bash
pm2 logs 
```
- ELIMINAR PROCESOS PM2
> Eliminar todos los procesos del bot. Para volver a usar PM2 debe volver a usar los comandos de INICIAR
```bash
pm2 delete all
```

### 💠 [`IDIOMAS DISPONIBLES PARA BENJAEXE-BOT`]
#### ✨ Español  [`Editar Idioma`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/espanol.js)
----

### CREADOR
[BenjaExe-Bot] 

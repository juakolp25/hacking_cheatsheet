# 💻 hacking_cheatsheet

> **Ethical Hacking Quick Reference — TryHackMe Edition**  
> Una landing page interactiva de una sola página con los comandos esenciales para estudiantes de hacking ético y usuarios de TryHackMe.

---

## 🖥️ Preview

```
╔══════════════════════════════════════════════╗
║  HACK SHEET  //  Ethical Hacking Reference   ║
║  ⚡ RECON  🌐 WEB  💥 EXPLOIT  🔑 PRIVESC   ║
╚══════════════════════════════════════════════╝
```

![Dark Mode](https://img.shields.io/badge/Theme-Dark%20Mode-000000?style=for-the-badge&logo=gnometerminal&logoColor=00ff41)
![HTML5](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-00C832?style=for-the-badge)

---

## 📋 Contenido

La cheat sheet está organizada en **5 secciones navegables**:

| Sección | Herramientas | Comandos |
|---------|-------------|---------|
| 🎯 **Reconocimiento** | Nmap | 6 comandos (ping scan, SYN, agresivo, stealth, vuln scripts) |
| 🌐 **Enumeración Web** | Gobuster, Nikto | 5 comandos (directorios, extensiones, subdominios DNS) |
| 💥 **Explotación** | Metasploit, msfvenom, Netcat | 8 comandos (payloads, reverse shells, TTY upgrade) |
| 🔑 **Privilege Escalation** | find, sudo, LinPEAS | 6 comandos (SUID, cron, sudo -l, passwords) |
| 📦 **Transferencia de Archivos** | Python HTTP, SCP, Netcat, Base64 | 7 comandos |

---

## ✨ Features

- **🖤 Dark Mode** con estética hacker — scanlines CRT, lluvia de Matrix animada, glow verde neón
- **📋 Copy to Clipboard** — botón en cada comando con toast de confirmación
- **🏷️ Badges de riesgo** — cada comando clasificado como Pasivo / Agresivo / Intrusivo
- **🎨 Syntax highlighting** — flags, IPs, strings y opciones coloreadas en el código
- **📱 Responsive** — funciona en móvil, tablet y escritorio
- **⚡ Zero dependencias** — un único archivo `.html`, sin npm, sin build, sin instalación
- **🔤 Tipografías temáticas** — Orbitron + Share Tech Mono + Rajdhani

---

## 🚀 Uso

### Opción 1 — Abrir directamente

```bash
git clone https://github.com/TU_USUARIO/hacking_cheatsheet.git
cd hacking_cheatsheet
# Abre el archivo en tu navegador:
open hacking_cheatsheet.html        # macOS
xdg-open hacking_cheatsheet.html    # Linux
start hacking_cheatsheet.html       # Windows
```

### Opción 2 — Servir con Python

```bash
python3 -m http.server 8080
# Abre: http://localhost:8080/hacking_cheatsheet.html
```

### Opción 3 — GitHub Pages

Habilita GitHub Pages en tu repositorio apuntando a la rama `main` y accede directamente desde la URL pública.

---

## 🗂️ Estructura del Repositorio

```
hacking_cheatsheet/
│
├── hacking_cheatsheet.html   # Archivo principal (todo en uno)
├── README.md                 # Este archivo
└── LICENSE                   # MIT License
```

---

## 🔧 Personalización

Todos los colores están definidos como variables CSS al inicio del archivo. Puedes cambiar la paleta fácilmente:

```css
:root {
  --bg:      #050a05;    /* Fondo principal */
  --green:   #00ff41;    /* Acento verde neón */
  --blue:    #00d4ff;    /* Acento azul eléctrico */
  --yellow:  #ffd700;    /* Badge riesgo medio */
  --red:     #ff4141;    /* Badge riesgo alto */
}
```

Para añadir un nuevo comando, copia el bloque `.cmd-card` en la sección correspondiente y edita el contenido.

---

## ⚠️ Aviso Legal

> Este proyecto es exclusivamente para fines **educativos y de práctica ética**.  
> Los comandos aquí documentados deben usarse **únicamente en entornos autorizados** como:
> - [TryHackMe](https://tryhackme.com)
> - [HackTheBox](https://www.hackthebox.com)
> - Laboratorios propios y máquinas virtuales personales
>
> El uso no autorizado de estas técnicas en sistemas ajenos es **ilegal** y puede acarrear consecuencias legales graves. El autor no se hace responsable del mal uso de la información aquí contenida.

---

## 📚 Recursos Complementarios

- [GTFOBins](https://gtfobins.github.io/) — Escalada de privilegios con binarios de Unix
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) — Colección de payloads y bypasses
- [RevShells.com](https://www.revshells.com/) — Generador de reverse shells online
- [HackTricks](https://book.hacktricks.xyz/) — Wiki de técnicas de pentesting
- [SecLists](https://github.com/danielmiessler/SecLists) — Wordlists para fuzzing y enumeración

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si quieres añadir comandos, corregir errores o mejorar el diseño:

1. Haz un **fork** del repositorio
2. Crea una rama: `git checkout -b feature/nuevo-comando`
3. Haz tus cambios y un commit: `git commit -m 'feat: añadir comandos de SQLMap'`
4. Abre un **Pull Request**

---

## 📄 Licencia

Distribuido bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más información.

---

<div align="center">

Hecho con 💚 para la comunidad de **Ethical Hacking**

*"With great power comes great responsibility"*

</div>

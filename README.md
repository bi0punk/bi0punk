<div align="center">

<img src="./assets/terminal-profile.svg" width="100%" alt="Bi0punk terminal profile">

<br>

![Linux](https://img.shields.io/badge/Linux-070B14?style=for-the-badge&logo=linux&logoColor=39FF14)
![Python](https://img.shields.io/badge/Python-070B14?style=for-the-badge&logo=python&logoColor=00E5FF)
![Docker](https://img.shields.io/badge/Docker-070B14?style=for-the-badge&logo=docker&logoColor=00E5FF)
![Ansible](https://img.shields.io/badge/Ansible-070B14?style=for-the-badge&logo=ansible&logoColor=FF1744)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-070B14?style=for-the-badge&logo=hackthebox&logoColor=39FF14)
![DevOps](https://img.shields.io/badge/DevOps-070B14?style=for-the-badge&logo=gitlab&logoColor=B026FF)

</div>

---

## `root@bi0punk:~# ./stack --full`

<table>
<tr>
<td width="50%" valign="top">

### Core

![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=00E5FF)
![Bash](https://img.shields.io/badge/Bash-111827?style=flat-square&logo=gnubash&logoColor=39FF14)
![SQL](https://img.shields.io/badge/SQL-111827?style=flat-square&logo=postgresql&logoColor=00E5FF)
![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=F7DF1E)

### Backend

![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=00E5FF)
![Flask](https://img.shields.io/badge/Flask-111827?style=flat-square&logo=flask&logoColor=FFFFFF)
![Django](https://img.shields.io/badge/Django-111827?style=flat-square&logo=django&logoColor=39FF14)
![REST API](https://img.shields.io/badge/REST_API-111827?style=flat-square&logo=swagger&logoColor=B026FF)

### AI and Data

![OpenCV](https://img.shields.io/badge/OpenCV-111827?style=flat-square&logo=opencv&logoColor=00E5FF)
![YOLO](https://img.shields.io/badge/YOLO-111827?style=flat-square&logo=yolo&logoColor=B026FF)
![Pandas](https://img.shields.io/badge/Pandas-111827?style=flat-square&logo=pandas&logoColor=FFFFFF)
![LangChain](https://img.shields.io/badge/LangChain-111827?style=flat-square&logo=chainlink&logoColor=39FF14)
![Local LLM](https://img.shields.io/badge/Local_LLM-111827?style=flat-square&logo=ollama&logoColor=00E5FF)

</td>
<td width="50%" valign="top">

### Infrastructure

![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=00E5FF)
![Ansible](https://img.shields.io/badge/Ansible-111827?style=flat-square&logo=ansible&logoColor=FF1744)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-111827?style=flat-square&logo=gitlab&logoColor=FC6D26)
![Nginx](https://img.shields.io/badge/Nginx-111827?style=flat-square&logo=nginx&logoColor=39FF14)
![Tailscale](https://img.shields.io/badge/Tailscale-111827?style=flat-square&logo=tailscale&logoColor=FFFFFF)

### Observability

![Grafana](https://img.shields.io/badge/Grafana-111827?style=flat-square&logo=grafana&logoColor=F46800)
![Prometheus](https://img.shields.io/badge/Prometheus-111827?style=flat-square&logo=prometheus&logoColor=E6522C)
![Loki](https://img.shields.io/badge/Loki-111827?style=flat-square&logo=grafana&logoColor=B026FF)
![Datadog](https://img.shields.io/badge/Datadog-111827?style=flat-square&logo=datadog&logoColor=632CA6)

### Security

![Kali Linux](https://img.shields.io/badge/Kali_Linux-111827?style=flat-square&logo=kalilinux&logoColor=00E5FF)
![SIEM](https://img.shields.io/badge/SIEM-111827?style=flat-square&logo=elastic&logoColor=39FF14)
![Threat Intel](https://img.shields.io/badge/Threat_Intelligence-111827?style=flat-square&logo=virustotal&logoColor=B026FF)
![Hardening](https://img.shields.io/badge/System_Hardening-111827?style=flat-square&logo=securityscorecard&logoColor=FF1744)

</td>
</tr>
</table>

---

## `root@bi0punk:~# system-status`

```diff
+ Infrastructure automation       ONLINE
+ Threat detection                ONLINE
+ Security monitoring             ONLINE
+ Local artificial intelligence   ONLINE
+ Data processing pipelines       ONLINE
+ Computer vision systems         ONLINE
+ Continuous learning             ALWAYS ON
```

---

## Contenido

- [Características](#características)
- [Arquitectura](#arquitectura)
- [Stack](#stack)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Uso](#uso)
- [Configuración](#configuración)
- [Roadmap](#roadmap)
- [Licencia](#licencia)

## Características

- README de perfil de GitHub con estética de terminal cyberpunk.
- Banner principal vectorial (`assets/terminal-profile.svg`).
- Badges por categorías de stack: Core, Backend, AI and Data, Infrastructure, Observability y Security.
- Bloque de estado estilo `system-status` con `online`.
- Vista previa HTML local (`preview.html`) para revisar el perfil sin publicarlo.
- Guía de personalización en `CUSTOMIZE.md`: cambiar usuario, paleta de colores y despliegue.

## Arquitectura

```mermaid
flowchart TD
  README[README.md perfil] --> RENDER[GitHub renderiza el perfil]
  ASSET[assets/terminal-profile.svg] --> README
  PREVIEW[preview.html vista previa local] --> RENDER
  CUST[CUSTOMIZE.md guia de personalizacion] --> README
  USER[Repos dedica con el nombre de usuario] --> RENDER
  RENDER --> PERFIL[Pagina de perfil publica]
```

El repositorio funciona como página de perfil: GitHub muestra `README.md` como landing del perfil; el banner SVG da la identidad visual; `preview.html` sirve para previsualización local y `CUSTOMIZE.md` documenta cómo adaptarlo.

## Stack

Stack declarado en el perfil (badges):

| Categoría | Tecnologías |
|---|---|
| Core | Python, Bash, SQL, JavaScript |
| Backend | FastAPI, Flask, Django, REST API |
| AI and Data | OpenCV, YOLO, Pandas, LangChain, Local LLM |
| Infrastructure | Docker, Ansible, GitLab CI, Nginx, Tailscale |
| Observability | Grafana, Prometheus, Loki, Datadog |
| Security | Kali Linux, SIEM, Threat Intel, Hardening |

## Estructura del repositorio

```
bi0punk/
├── README.md              # Perfil (lo muestra GitHub)
├── CUSTOMIZE.md           # Guía de personalización rápida
├── preview.html           # Vista previa local del banner
├── assets/
│   ├── terminal-profile.svg    # Banner principal
│   └── terminal-profile-preview.png
├── LICENSE
└── .gitignore
```

## Uso

1. Crea un repositorio público con el mismo nombre que tu usuario de GitHub (p. ej. `bi0punk`).
2. Copia `README.md` y `assets/` en la raíz del repositorio.
3. Haz commit y push. GitHub mostrará el README como perfil.

```bash
git init
git add README.md assets/
git commit -m "feat: add cyberpunk GitHub profile"
git branch -M main
git remote add origin <tu-repo>
git push -u origin main
```

Para previsualizar antes de publicar, abre `preview.html` en el navegador: muestra el banner del perfil sin necesidad de subir cambios.

## Configuración

Personalización documentada en `CUSTOMIZE.md`:

- **Cambiar el usuario**: reemplaza todas las apariciones de `bi0punk` en `README.md` y `assets/terminal-profile.svg`.
- **Paleta de colores**: fondo `#070B14`, verde terminal `#39FF14`, cian `#00E5FF`, morado `#B026FF`, texto secundario `#94A3B8`, rojo de alerta `#FF1744`.
- **Despliegue**: clona el README y los assets en el repositorio con tu nombre de usuario y haz push.

## Roadmap

- [x] Banner cyberpunk y badges de stack
- [x] Vista previa HTML y guía de personalización
- [ ] Badges dinámicos (actividad, tecnologías en obras, etc.)
- [ ] Sección destacada de proyectos

## Licencia

MIT — ver [LICENSE](LICENSE).
<div align="center">

<img src="./assets/terminal-profile.svg" width="100%" alt="Bi0punk — terminal profile">

<br>

![Linux](https://img.shields.io/badge/Linux-070B14?style=for-the-badge&logo=linux&logoColor=39FF14)
![Python](https://img.shields.io/badge/Python-070B14?style=for-the-badge&logo=python&logoColor=00E5FF)
![Docker](https://img.shields.io/badge/Docker-070B14?style=for-the-badge&logo=docker&logoColor=00E5FF)
![Ansible](https://img.shields.io/badge/Ansible-070B14?style=for-the-badge&logo=ansible&logoColor=FF1744)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-070B14?style=for-the-badge&logo=hackthebox&logoColor=39FF14)
![DevOps](https://img.shields.io/badge/DevOps-070B14?style=for-the-badge&logo=gitlab&logoColor=B026FF)

</div>

---

## `root@bi0punk:~# whoami`

```yaml
user:       bi0punk
role:       Ingeniero de sistemas · automatización, seguridad y datos
base:       Chile · trabajo remoto
focus:
  - Computer vision sobre RTSP (YOLO / OpenCV)
  - LLM locales y agentes (llama.cpp, LangGraph)
  - Infraestructura reproducible (Docker, Ansible, CI/CD)
  - Pipelines de datos y observabilidad (Kafka, PostgreSQL, Grafana)
principio: "Automatiza lo repetible, observa lo importante, asegura lo demás."
```

Construyo sistemas que **ven, escuchan y deciden** en la periferia: cámaras que
detectan en tiempo real, modelos que corren sin depender de la nube y
automatizaciones que dejan de necesitar a una persona mirando una pantalla.

Me importa que lo que entrego sea **reproducible**: un `docker compose up`, un
CI en verde y una guía que otra persona pueda seguir sin preguntarme nada.

---

## `root@bi0punk:~# ls proyectos/`

| Proyecto | Qué resuelve | Stack |
|---|---|---|
| [**catfinder**](https://github.com/bi0punk/catfinder) | Detección de gatos en cámaras RTSP con overlay, evidencias y alertas por Telegram | Python · YOLO · Flask · Docker |
| [**ipcam-hunter**](https://github.com/bi0punk/ipcam-hunter) | Alerta cuando una persona permanece en una ROI; snapshot a WhatsApp y dashboard MJPEG | Python · YOLO · FastAPI · WAHA |
| [**llama-webapp**](https://github.com/bi0punk/llama-webapp) | Gestor de modelos GGUF y centro de control para `llama-server` desde la web | FastAPI · SQLAlchemy · Redis/RQ |
| [**repo-analyzer**](https://github.com/bi0punk/repo-analyzer) | Diagnóstico de repos y bundle de contexto listo para un LLM; también como GitHub Action | Python · LangChain · Docker |
| [**kpi-datapipeline**](https://github.com/bi0punk/kpi-datapipeline) | Pipeline Kafka → PostgreSQL con KPIs por minuto/hora/día y entrega *at-least-once* | Kafka · PostgreSQL · Docker |
| [**readme-llm-gen**](https://github.com/bi0punk/readme-llm-gen) | Reconstruye READMEs analizando el código, con LLM local | Python · LangGraph · Ollama |

---

## `root@bi0punk:~# cat stack.txt`

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
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-111827?style=flat-square&logo=githubactions&logoColor=00E5FF)
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

## `root@bi0punk:~# cat principios.md`

- **CI verde o no se mergea.** `ruff`, `mypy`, tests con cobertura y auditoría de
  dependencias en cada push.
- **Un comando para probar.** `docker compose up` o `make demo`; si necesita diez
  pasos manuales, todavía no está terminado.
- **La documentación es parte del código.** Configuración, despliegue y
  troubleshooting viven en `docs/`, no en mi cabeza.
- **Seguridad por defecto.** Contenedores sin root, secretos fuera de git y
  dependencias auditadas.
- **Menos ruido, más señal.** Logs útiles, healthchecks y métricas que responden
  “¿está funcionando?” en un vistazo.

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

<div align="center">

### `ACCESS GRANTED`

![Profile Views](https://komarev.com/ghpvc/?username=bi0punk&color=39FF14&style=for-the-badge&label=PROFILE+ACCESS)

```text
Automate everything.
Secure everything.
Observe everything.
Keep building.
```

**“Hack the planet, automate the boring stuff and engineer systems that last.”**

¿Tienes una cámara, un modelo o un pipeline que necesita dejar de ser manual?
Abre un issue en cualquiera de los repos.

</div>

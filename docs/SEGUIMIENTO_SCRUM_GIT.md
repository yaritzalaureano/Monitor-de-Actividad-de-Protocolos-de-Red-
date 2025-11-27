# SEGUIMIENTO DEL PROYECTO (SCRUM) MEDIANTE GIT  
**Proyecto:** Sistema de Monitoreo de Protocolos  
**Metodología:** SCRUM  

---

# ✔ ¿Qué es este documento?  
Este archivo sirve para registrar los **cambios más importantes del proyecto**, indicando cómo **cada commit** se relaciona con:

- Un Sprint  
- Una Historia de Usuario (HU)  
- Un Incremento del producto  

---

# ✔ Formato que usaré en los commits

Formato obligatorio para cada commit:

`<tipo>: <descripción> - Sprint <N> - HU-<N>`

Ejemplos:

- `feat: agregar captura de IP - Sprint 1 - HU-02`
- `docs: actualizar seguimiento scrum - Sprint 1 - HU-00`

---

# 🟦 SPRINT 1 – Captura de información del sistema

### Commit: feat: script inicial de captura - Sprint 1 - HU-01
**Descripción:**  
Se creó el archivo inicial `agent_capture.ps1` para capturar:  
- Hostname  
- Sistema operativo  
- MAC  
- IP  

---

### Commit: feat: regla de 10 minutos para puertos - Sprint 1 - HU-02  
**Descripción:**  
Se implementó la lógica que evita registrar un puerto si ya fue usado en los últimos 10 minutos.

---

# 🟩 SPRINT 2 – Validación y Base de Datos

### Commit: chore: agregar modelo MySQL - Sprint 2 - HU-03  
**Descripción:**  
Se creó el archivo `schema.sql` con las tablas:  
- Equipo  
- Fabricante  
- Protocolo  
- Protocolo Usado  

---

### Commit: feat: validación de MAC/IP duplicados - Sprint 2 - HU-04  
**Descripción:**  
Se implementó una función que verifica si una IP o MAC ya pertenece a otro equipo.

---

# 🟨 SPRINT 3 – Cliente en Windows y servicio

### Commit: feat: agregar icono en System Tray - Sprint 3 - HU-05  
**Descripción:**  
Se implementó un ícono en la barra de tareas que no permite cerrar el programa.

---

### Commit: feat: servicio automático - Sprint 3 - HU-06  
**Descripción:**  
El cliente ahora se ejecuta como servicio al iniciar Windows.

---

# 🟧 SPRINT 4 – Interfaz web y reportes

### Commit: feat: crear dashboard web - Sprint 4 - HU-07  
**Descripción:**  
Se implementó una interfaz web responsiva que muestra la actividad de los equipos.

---

### Commit: feat: gráficos de protocolos - Sprint 4 - HU-08  
**Descripción:**  
Se agregaron gráficos de pastel para protocolos seguros e inseguros.

---

# ✔ FIN DEL DOCUMENTO  
Cada nuevo commit importante debe agregarse aquí.

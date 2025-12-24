# Remote-Control-Agent (RCA) – DadRat

**DadRat** es un agente de administración y control remoto diseñado para **laboratorios de seguridad, simulaciones controladas y ejercicios de investigación ofensiva y defensiva** en entornos corporativos autorizados.

<p align="center">
  <img width="520" alt="Vista general" src="https://github.com/user-attachments/assets/0ec4c5da-e50e-4fc7-bc65-13e33a29b339" />
</p>

---

## ⚠️ Disclaimer

Este proyecto es una herramienta profesional diseñada para **evaluaciones de seguridad, pruebas de penetración y servicios de ciberseguridad** prestados a organizaciones, **bajo contrato y con autorización expresa del propietario de los sistemas**.

Su uso está estrictamente limitado a **entornos corporativos** en los que exista un **acuerdo legal previo** que habilite las actividades de prueba.

El autor **no asume responsabilidad alguna** por el uso indebido, no autorizado o contrario a la legislación vigente.

---

## 🔒 Limitaciones de la DEMO

La versión demo cuenta únicamente con las siguientes secciones habilitadas:

- **Agentes**
- **Payloads** (C# y PowerShell)
- **Info**
- **Opciones**

Al ejecutar un payload, **se abrirá una ventana visible**, como medida preventiva para evitar un uso indebido.

---

## 🚀 Versión Full

### Payloads adicionales incluidos
- Payload **Python** para Linux  
- **C# → EXE**
- **Python → EXE**
- **PowerShell scripts**
- **Shellcode / BIN**
- **PowerShell → Shellcode**
- **C# → Shellcode**

### Módulos de bypass
- Bypass **UAC** (Windows 10 y 11)  
- Bypass **ETW**  
- Bypass **AMSI** (Windows 10 y 11)

### Ofuscación de payloads
- **EXE**
- **Shellcode**
- **PowerShell**

---

## ▶️ Uso

⚠️ **Importante:**  
Se recomienda ejecutar los payloads **exclusivamente en entornos aislados**, como **máquinas virtuales (VirtualBox u otras)** o sistemas de laboratorio alternos.

---

### 1️⃣ Inicio de sesión

Inicia sesión con las siguientes credenciales de la demo:

- **Correo:** `DadratDemo@kvx.com`  
- **Contraseña:** `kvxfree`

Luego, ajusta el **puerto** y la **IP de conexión**.  
La IP local se mostrará automáticamente en el panel derecho.

<p align="center">
  <img width="640" alt="Configuración inicial" src="https://github.com/user-attachments/assets/6bdfb21c-9349-490e-a7e8-b25bf991c440" />
</p>

---

### 2️⃣ Creación del payload

A continuación, se muestra un ejemplo de la configuración de un payload:

<p align="center">
  <img width="640" alt="Configuración del payload" src="https://github.com/user-attachments/assets/29d4effa-5f71-4fe1-b69f-b64a73df7649" />
</p>

---

### 3️⃣ Ejecución del agente

Una vez generado el payload, abre el ejecutable ubicado en la carpeta **`baul-rat`**.  
Al ejecutarlo, se mostrará una ventana similar a la siguiente:

<p align="center">
  <img width="640" alt="Ejecución del agente" src="https://github.com/user-attachments/assets/26a6fd07-0cdf-4e27-8bd4-deb211da71ca" />
</p>

---

### 4️⃣ Agente conectado

Finalmente, el agente aparecerá conectado y visible en el panel de control:

<p align="center">
  <img width="640" alt="Agente conectado" src="https://github.com/user-attachments/assets/05807f9e-d0dd-4ec3-a657-8c6686ca0e58" />
</p>

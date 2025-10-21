# web-training-semana1

# 🌐 Semana 1 – Fundamentos Web + Configuración del Entorno

**Objetivo:** entender cómo funciona una web y preparar el entorno de trabajo.

---

## 🧭 Tareas principales
- Crear una carpeta compartida (Google Drive o Notion).
- Instalar herramientas: **VS Code**, **Canva**, **Figma**, **WordPress local (LocalWP)**.
- Hacer el curso corto de **HTML y CSS básico** en [freeCodeCamp](https://www.freecodecamp.org/learn/).
- Crear un pequeño “Hello World” en HTML + CSS.
- Dividir el trabajo según roles:

| Rol | Tarea principal |
|-----|------------------|
| 🧩 A | Aprende Figma (interfaz + wireframes) |
| 💻 B | Aprende HTML y CSS en profundidad |
| ✍️ C | Aprende copywriting web (titulares y textos persuasivos) |

---

## 📂 Estructura del repositorio

web-training-semana1/
│
├── README.md
├── html-css/
│ ├── index.html
│ └── style.css
│
├── figma/
│ └── enlaces.md
│
├── copywriting/
│ └── textos.md
│
├── recursos/
│ ├── herramientas.md
│ └── links-curso-freecodecamp.md
│
└── notas-equipo/
└── tareas-semana1.md

---

## 🤝 Cómo colaborar paso a paso

> Si nunca usaste Git o GitHub, sigue estas instrucciones con calma. No necesitas conocimientos previos de programación.

### 1️⃣ Crear tu cuenta y acceder al repositorio
1. Crea una cuenta en [GitHub.com](https://github.com) si aún no tienes una.
2. Pide al responsable del equipo que te agregue como **colaborador** del repositorio.
3. Acepta la invitación que te llegará por correo o desde la sección de **Invitations** en GitHub.
4. Entra al repositorio:  
   👉 [https://github.com/tuusuario/web-training-semana1](https://github.com/tuusuario/web-training-semana1)

---

### 2️⃣ Clonar el repositorio en tu computadora
1. Instala **Git** desde [git-scm.com](https://git-scm.com/downloads).
2. Crea una carpeta donde guardarás el proyecto (por ejemplo, en tu escritorio).
3. Abre **Visual Studio Code (VS Code)**.
4. En VS Code, selecciona **Archivo → Abrir carpeta...** y elige esa carpeta vacía.
5. Abre la terminal integrada con **Ctrl + Ñ** o **Ctrl + `**.
6. Escribe el siguiente comando y presiona **Enter**:

   ```bash
   git clone https://github.com/tuusuario/web-training-semana1.git
Entra en la carpeta clonada:

bash
Copiar código
cd web-training-semana1
3️⃣ Crear tu propia rama de trabajo
Las ramas son versiones paralelas del proyecto que permiten trabajar sin alterar el trabajo de otros.

Crea una nueva rama con tu nombre o rol. Por ejemplo:

bash
Copiar código
git checkout -b ana-figma
A partir de ahora, todos tus cambios se guardarán en tu propia rama.

4️⃣ Hacer tus aportes
Abre los archivos y edita lo que necesites (HTML, CSS, textos, etc.).

Guarda tus cambios.

En la terminal, escribe:

bash
Copiar código
git add .
git commit -m "Descripción breve de lo que hiciste"
git push origin ana-figma
(Reemplaza ana-figma por el nombre de tu rama.)

5️⃣ Crear un Pull Request (PR)
Un Pull Request es una solicitud para que tus cambios se revisen antes de unirlos al proyecto principal.

Ve al repositorio en GitHub.

Verás un botón que dice “Compare & pull request” → haz clic.

Añade un título y una breve descripción (por ejemplo: “Agrego wireframe inicial de Figma”).

Haz clic en “Create Pull Request”.

El resto del equipo podrá revisar, comentar y aprobar tus cambios antes de incorporarlos al proyecto.

6️⃣ Actualizar tu copia local
Antes de empezar a trabajar cada día, asegúrate de tener los últimos cambios del equipo:

bash
Copiar código
git checkout main
git pull origin main
Si quieres volver a tu rama:

bash
Copiar código
git checkout ana-figma
💬 Consejos útiles
No trabajes directamente sobre la rama main.

Usa una rama nueva para cada tarea importante.

Escribe mensajes de commit claros y cortos.
Ejemplo:

bash
Copiar código
git commit -m "Corrijo estilos del header"
Si te equivocas, pide ayuda antes de hacer “force push”.

🧠 Recursos de apoyo
GitHub Desktop → alternativa visual sin usar la terminal.

Curso básico de Git y GitHub (YouTube – freeCodeCamp Español)

Documentación oficial de GitHub


<!-- ================= HEADER ================= -->
<h1 align="center">🚀 TaskFlow</h1>
<h3 align="center">Gestor de Tareas Full-Stack</h3>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Estructura-orange">
  <img src="https://img.shields.io/badge/CSS3-Responsive-blue">
  <img src="https://img.shields.io/badge/JavaScript-DOM-yellow">
  <img src="https://img.shields.io/badge/Node.js-Backend-green">
  <img src="https://img.shields.io/badge/Express-API-lightgrey">
</p>

<p align="center">
  Práctica Integradora — Ingeniería en Sistemas Computacionales
</p>

<hr>

<!-- ================= DESCRIPCIÓN ================= -->
<h2>📌 Descripción</h2>

<p>
<strong>TaskFlow</strong> es una aplicación web full-stack para gestionar tareas.
Integra frontend moderno con backend usando una API REST.
</p>

<ul>
  <li>HTML5 semántico</li>
  <li>CSS3 (Flexbox, Grid, Responsive)</li>
  <li>JavaScript (DOM, Fetch, async/await)</li>
  <li>Node.js + Express</li>
</ul>

<hr>

<!-- ================= TECNOLOGÍAS ================= -->
<h2>🛠️ Tecnologías</h2>

<p>
HTML5 • CSS3 • JavaScript • Node.js • Express • CORS • Nodemon
</p>

<hr>

<!-- ================= ESTRUCTURA ================= -->
<h2>📁 Estructura del Proyecto</h2>

<pre>
taskflow/
├── server.js
├── package.json
└── public/
    ├── index.html
    ├── css/
    │   └── styles.css
    └── js/
        └── app.js
</pre>

<hr>

<!-- ================= INSTALACIÓN ================= -->
<h2>⚙️ Instalación</h2>

<pre>
mkdir taskflow
cd taskflow
npm init -y
npm install express cors
npm install --save-dev nodemon
</pre>

<hr>

<!-- ================= SCRIPTS ================= -->
<h2>▶️ Scripts</h2>

<pre>
"scripts": {
  "start": "node server.js",
  "dev": "nodemon server.js"
}
</pre>

<hr>

<!-- ================= EJECUCIÓN ================= -->
<h2>🚀 Ejecutar Proyecto</h2>

<pre>
npm run dev
</pre>

<p>Abre en tu navegador:</p>

<pre>http://localhost:3000</pre>

<hr>

<!-- ================= API ================= -->
<h2>🔥 API REST</h2>

<table>
  <tr>
    <th>Método</th>
    <th>Ruta</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/tareas</td>
    <td>Obtener todas las tareas</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/tareas/:id</td>
    <td>Obtener tarea por ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/tareas</td>
    <td>Crear tarea</td>
  </tr>
  <tr>
    <td>PUT</td>
    <td>/api/tareas/:id</td>
    <td>Actualizar tarea</td>
  </tr>
  <tr>
    <td>PATCH</td>
    <td>/api/tareas/:id/toggle</td>
    <td>Completar/Pendiente</td>
  </tr>
  <tr>
    <td>DELETE</td>
    <td>/api/tareas/:id</td>
    <td>Eliminar tarea</td>
  </tr>
</table>

<hr>

<!-- ================= FUNCIONALIDADES ================= -->
<h2>🎯 Funcionalidades</h2>

<ul>
  <li>✅ Crear tareas</li>
  <li>✅ Marcar como completadas</li>
  <li>✅ Eliminar tareas</li>
  <li>✅ Filtrar por categoría</li>
  <li>✅ Diseño responsive</li>
</ul>

<hr>

<!-- ================= UI ================= -->
<h2>🎨 UI / Diseño</h2>

<ul>
  <li>🎯 CSS Grid & Flexbox</li>
  <li>📱 Responsive Design</li>
  <li>✨ Animaciones suaves</li>
  <li>🎚️ Filtros dinámicos</li>
</ul>

<hr>

<!-- ================= TIEMPO ================= -->
<h2>⏱️ Distribución del Tiempo</h2>

<table>
  <tr>
    <th>Fase</th>
    <th>Actividad</th>
    <th>Tiempo</th>
  </tr>
  <tr><td>1</td><td>Setup + Express</td><td>15 min</td></tr>
  <tr><td>2</td><td>API REST</td><td>20 min</td></tr>
  <tr><td>3</td><td>HTML</td><td>20 min</td></tr>
  <tr><td>4</td><td>CSS</td><td>25 min</td></tr>
  <tr><td>5</td><td>JavaScript</td><td>25 min</td></tr>
  <tr><td>6</td><td>Extras</td><td>15 min</td></tr>
</table>

<hr>

<!-- ================= RETOS ================= -->
<h2>🧪 Retos Extra</h2>

<ul>
  <li>🔍 Búsqueda en tiempo real</li>
  <li>🌙 Modo oscuro</li>
  <li>🎬 Animaciones al eliminar</li>
  <li>📊 Endpoint de estadísticas</li>
</ul>

<hr>

<!-- ================= CHECKLIST ================= -->
<h2>✅ Checklist</h2>

<ul>
  <li>Servidor funcionando</li>
  <li>CRUD completo</li>
  <li>UI funcional</li>
  <li>Responsive</li>
  <li>Sin errores en consola</li>
</ul>

<hr>

<!-- ================= ENTREGA ================= -->
<h2>📦 Entrega</h2>

<ul>
  <li>Comprimir proyecto (.zip)</li>
  <li><strong>NO incluir node_modules</strong></li>
  <li>Subir a GitHub o plataforma</li>
</ul>

<hr>

<!-- ================= FOOTER ================= -->
<h2>💡 Nota Final</h2>

<p align="center">
  Cada línea de código te acerca a ser mejor desarrollador 🚀
</p>

<p align="center">
  <strong>Hecho con 💻 por ISC</strong>
</p>

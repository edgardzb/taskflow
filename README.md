<h1 align="center">TaskFlow — Gestor de Tareas Full-Stack</h1>
<h3 align="center">Práctica Integradora de Fin de Curso</h3>

<p align="center">
Ingeniería en Sistemas Computacionales — 2º Semestre
</p>

<hr>

<h2>Descripción del Proyecto</h2>

<p>
En esta práctica construirás <strong>TaskFlow</strong>, una aplicación web de gestión de tareas completamente funcional.
Integrarás conocimientos de:
</p>

<ul>
<li><strong>HTML5:</strong> estructura semántica, formularios, data-attributes</li>
<li><strong>CSS3:</strong> Flexbox, Grid, animaciones, responsive</li>
<li><strong>JavaScript:</strong> DOM, eventos, Fetch API, async/await</li>
<li><strong>Node.js + Express:</strong> backend con API REST</li>
</ul>

<p><strong>Duración:</strong> 2 horas (120 minutos)</p>
<p><strong>Modalidad:</strong> Individual o en parejas</p>
<p><strong>Entregable:</strong> Repositorio funcional</p>

<hr>

<h2>Competencias a Evaluar</h2>

<table>
<tr><th>Área</th><th>Competencia</th><th>Tópicos</th></tr>
<tr><td>HTML5</td><td>Estructura semántica</td><td>header, nav, main, section, form</td></tr>
<tr><td>CSS3</td><td>Diseño responsive</td><td>Flexbox, Grid, animaciones</td></tr>
<tr><td>JavaScript</td><td>Manipulación DOM</td><td>Fetch API, async/await</td></tr>
<tr><td>Node.js</td><td>API REST</td><td>Express, rutas, middleware</td></tr>
</table>

<hr>

<h2>Distribución del Tiempo</h2>

<table>
<tr><th>Fase</th><th>Actividad</th><th>Duración</th></tr>
<tr><td>1</td><td>Configuración del proyecto</td><td>15 min</td></tr>
<tr><td>2</td><td>API REST</td><td>20 min</td></tr>
<tr><td>3</td><td>HTML</td><td>20 min</td></tr>
<tr><td>4</td><td>CSS</td><td>25 min</td></tr>
<tr><td>5</td><td>JavaScript</td><td>25 min</td></tr>
<tr><td>6</td><td>Extras</td><td>15 min</td></tr>
</table>

<hr>

<h2>⚙️ Fase 1: Configuración</h2>

<pre>
mkdir taskflow
cd taskflow
npm init -y
npm install express cors
npm install --save-dev nodemon
</pre>

<h3>Estructura</h3>

<pre>
taskflow/
├── server.js
├── package.json
└── public/
</pre>

<hr>

<h2>Fase 2: API REST</h2>

<h3>GET tareas</h3>
<pre>GET /api/tareas</pre>

<h3>POST tarea</h3>
<pre>POST /api/tareas</pre>

<h3>PUT actualizar</h3>
<pre>PUT /api/tareas/:id</pre>

<h3>DELETE</h3>
<pre>DELETE /api/tareas/:id</pre>

<hr>

<h2>Fase 3: HTML</h2>

<p>Uso de etiquetas semánticas:</p>

<pre>
&lt;header&gt; &lt;nav&gt; &lt;main&gt; &lt;section&gt; &lt;footer&gt;
</pre>

<hr>

<h2>🎨 Fase 4: CSS</h2>

<ul>
<li>Variables CSS</li>
<li>Flexbox y Grid</li>
<li>Animaciones</li>
<li>Media Queries</li>
</ul>

<hr>

<h2>Fase 5: JavaScript</h2>

<ul>
<li>Fetch API</li>
<li>async/await</li>
<li>Manipulación DOM</li>
<li>Eventos</li>
</ul>

<hr>

<h2>🧪 Fase 6: Extras</h2>

<ul>
<li>Búsqueda en tiempo real</li>
<li>Modo oscuro</li>
<li>Animaciones</li>
<li>Endpoint de estadísticas</li>
</ul>

<hr>

<h2>✅ Checklist</h2>

<ul>
<li>Servidor funciona</li>
<li>CRUD completo</li>
<li>UI funcional</li>
<li>Responsive</li>
<li>Sin errores</li>
</ul>

<hr>

<h2>📦 Entrega</h2>

<ul>
<li>Subir proyecto</li>
<li>No incluir node_modules</li>
</ul>

<hr>

<h2>📊 Rúbrica</h2>

<table>
<tr><th>Criterio</th><th>Puntos</th></tr>
<tr><td>Backend</td><td>20</td></tr>
<tr><td>HTML</td><td>15</td></tr>
<tr><td>CSS</td><td>20</td></tr>
<tr><td>JavaScript</td><td>25</td></tr>
<tr><td>Responsive</td><td>10</td></tr>
<tr><td>Código limpio</td><td>10</td></tr>
<tr><td><strong>Total</strong></td><td><strong>100</strong></td></tr>
</table>

<hr>

<p align="center">
💡 Cada línea de código te acerca a ser mejor desarrollador 🚀
</p>

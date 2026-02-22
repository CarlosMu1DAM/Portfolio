<h1 align="center">🎮 API & App Directorio de Empleados</h1>

<p align="center">
Proyecto académico desarrollado con <b>FastAPI</b> y <b>.NET MAUI</b>
</p>

<hr/>

<h2>📌 Descripción</h2>

<p>
Aplicación multiplataforma desarrollada en <b>.NET MAUI</b> que consume una API REST creada con <b>FastAPI</b>.
Permite gestionar empleados y departamentos, visualizar estadísticas y realizar operaciones CRUD.
</p>

<hr/>

<h2>🚀 Tecnologías Utilizadas</h2>

<ul>
  <li><b>Backend:</b> FastAPI, SQLModel, PostgreSQL, SQLite</li>
  <li><b>Frontend:</b> .NET MAUI</li>
  <li><b>Patrón:</b> Arquitectura por capas + MVVM</li>
  <li><b>Contenedores:</b> Docker</li>
  <li><b>Documentación:</b> Swagger UI</li>
</ul>

<hr/>

<h2>📂 Estructura Backend</h2>

<pre>
app/
 ├── core
 ├── db
 ├── models
 ├── schemas
 ├── services
 ├── routers
 └── main.py
</pre>

<hr/>

<h2>📂 Estructura MAUI</h2>

<pre>
MauiAppPractica/
 ├── Models
 ├── ViewModels
 ├── Pages
 ├── Services
 ├── AppShell.xaml
 └── MauiProgram.cs
</pre>

<hr/>

<h2>⚙ Funcionalidades</h2>

<ul>
  <li>✔ Listado de empleados</li>
  <li>✔ Listado de departamentos</li>
  <li>✔ Vista detalle</li>
  <li>✔ Añadir empleado (POST)</li>
  <li>✔ Eliminar empleado (DELETE)</li>
  <li>✔ Vista gráfica</li>
  <li>✔ Navegación Shell</li>
</ul>

<hr/>

<h2>📸 Capturas</h2>

<p align="center">
  <img src="imagenes/listado.png" width="400"/>
  <img src="imagenes/grafica.png" width="400"/>
</p>

<hr/>

<h2>🐳 Ejecución Backend</h2>

<pre>
pip install -r requirements.txt
uvicorn app.main:app --reload
</pre>

Swagger disponible en:

<pre>
http://localhost:8000/docs
</pre>

<hr/>

<h2>📱 Ejecución App MAUI</h2>

<pre>
Abrir solución en Visual Studio 2022
Ejecutar proyecto MauiAppPractica
</pre>

<hr/>

<h2>👤 Autor</h2>

<p>
Nombre Apellidos<br>
Asignatura: SGE / DI<br>
Curso 2025-2026
</p>

<hr/>

<p align="center">
⭐ Proyecto académico con fines educativos
</p>

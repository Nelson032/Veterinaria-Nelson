# Veterinaria-Nelson

Una propuesta de una sola pagina pensado para una veterinaria, por el momento armado con HTML, CSS.
Es un solo archivo que podés abrir en el navegador y listo.

- Ver los **servicios** que ofrecemos (consulta, vacunas, cirugía, urgencias, etc.)
- Saber **por qué elegirnos**
- **Pedir un turno** escribiendo por el formulario de contacto

## 🗂️ ¿Diseño?

Todo el código vive en un solo archivo: **`index.html`**. Adentro tiene:

| Parte | Qué es |
|-------|--------|
| **Navegación** | Barra fija arriba con el logo y los enlaces. 
| **Hero** | Lo primero que ves: un título, botones para reservar y unas estadísticas de la clínica. |
| **Servicios** | Seis tarjetas con los servicios que ofrecemos. |
| **Por qué elegirnos** | Los motivos por los cuales la gente debería venir a la clínica, con sus checkmarks. |
| **Contacto** | Formulario para que la gente deje su consulta + la dirección, teléfono y horarios. |
| **Footer** | El cierre de la página, con datos y enlaces rápidos. |


## 🚀 ¿Cómo laPueden ver?

No hace falta instalar nada. Dos opciones:

**Opción 1 — la más directa:**
Doble clic sobre `index.html` y se abre en tu navegador.

**Opción 2 — como si fuera "producción":**
Si querés hacerlo desde visual y ver actualización al momento, levantá un servidor local:

**TENER EN CUENTA QUE DEBES TENER INSTALADO EN TU PC, algunas de las version de Python:**

```bash
python3 -m http.server 8080
```

Y entrás a `http://localhost:8080`.


## 🧪 ¿formulario?

Por ahora es **Prueba falta la parte de la conexion**: valida que el nombre y el email estén bien escritos y te tira un mensajito de "¡Mensaje enviado!". Pero no envía nada a ningún lado todavía. O sea: sirve para mostrar, no para recibir consultas de verdad.


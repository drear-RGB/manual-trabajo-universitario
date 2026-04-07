# 📘 Manual de Buenas Prácticas para Trabajos Universitarios en Grupo

**Versión:** v1.0  
**Fecha:** Abril 2026  
**Repositorio:** GitHub  

---

## Tabla de Contenidos

1. [Organización del equipo](#1-organización-del-equipo)
2. [Gestión del tiempo](#2-gestión-del-tiempo)
3. [Formatos y citación APA](#3-formatos-y-citación-apa)
4. [Herramientas colaborativas](#4-herramientas-colaborativas)
5. [Presentación de trabajos](#5-presentación-de-trabajos)
6. [Control de versiones con GitHub](#6-control-de-versiones-con-github)

---

## 1. Organización del equipo

### 1.1 Roles recomendados

Para un grupo universitario se recomienda asignar los siguientes roles rotativos:

| Rol | Responsabilidad |
|-----|----------------|
| **Coordinador/a** | Organiza reuniones, hace seguimiento de tareas |
| **Redactor/a** | Lidera la escritura y coherencia del documento |
| **Revisor/a** | Verifica ortografía, formato y coherencia |
| **Investigador/a** | Busca fuentes y referencias bibliográficas |

> 💡 **Buena práctica:** Rotar los roles en cada trabajo para que todos desarrollen todas las habilidades.

### 1.2 Primera reunión

Antes de empezar cualquier trabajo, realizar una reunión inicial donde se definan:

- El objetivo y alcance del trabajo
- Las fechas clave (entrega parcial, entrega final)
- Los canales de comunicación (WhatsApp, Discord, correo)
- La división de secciones por integrante

---

## 2. Gestión del tiempo

### 2.1 Regla del 70-20-10

Divide el tiempo total disponible así:

- **70%** → Investigación, desarrollo y escritura
- **20%** → Revisión, correcciones y unificación del documento
- **10%** → Formato final, revisión APA y entrega

### 2.2 Cronograma sugerido

Para un trabajo con **2 semanas** de plazo:

| Día | Actividad |
|-----|-----------|
| 1-2 | Reunión inicial, reparto de tareas, creación del repositorio |
| 3-7 | Investigación y redacción de cada sección |
| 8-10 | Entrega interna de secciones, revisión cruzada |
| 11-12 | Correcciones, unificación y formato |
| 13 | Revisión final y entrega |
| 14 | Buffer (margen de emergencia) |

> ⚠️ **Evitar:** Dejar todo para los últimos días. La revisión es tan importante como la redacción.

### 2.3 Herramientas de gestión

- **GitHub Projects (Kanban):** Para organizar tareas en columnas: *Por hacer / En progreso / Hecho*
- **Google Calendar:** Para fijar fechas de reunión y entrega
- **Notion o Trello:** Alternativas para seguimiento de tareas

---

## 3. Formatos y citación APA

### 3.1 Formato del documento

- **Fuente:** Times New Roman 12pt o Arial 11pt
- **Interlineado:** 2.0 (doble espacio) en APA 7ª edición
- **Márgenes:** 2.54 cm (1 pulgada) por todos los lados
- **Alineación:** Justificada
- **Sangría:** 1.27 cm al inicio de cada párrafo

### 3.2 Estructura general APA

```
1. Portada
2. Resumen (Abstract) — si se requiere
3. Introducción
4. Desarrollo (secciones temáticas)
5. Conclusiones
6. Referencias
7. Apéndices — si aplica
```

### 3.3 Tipos de citas APA 7

**Cita directa corta** (menos de 40 palabras):

> "El aprendizaje colaborativo mejora significativamente el rendimiento académico" (García, 2021, p. 45).

**Cita directa larga** (40 palabras o más): en bloque, sin comillas, sangría de 1.27 cm.

**Cita parafraseada:**

> Según García (2021), trabajar en equipo tiene efectos positivos en el rendimiento de los estudiantes.

### 3.4 Referencias bibliográficas

**Libro:**
> Apellido, N. (Año). *Título del libro*. Editorial.

**Artículo de revista:**
> Apellido, N. (Año). Título del artículo. *Nombre de la Revista*, *volumen*(número), páginas. https://doi.org/...

**Página web:**
> Apellido, N. (Año, día de mes). Título del artículo. Nombre del sitio. URL

> 💡 **Herramienta útil:** Usa [Zotero](https://www.zotero.org/) o [Citation Machine](https://www.citationmachine.net/) para generar referencias APA automáticamente.

---

## 4. Herramientas colaborativas

### 4.1 GitHub para documentos

GitHub no es solo para programadores. Para trabajos universitarios permite:

- Guardar el historial completo de cambios
- Trabajar en paralelo sin pisarse el trabajo
- Revisar los aportes de cada integrante
- Volver a versiones anteriores si algo sale mal

### 4.2 Flujo de trabajo recomendado en GitHub

```
main (rama principal)
 ├── seccion-introduccion    ← cada integrante trabaja aquí
 ├── seccion-desarrollo
 └── seccion-conclusiones
```

**Pasos:**
1. Cada integrante crea su propia rama: `git checkout -b mi-seccion`
2. Hace cambios y los guarda: `git add . && git commit -m "Agrego introducción"`
3. Sube su rama: `git push origin mi-seccion`
4. Crea un **Pull Request** para que el equipo revise
5. El coordinador aprueba y fusiona con `main`

### 4.3 Otras herramientas útiles

| Herramienta | Uso |
|-------------|-----|
| **Google Docs** | Redacción colaborativa en tiempo real |
| **Grammarly** | Corrección ortográfica y de estilo |
| **Canva** | Diseño de presentaciones y portadas |
| **Mendeley** | Gestión de referencias bibliográficas |
| **Notion** | Organización de notas e ideas del equipo |

---

## 5. Presentación de trabajos

### 5.1 Presentación oral

- **Duración:** Respeta estrictamente el tiempo asignado
- **Diapositivas:** Máximo 1 diapositiva por minuto de presentación
- **Regla 6x6:** Máximo 6 líneas por diapositiva, 6 palabras por línea
- **Ensayar:** Al menos una vez completa antes de la presentación real

### 5.2 Diseño de diapositivas

**Hacer:**
- Usar imágenes de alta calidad
- Mantener consistencia visual (mismos colores y fuentes)
- Incluir números de diapositiva
- Usar gráficas en lugar de tablas con muchos datos

**Evitar:**
- Leer directamente de las diapositivas
- Textos muy pequeños (mínimo 24pt)
- Demasiados colores o fuentes diferentes
- Animaciones distractoras

### 5.3 Entrega de documentos escritos

Antes de entregar, verificar esta lista:

- [ ] Portada completa (nombre, materia, docente, fecha)
- [ ] Paginación correcta
- [ ] Citas en formato APA
- [ ] Lista de referencias al final
- [ ] Ortografía revisada
- [ ] Formato uniforme en todo el documento
- [ ] Nombre del archivo correcto (ej: `Apellido_Materia_Trabajo1.pdf`)

---

## 6. Control de versiones con GitHub

### 6.1 Estructura del repositorio

```
📁 mi-trabajo-universitario/
 ├── 📄 README.md
 ├── 📄 CHANGELOG.md
 ├── 📁 /documentos
 │    ├── manual_v1.0.md
 │    └── manual_v1.0.pdf
 ├── 📁 /imagenes
 └── 📁 /referencias
```

### 6.2 Buenas prácticas de commits

Un buen mensaje de commit describe **qué** se hizo y **por qué**:

```bash
# Buenos mensajes
git commit -m "Agrego sección de citación APA 7"
git commit -m "Corrijo errores ortográficos en introducción"
git commit -m "Actualizo referencias bibliográficas"

# Malos mensajes
git commit -m "cambios"
git commit -m "arreglos"
git commit -m "no sé"
```

### 6.3 Etiquetas de versión (Tags)

Cuando el documento está listo para una entrega:

```bash
git tag -a v1.0 -m "Primera versión del manual"
git push origin v1.0
```

### 6.4 Issues para organizar el trabajo

Crear un Issue por cada sección del manual:

- `#1` - Redactar sección Organización del equipo
- `#2` - Redactar sección Gestión del tiempo
- `#3` - Redactar sección Citación APA
- `#4` - Revisión final y formato

Asigna cada issue a un integrante y ciérralo con el Pull Request correspondiente.

---

## 📎 Recursos adicionales

- [Guía APA 7ª edición — Normas APA](https://normasapa.in/)
- [GitHub Docs en español](https://docs.github.com/es)
- [Markdown Guide](https://www.markdownguide.org/)
- [Zotero — Gestor de referencias](https://www.zotero.org/)

---
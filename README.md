# Actividad: Propuesta de práctica temática pequeña (LOOM)

## 1) Título de la práctica
**Diseña tu práctica temática pequeña**

> Ejemplos de títulos que puedes usar o adaptar:
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general
En esta actividad vas a **diseñar y documentar** una propuesta de proyecto pequeño para terminal.

Tu propuesta debe:
- Tener una temática concreta y útil.
- Poder construirse en pequeño (alcance realista para una entrega corta).
- Elegir **un solo lenguaje principal**:
  - ARM64 Assembly
  - C
  - Python
  - Bash

### Importante sobre el lenguaje
- Si eliges **ARM64 Assembly**, tu programa debe ser **muy pequeño** (por ejemplo: operaciones simples, lectura básica de argumentos, impresión de resultados).
- Si eliges **C, Python o Bash**, también se espera una solución ligera, sin complejidad innecesaria.

### Enfoque principal de la actividad
La prioridad **no** es escribir mucho código al inicio. La prioridad es:
1. Definir bien la idea.
2. Justificar el caso de uso.
3. Diseñar estructura del repositorio.
4. Planear pruebas básicas.
5. Documentar claramente lo que se va a construir.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcionales (si decides incluir implementación):
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta estructura mínima como guía:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Guía de contenido por archivo

### `README.md`
Incluye:
- Nombre del proyecto.
- Descripción breve (3 a 6 líneas).
- Lenguaje principal elegido y por qué.
- Alcance del proyecto en una primera versión (MVP).
- Instrucciones básicas de uso (aunque todavía no esté implementado completo).

### `docs/propuesta.md`
Incluye:
1. **Problema a resolver**.
2. **Objetivo general**.
3. **Objetivos específicos** (3 a 5).
4. **Alcance** (qué sí hará y qué no hará).
5. **Justificación técnica** del lenguaje elegido.
6. **Plan mínimo de implementación** (pasos cortos).

### `docs/caso_de_uso.md`
Incluye:
- Perfil de usuario objetivo (quién lo usaría).
- Escenario principal de uso (paso a paso).
- Entradas esperadas.
- Salidas esperadas.
- Criterios de éxito del caso.

### `docs/estructura_repositorio.md`
Incluye:
- Árbol de carpetas propuesto.
- Función de cada carpeta/archivo.
- Convenciones de nombres (por ejemplo: `snake_case`, prefijos, etc.).
- Estrategia para crecimiento gradual sin romper simplicidad.

### `docs/plan_de_pruebas.md`
Incluye al menos 5 casos de prueba con:
- ID del caso.
- Descripción.
- Entrada.
- Resultado esperado.
- Resultado obtenido (puede quedar en blanco inicialmente).

---

## 6) Restricciones del proyecto
Para mantener la práctica accesible y compatible con herramientas gratuitas:

- ❌ No usar frameworks grandes.
- ❌ No usar APIs pagadas.
- ❌ No usar bases de datos.
- ❌ No usar servicios en la nube.
- ❌ No usar contenedores.
- ❌ No agregar dependencias complejas o difíciles de instalar.

- ✅ Sí se permite uso de librerías estándar del lenguaje.
- ✅ Sí se permite automatización simple con scripts.
- ✅ Sí se permite una implementación mínima funcional.

---

## 7) Requisitos de calidad de documentación
Tu propuesta debe ser:
- Clara y entendible para otra persona.
- Coherente entre problema, solución y pruebas.
- Realista para el tiempo de la práctica.
- Replicable por alguien con entorno local básico.

Redacción recomendada:
- Usa secciones con títulos claros.
- Usa listas y tablas cuando ayuden.
- Evita texto ambiguo.
- Justifica decisiones técnicas con argumentos concretos.

---

## 8) Rúbrica sugerida (100 puntos)

- **Definición del problema y objetivos** – 20 pts
- **Calidad del caso de uso** – 20 pts
- **Diseño de estructura del repositorio** – 20 pts
- **Plan de pruebas (claridad y cobertura mínima)** – 20 pts
- **Coherencia, redacción y formato de documentación** – 20 pts

---

## 9) Entrega
Publica tu repositorio en GitHub Classroom con todos los archivos solicitados.

Si incluyes código, debe ser una versión mínima y alineada con la documentación.

---

## 10) Sugerencia de inicio rápido para el estudiante
1. Elige un tema pequeño (ejemplo: organizador de archivos por extensión).
2. Elige un lenguaje principal.
3. Escribe primero `docs/propuesta.md`.
4. Después desarrolla `docs/caso_de_uso.md` y `docs/plan_de_pruebas.md`.
5. Por último, si te da tiempo, implementa una versión mínima en `src/`.


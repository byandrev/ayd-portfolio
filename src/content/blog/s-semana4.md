---
title: 'Semana 4: Análisis PERT en Proyectos de Software'
description: ''
pubDate: 2025-02-24T22:00:00.000Z
heroImage: ../../assets/images/analisis_pert.jpg
category: Software
tags:
  - clase
---

# 🧮 Análisis PERT: Estimaciones Realistas para Proyectos de Software

Durante la semana 4 del curso de Ingeniería de Software, exploramos el **método PERT** (Program Evaluation and Review Technique), una técnica fundamental para la **estimación de tiempos** y la **planificación de actividades** en proyectos complejos, como lo son los de desarrollo de software.

---

## ⏱️ ¿Qué es el Método PERT?

El método PERT permite **estimar la duración de tareas** cuando hay incertidumbre, usando tres valores:

- **Tiempo optimista (O):** El mínimo tiempo posible si todo va bien.
- **Tiempo más probable (M):** El tiempo esperado en condiciones normales.
- **Tiempo pesimista (P):** El máximo tiempo posible si algo sale mal.

Con estos valores, se calcula un **tiempo esperado (TE)** para cada actividad:

\[
\text{TE} = \frac{O + 4M + P}{6}
\]

Esta fórmula ponderada da mayor peso al tiempo más probable, lo cual mejora la precisión de la planificación.

---

## 📊 ¿Por qué usar PERT en Software?

El desarrollo de software está lleno de incertidumbre: cambios en requisitos, tecnologías nuevas, dependencias externas. PERT permite **abordar esa incertidumbre con datos**, ayudando a:

- Crear cronogramas más realistas.
- Identificar actividades críticas.
- Calcular márgenes de seguridad (holguras).
- Prever retrasos antes de que ocurran.

---

## 🧩 Componentes Clave de un Diagrama PERT

- **Nodos (eventos):** Representan el inicio o fin de una actividad.
- **Arcos (actividades):** Muestran las tareas necesarias y sus duraciones esperadas.
- **Ruta crítica:** Es la secuencia de actividades que determina la duración total del proyecto. Si una tarea de esta ruta se retrasa, todo el proyecto se retrasa.

> **Ejemplo:**  
> Si crear la base de datos tiene O=2, M=4 y P=8 días, entonces:  
> TE = (2 + 4×4 + 8) / 6 = 26 / 6 ≈ 4.33 días.

---

## 📐 Aplicación Práctica en el Proyecto

Durante la semana, aplicamos el análisis PERT a nuestras tareas clave. Ejemplo:

- **Actividad:** Implementar backend  
  - O: 3 días, M: 5 días, P: 9 días  
  - TE: (3 + 4×5 + 9) / 6 = 32 / 6 ≈ 5.33 días

Esto nos ayudó a:

- Identificar cuáles tareas tienen mayor incertidumbre.
- Determinar en qué partes conviene agregar márgenes.
- Priorizar tareas críticas para cumplir con la fecha de entrega.

---

## ✅ Conclusión: Planificar con Incertidumbre es Posible

El análisis PERT no elimina la incertidumbre, pero nos da herramientas para **entenderla y gestionarla con datos**. Con esta técnica, planificamos mejor, evitamos sorpresas y hacemos que nuestros proyectos sean más predecibles y eficientes.

> **Frase para recordar:**  
> “Una buena estimación no es exacta, es útil.”

---

# BlümSens

**Maceta Inteligente e Invernadero Modular con Visión para Salud Foliar**

Proyecto de la materia **Innovación Tecnológica** (Ingeniería de Software, UACJ). Profesor: Abraham López Nájera.
Equipo: **BlumSoft**.

## Descripción

BlümSens es una maceta inteligente que monitorea una planta mediante sensores (humedad, luz, temperatura y ambiente), analiza su estado, incluida la salud de las hojas mediante visión por computadora, y avisa al usuario desde una aplicación cuando detecta un problema o una necesidad de cuidado.

El producto está pensado para quienes tienen plantas en casa y no siempre saben cuándo regar, cuánta luz necesitan o por qué se ven afectadas sus hojas. Un estudio de mercado propio (98 respuestas) respalda esta necesidad: ver `docs/` y el Anexo A del documento de la Fase 2.

## Equipo

| Integrante |
|---|
| Blanca Dariela Almanza Lome |
| Alan Alejandro Hipolito de Santiago |
| Diego Alejandro Jasso Fernández |
| Ricardo Rodríguez Ponce |
| Brayan Omar Tobias Ornelas |

## Metodología y gestión

- **Metodología:** Kanban.
- **Tablero:** Jira, proyecto **KAN** (tareas, responsables, fechas límite y dependencias).
- **Plan de trabajo:** ProjectLibre (tiempos esperados con PERT), del 31/08/2026 al 24/11/2026, con ruta crítica identificada.
- **Seguimiento en GitHub:** issues por actividad, etiquetas por área e hitos por etapa.

### Hitos

| Hito | Contenido |
|---|---|
| Planeación | Nombre, misión, objetivos, alcance, mercado, FODA, costos y encuesta |
| Diseño | Arquitectura, diagramas, modelo de datos y diseño de la aplicación |
| Implementación y pruebas | Hardware, firmware, backend, aplicación y pruebas del prototipo |
| Li-Fi | Pruebas exploratorias de comunicación por luz |

### Etiquetas

`diseno`, `hardware`, `firmware`, `backend`, `app`, `pruebas`, `documentacion`, `li-fi`

## Estructura del repositorio

```
Blumsens/
├── README.md
└── docs/
    ├── Fase1_BlumSoft.pdf
    ├── Fase2_BlumSens_Plan_PERT_Costos_GitHub.docx
    ├── plan/            # archivo .pod de ProjectLibre y su PDF
    └── diagramas/       # arquitectura, casos de uso, clases, entidad-relación
```

## Flujo de trabajo con ramas

- `main`: versión estable y entregable.
- `develop`: integración del trabajo en curso.
- `feature/<nombre>-<tarea>`: una rama por tarea; se une a `develop` mediante *pull request*.

Para colaborar:

```bash
git clone https://github.com/Al214545/Blumsens.git
cd Blumsens
git checkout develop
git checkout -b feature/tu-nombre-tarea
# haz tus cambios
git add .
git commit -m "Describe brevemente el cambio"
git push -u origin feature/tu-nombre-tarea
# abre un pull request hacia develop
```

## Estado actual

Fase 2: plan de trabajo, matriz FODA, recursos y costos, y organización del proyecto en Jira y GitHub.

## Documentación

Los documentos de cada fase están en la carpeta [`docs/`](docs/).

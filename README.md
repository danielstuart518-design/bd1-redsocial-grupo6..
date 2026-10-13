# bd1-redsocial-grupo6

## Integrantes del equipo
* Eisson Javier Oyola Tique
* Julian Quintero Copete
* Jonathan Andres Serna Velasco
* Daniel Alejandro Stuart Muñoz

---

## Breve descripción del caso
El proyecto consiste en la implementación del **modelo físico de base de datos** para la **Red Social Estudiantil Pascualina**. La necesidad surge debido a que las plataformas institucionales actuales son formales y no facilitan la interacción casual, el intercambio de conocimientos ni la organización espontánea de actividades entre estudiantes.

Esta plataforma permite a la comunidad estudiantil:
* **Crear perfiles:** Compartir áreas de estudio, intereses, habilidades y deportes.
* **Conectar con compañeros:** Encontrar y seguir a otros estudiantes o cursos avanzados para mentoría.
* **Publicar actualizaciones:** Compartir preguntas sobre tareas, recursos útiles, noticias tecnológicas o memes universitarios.
* **Crear y unirse a grupos:** Organizar equipos de estudio, hackatones o clubes de interés (videojuegos, programación competitiva, etc.).
* **Programar eventos:** Anunciar y coordinar reuniones de estudio, talleres o actividades sociales.

En esta tercera etapa, se selecciona e implementa un **Sistema de Gestión de Bases de Datos (SGBD) relacional**, transformando el modelo lógico previo en un **script DDL funcional**. Se definen las tablas bajo estándares rigurosos de nomenclatura, tipos y tamaños de datos precisos, claves primarias (PK), claves foráneas (FK) con sus respectivas acciones referenciales (`ON DELETE`, `ON UPDATE`), e índices para optimizar la integridad y el rendimiento del sistema.

---

## Estructura del repositorio

```text
bd1-redsocial-grupo6/
├── README.md
└── Tarea3/
    ├── Informe/
    │   ├── informe_modelo_fisico.pdf
    │   └── script_redsocial.sql
    └── Video/
        └── enlace_video.txt

# CTMM Open

Repositorio oficial propuesto para **CTMM Core 1.0** (*Computational Thinking Measurement Model*), un modelo para medir y evaluar habilidades de pensamiento computacional mediante evidencias observables.

> Estado: versión de preparación 0.1. La publicación como CTMM Core 1.0 requiere aprobación de autoría, licencias y reglas comunes de valoración.

## Qué es CTMM

CTMM integra:

- cuatro habilidades del núcleo: abstracción, descomposición, pensamiento algorítmico/lógico y depuración;
- tres niveles cognitivos: N1 recordar/comprender, N2 aplicar/analizar y N3 evaluar/crear;
- la Taxonomía de Bloom para la era digital;
- el enfoque Goal Question Metric (GQM);
- evaluación basada en productos, procesos, ejecución, pruebas y explicación.

El modelo puede aplicarse en actividades de programación, robótica, resolución de problemas, construcción de artefactos y actividades desconectadas.

## Cómo empezar

1. Lea la [visión general](docs/01-vision-general.md).
2. Consulte las [habilidades y niveles](docs/02-habilidades-y-niveles.md).
3. Diseñe la evaluación con el [procedimiento de aplicación](docs/03-procedimiento-aplicacion.md).
4. Seleccione o adapte un instrumento en [`instrumentos/`](instrumentos/README.md).
5. Documente el contexto, las evidencias y los cambios realizados.

## Estructura

```text
ctmm-open/
├── README.md
├── CITATION.cff
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── CHANGELOG.md
├── ROADMAP.md
├── VERSIONING.md
├── LICENSE-CONTENT.md
├── LICENSE-SOFTWARE
├── docs/
├── instrumentos/
├── casos/
├── software/
├── investigacion/
└── .github/ISSUE_TEMPLATE/
```

## Versiones y extensiones

- **CTMM Core** contiene las definiciones estables de habilidades, niveles y proceso de evaluación.
- **CTMM Educación Superior** contextualiza el modelo para cursos universitarios e incorpora verificación y ética como dimensiones adicionales en revisión.
- **CTMM+IA** orienta su aplicación en actividades mediadas por inteligencia artificial generativa.
- **CTMM-DS** se mantiene como línea de evolución que integra diseño didáctico y evaluación.

Las extensiones no modifican silenciosamente el núcleo. Consulte [VERSIONING.md](VERSIONING.md).

## Contribuir

Docentes e investigadores pueden proponer indicadores, instrumentos, casos y mejoras. Toda contribución debe identificar:

- contexto educativo;
- habilidad y nivel CTMM;
- evidencia observable;
- instrumento utilizado;
- cambio realizado;
- resultados y limitaciones.

Consulte [CONTRIBUTING.md](CONTRIBUTING.md) y [GOVERNANCE.md](GOVERNANCE.md).

## Licencias propuestas

- Documentación, guías e instrumentos originales de CTMM: **CC BY-SA 4.0**, después de la aprobación de los titulares.
- Código fuente: **Apache License 2.0**.
- Datos de investigación: licencia y condiciones específicas según consentimiento, anonimización y normativa aplicable.

## Citación

La referencia provisional y los metadatos de citación se encuentran en [CITATION.cff](CITATION.cff). Se actualizarán cuando exista una versión pública con DOI.

## Autores del modelo original

- René Fabián Zúñiga Muñoz
- Julio Ariel Hurtado Alegría
- Marcos Román-González
- Gregorio Robles

La extensión universitaria CTMM+IA reconoce además la contribución de Angela María Muñoz Muñoz.


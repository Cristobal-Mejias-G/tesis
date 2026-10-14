# Justicia de Mercado en Salud: Un estudio de 30 años en Chile

Tesis de pregrado en Sociología, Universidad de Chile. Profesor guía: Juan Carlos Castillo.

Evolución de las preferencias por justicia de mercado en salud en Chile (1999, 2009 y 2019), con tres hipótesis: interés racional (H1), percepción de meritocracia (H2) y percepción de brecha salarial (H3).

## Estructura

| Carpeta o archivo | Contenido |
|---|---|
| `*.qmd` | Capítulos del libro (Quarto Book), numerados en orden de lectura |
| `_quarto.yml` | Configuración del libro |
| `input/data/original/` | Datos originales, sin modificar (no se versionan) |
| `input/data/proc/` | Bases procesadas (no se versionan) |
| `input/bib/` | `Tesis.bib` (exportado desde Zotero) y `apa.csl` |
| `proc/` | Scripts de R, numerados en orden de ejecución |
| `output/` | Tablas y figuras generadas |
| `assets/` | Estilos |
| `decisiones.md` | Bitácora de decisiones metodológicas y teóricas |

## Cómo reproducir

1. Instalar Quarto y R. 
2. Ubicar los datos originales en `input/data/original/`
3. Ejecutar los scripts de `proc/` en orden.
4. Renderizar: `quarto render`.



# Trivia SERUMS / ENARM — Salud Pública, Investigación y Especialidades

Aplicación web autónoma (una sola página) para repasar preguntas de simulacros **SERUMS / ENARM**, con **412 preguntas** clasificadas, respuesta correcta, **fundamento** y **referencias en formato AMA**.

**Autor:** Dr. Joshuan J. Barboza — Investigador RENACYT · ORCID 0000-0002-2896-1407

## Contenido del banco

| Área | N.º de preguntas |
|------|------------------|
| Salud Pública e Investigación | 343 |
| Ética y Medicina Legal | 28 |
| Especialidades Clínicas (GO, Pediatría, Cirugía, Medicina Interna, etc.) | 41 |
| **Total** | **412** |

**Fuentes compiladas:** Banqueo Final Salud Pública USAMEDIC 2023, Simulacros por Especialidad QX Medic (Básico y Avanzado), Primer Simulacro SERUMS Villamedic y Examen ENAM 2025 (Ordinario I).

## Funcionalidades

- **Modo Trivia:** rondas aleatorias de 10, 20, 30 o 50 preguntas. Al responder se muestra si es correcto, el **fundamento** y las **referencias AMA**. Al final, puntaje y revisión completa.
- **No repite preguntas:** cada ronda toma preguntas aún no mostradas (memoria en `localStorage`); al agotarse el filtro, el ciclo se reinicia automáticamente. Al **actualizar (refresh)** obtienes preguntas distintas.
- **Modo Lectura:** todas las preguntas del filtro con su respuesta marcada, fundamento y referencias; incluye buscador por palabra clave y paginación.
- **Filtros:** por Área, Especialidad y Tema.

## Archivos

```
index.html      ← aplicación (abre directamente en el navegador)
questions.js     ← banco de 412 preguntas (datos)
.nojekyll        ← evita el procesamiento Jekyll en GitHub Pages
README.md
```

## Publicar en GitHub Pages

1. Crea un repositorio (por ejemplo `trivia-serums`) y sube estos archivos a la raíz.
2. En **Settings → Pages**, selecciona *Deploy from a branch* → rama `main` → carpeta `/root`.
3. En pocos minutos estará disponible en `https://TU-USUARIO.github.io/trivia-serums/`.

También puedes probarla localmente haciendo doble clic en `index.html`.

## Nota

Banco con fines educativos, elaborado a partir de simulacros de acceso público. Los fundamentos y referencias son orientativos; ante discrepancias, prevalece la normativa vigente del MINSA y las guías clínicas actualizadas.

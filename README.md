# EcoMatriz

Herramienta web (un solo archivo, sin dependencias) para:

1. **Identificar** actividades, aspectos e impactos ambientales.
2. **Evaluar** el riesgo: probabilidad (1–5) × severidad (1–5).
3. **Proponer** medidas de mitigación según la jerarquía: eliminar → sustituir → controlar → compensar.

## Niveles de riesgo

| Puntaje | Nivel |
|---|---|
| 1–4 | Bajo |
| 5–9 | Moderado |
| 10–15 | Alto |
| 16–25 | Crítico |

Cada registro calcula el riesgo inherente y el residual (después de aplicar medidas).

## Uso

Abre `index.html` en el navegador. Los datos se guardan en `localStorage`; también puedes exportar a CSV/JSON e importar JSON.

## Publicar en GitHub Pages

1. Crea un repositorio y sube `index.html` y `README.md`.
2. En *Settings → Pages*, elige la rama `main` y la carpeta `/ (root)`.
3. Tu app quedará en `https://<usuario>.github.io/<repositorio>/`.

## Personalizar

El catálogo de aspectos, impactos y medidas está en la constante `CAT` dentro de `index.html`. Ajusta los criterios a tu normativa (ISO 14001, LMP/ECA locales).

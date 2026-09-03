# Auto-Documentador Tech

Skill para agentes de programación (GitHub Copilot y similares) que genera **documentación técnica formal en LaTeX** a partir de lo que el usuario pida documentar: resumen del proyecto, nuevos requerimientos, diagramas de flujo, manuales, reportes, estimaciones, etc.

## ✨ Características

- **Portada minimalista** con `titlepage`.
- **Detecta el logo** del proyecto (imágenes en `img/` o `logo.*`) y lo incluye en la portada.
- **Detecta la paleta de colores** del proyecto y la aplica al documento.
- **Fecha actual** en portada y pie de página (`\today`).
- **Tablas con formato corporativo** (cabecera con fondo de color principal y texto blanco, filas alternas).
- **Código** con `listings` / `texttt`.
- **Organización automática** del `Documentos/` en subcarpetas según la solicitud.

## 📦 Instalación

Copia la carpeta `Auto-Documentador-Tech` dentro de tu carpeta de skills:

- **Windows:** `%USERPROFILE%\.agents\skills\`
- **macOS / Linux:** `~/.agents/skills/`

```
~/.agents/skills/Auto-Documentador-Tech/
└── SKILL.md
```

## 🚀 Uso

Invoca la skill y pide documentar lo que necesites. Ejemplos:

```
/auto-documentador-tech resumen del proyecto
/auto-documentador-tech nuevos requerimientos del módulo de pagos
/auto-documentador-tech diagrama de flujo del proceso de registro
```

## 🧩 Requisitos

- VS Code
- Extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [MiKTeX](https://miktex.org/download) (u otro motor LaTeX)
- Un agente con soporte de skills (GitHub Copilot)

## 📄 Estructura

```
Auto-Documentador-Tech/
├── SKILL.md
└── ...
```

## 📝 Licencia

MIT — ver [LICENSE](LICENSE).

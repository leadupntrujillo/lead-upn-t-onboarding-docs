# <img src="../../assets/images/org_emoji_animated.gif" width=25> Estándar de Commits (Lead UPN Style)

**Autor:** [Axel Castro A.] 

**Fecha:** [08/03/2026] 

**Versión:** 1.2.0

---

Para mantener un historial profesional y legible, utilizaremos Conventional Commits. Esto no es opcional; es parte de nuestra cultura de ingeniería.

## Estructura del Commit
Formato base: `tipo (alcance opcional): descripción breve`

* **tipo**: Indica qué clase de cambio hiciste.
* **(alcance opcional)**: Indica dónde está el cambio (nombre del módulo, archivo o componente). Va entre paréntesis.
* **descripción breve**: Un resumen imperativo (como una orden) de máximo 50 caracteres.
    * *Ejemplo*: `fix(landing): corregir alineación de fotos en móviles`
* **[Cuerpo opcional]**: explicación detallada del "por qué".

## Tipos Permitidos (tipo)

| Tipo | Descripción | Ejemplo |
| :--- | :--- | :--- |
| **feat** | Una nueva funcionalidad (incrementa MINOR en semver). | `feat: add google login button` |
| **fix** | Solución a un bug (incrementa PATCH en semver). | `fix: resolve crash on pdf export` |
| **docs** | Cambios solo en documentación. | `docs: update API endpoints in readme` |
| **style** | Espacios, puntos y comas, formato (no afecta lógica). | `style: format user.controller.js` |
| **refactor** | Cambio de código que no arregla bugs ni añade features. | `refactor: simplify auth middleware logic` |
| **test** | Añadir o corregir tests existentes. | `test: add unit test for date parser` |
| **chore** | Tareas de mantenimiento, dependencias, build. | `chore: upgrade node version to 20` |

## Reglas de Oro para el Mensaje
1.  **Imperativo**: Escribe como si estuvieras dando una orden.
    * *Bien*: `feat: add dark mode` (Añadir modo oscuro)
    * *Mal*: `feat: added dark mode` (Añadido...) o `feat: adding dark mode` (Añadiendo...) (Es decir, no uses gerundios).
2.  **Minúsculas**: La descripción empieza en minúscula (salvo nombres propios).
    * *Bien*: `fix: validate user email`
    * *Mal*: `fix: Validate User Email`
3.  **Sin punto final**: No pongas "." al final de la línea del asunto.
4.  **Atómico**: Si tu commit dice "feat: add login AND fix header", divídelo en dos commits.

## Ejemplos Reales

**Caso 1: Nueva feature simple**
`git commit -m "feat(auth): implement JWT token generation"`

**Caso 2: Fix con explicación en el cuerpo**
`git commit -m "fix: prevent header overflow on mobile" -m "The header was covering the content on screens smaller than 320px due to fixed positioning."`

**Caso 3: Cambio que rompe compatibilidad (Breaking Change)**
`git commit -m "feat!: remove support for v1 api endpoints"`
*(Nota el signo de exclamación `!` antes de los dos puntos)*

--- 

## <img src="https://cdn-icons-png.flaticon.com/512/337/337946.png" width="24" alt="Document"> **Para profundizar:**  
Si tienes alguna duda particular o quieres ver el detalle completo, revisa la sección correspondiente en la guía original: [Guía: Trunk-Based Development][URL].

[URL]: https://Rellenar-en-un-momento.com
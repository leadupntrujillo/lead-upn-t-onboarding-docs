# 🤝 Cómo contribuir a Onboarding Docs

¡Gracias por tu interés en mejorar la documentación de Lead UPN Trujillo! La documentación es un esfuerzo de todo el equipo. 

Para mantener el orden y la calidad, te pedimos que sigas estas directrices al proponer cambios.

## 1. Reglas Generales
* **Usa las plantillas:** Si vas a crear un documento o guía nueva, por favor utiliza las plantillas ubicadas en la carpeta `templates/`. Copia el archivo, pégalo en la ruta correspondiente y llena la información.
* **Sé claro y conciso:** Escribe pensando en alguien que acaba de entrar al equipo. Usa listas, negritas y bloques de código.
* **Imágenes ligeras:** Si necesitas subir diagramas o capturas a `assets/`, asegúrate de que sean ligeras (idealmente `.webp` o `.svg`) para no saturar el repositorio.

## 2. Flujo de Trabajo (Workflow)
Aplicamos las mismas reglas de ingeniería para nuestros documentos:

1. **Asegúrate de estar actualizado:** Haz `git pull origin main`.
2. **Crea una rama:** Crea una rama efímera para tu cambio. 
   * Ejemplo: `git checkout -b docs/agregar-guia-astro` o `chore/actualizar-readme`.
3. **Haz tus cambios:** Escribe o actualiza la documentación en formato Markdown (`.md`).
4. **Commits estandarizados:** Usa Conventional Commits.
   * Ejemplo: `docs(setup): agregar paso de instalacion de pnpm`
5. **Abre un Pull Request (PR):** Sube tu rama y abre un PR hacia `main`. Solicita la revisión al equipo de LEAD UPN Trujillo.

## 3. ¿Dudas?
Si no estás seguro de dónde debería ir un documento nuevo, abre un Issue primero para discutirlo con el equipo o pregunta en nuestro canal de comunicación interno.
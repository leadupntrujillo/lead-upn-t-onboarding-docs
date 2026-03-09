# Preguntas Frecuentes (FAQ) - Flujo de Trabajo

**Q: Mi tarea es muy grande para 2 días, ¿qué hago?**
R: Desglósala. En lugar de `feat/sistema-usuarios` (enorme), haz `feat/user-db-schema`, luego `feat/user-login-api`, luego `feat/user-ui`. Usa Feature Flags para ocultar lo que no esté listo.

**Q: ¿Puedo hacer commit directo a main?**
R: JAMÁS. Es pecado capital en Lead UPN. Todo cambio pasa por PR y Code Review.

**Q: Rompí Staging, ¿me van a despedir de la org?**
R: No. Staging es para romperse. Arréglalo rápido (`fix/`) y aprende del error para que no pase a Producción.

> "El mejor código es el que está en producción aportando valor, no el que vive perfecto en una rama local." 
> - Lead UPN Trujillo - Pilar de Desarrollo Profesional

# Registro de Conflictos (`CONFLICT-LOG.md`)

Este archivo documenta los conflictos encontrados durante el desarrollo del sitio web "Eventos Chiapas".

---

## Conflicto #1

**📅 Fecha:** 1 de junio de 2025.  
**📂 Archivo afectado:** index.html.  
**🔀 Ramas involucradas:** `main`, `josue-eventos`

### 📝 Descripción:

Se modificó la misma línea en `index.html` en ambas ramas:

- En `main`:
  ```html
  <h1>Bienvenido a Mi Página</h1>
  ```
- En `josue-eventos`:
  ```html
  <h1>Eventos Chiapas - Página Oficial</h1>
  ```

Esto causó un conflicto al intentar hacer merge de `josue-eventos` en `main`.

### ✅ Solución aplicada:

Se resolvió el conflicto manualmente usando el título de la rama `josue-eventos`:

```html
<h1>Eventos Chiapas - Página Oficial</h1>
```
Se hizo `git add index.html` y `git commit` para finalizar la resolución.

**👤 Resuelto por:** Josué López Cruz.  
**📅 Fecha de resolución:** 1 de junio de 2025.  
**🛠️ Método:** Edición manual y prueba visual en navegador.

---
# 🎼 BerniTech Rider

**Rider técnico para bandas escolares y agrupaciones musicales.**  
Creá, organizá y exportá tu rider en minutos, sin instalar nada.

![BerniTech Rider](https://img.shields.io/badge/version-2.0-6366f1?style=flat-square) ![PWA](https://img.shields.io/badge/PWA-ready-10b981?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-f59e0b?style=flat-square)

---

## ✨ Funcionalidades

- **Lista de inputs** — canales, micrófonos, pies y extras por sección
- **Monitores** — tipos, cantidades y notas de mezcla
- **Escenario visual** — arrastrá y rotá músicos sobre el plano del escenario
- **Íconos de instrumentos** — imágenes propias para 10 instrumentos (Batería, Clarinete, Flauta, Piano, Saxo Alto/Tenor/Barítono, Trombón, Trompeta, Voz)
- **Exportar PDF** — rider completo listo para imprimir o compartir
- **Portada personalizada** — subí una foto de portada con ajuste de escala
- **Logo de la banda** — aparece en el header del rider
- **Banner personalizable** — imagen de fondo para el encabezado
- **Dictado por voz** — cargá canales hablando (Chrome/Edge)
- **Autosave automático** — guarda en IndexedDB, nada se pierde al cerrar
- **Exportar/importar preset** — guardá configuraciones como `.json`
- **Paleta de colores** — personalizá la estética del rider
- **PWA instalable** — funciona como app en Android, iOS y desktop

---

## 🚀 Uso

### Opción 1 — GitHub Pages (recomendada, habilita PWA)

1. Hacé fork de este repositorio
2. Activá **GitHub Pages** en `Settings → Pages → Branch: main / root`
3. Entrá a `https://tu-usuario.github.io/bernitech-rider/`
4. En Chrome/Edge: menú → *"Instalar aplicación"* o *"Agregar a pantalla de inicio"*

### Opción 2 — Archivo local

Descargá `bernitech-rider.html` y abrilo directamente en el navegador.  
> ⚠️ En modo local la PWA no se puede instalar (requiere HTTPS). El resto funciona normalmente.

---

## 📋 Cómo armar tu rider

| Paso | Qué hacer |
|------|-----------|
| 1 | Completá los datos del evento (pestaña **Evento**) |
| 2 | Agregá los canales de input con micrófono y pie (pestaña **Inputs**) |
| 3 | Sumá los monitores necesarios |
| 4 | Armá el plano del escenario arrastrando los músicos (pestaña **Escenario**) |
| 5 | Configurá portada, logo y banner (pestaña **Diseño**) |
| 6 | Exportá el PDF desde la pestaña **Vista Previa** |

---

## 🛠️ Tecnología

- HTML5 + CSS3 + JavaScript vanilla — **sin dependencias externas**
- Progressive Web App (Manifest + Service Worker)
- IndexedDB para autosave persistente
- Web Speech API para dictado por voz
- Blob URL para exportación PDF sin popups bloqueados

---

## 📁 Estructura

```
bernitech-rider.html   ← app completa en un solo archivo
README.md
LICENSE
```

Todo en un único archivo HTML autocontenido. Los assets (íconos de instrumentos) están embebidos en base64.

---

## 🤝 Contribuciones

¡Bienvenidas! Abrí un issue o un pull request.  
Áreas donde se puede mejorar: más instrumentos, más idiomas, temas de color adicionales.

---

## 📄 Licencia

MIT © BerniTech — libre para usar, modificar y distribuir.

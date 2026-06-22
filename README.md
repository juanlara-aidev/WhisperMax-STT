<div align="center">

# WhisperMax

**Dictado por voz nativo para macOS — un beneficio de la comunidad [SinergIA](https://snrgia.ai).**

Mantén una tecla, habla, suéltala. El texto aparece escrito —limpio y pulido— justo donde tenías el cursor, en menos de medio segundo. Sin ventanas, sin copiar y pegar, sin perder el foco de lo que estás haciendo.

</div>

---

## ✨ Qué hace

- 🎙️ **Dictado global**: mantén **⌘ derecho**, habla, suéltala y el texto se escribe solo en cualquier app.
- 🔒 **Tú eliges cómo transcribir**: **100% local y offline** (privado, en tu Mac) o **en la nube con Groq** (tu propia API key).
- ✨ **Limpieza con IA** opcional: quita muletillas y arregla la puntuación automáticamente.
- 📖 **Diccionario propio**: enseña a WhisperMax tus nombres, marcas y términos para que los escriba bien.
- 🪶 **Vive en la barra de menú**, sin ícono en el Dock, sin estorbar.

---

## ✅ Requisitos

- **macOS 14 (Sonoma) o más nuevo**
- **Mac con Apple Silicon** (M1 o posterior)
- **Membresía activa de SinergIA** — WhisperMax es un beneficio de la comunidad: inicias sesión una vez y el dictado se desbloquea para miembros activos.

---

## 🚀 Instalación rápida (recomendada)

Copia esta línea, pégala en la app **Terminal** y presiona **Enter**:

```bash
curl -fsSL https://github.com/juanlara-aidev/WhisperMax-STT/releases/latest/download/install-whispermax.sh | bash
```

Eso descarga WhisperMax, lo instala en tus Aplicaciones y lo abre — **sin ningún aviso de seguridad de Apple**. Listo.

> ¿No sabes dónde está la Terminal? Presiona `⌘ + barra espaciadora`, escribe **Terminal**, Enter. Luego pega la línea de arriba.

---

## 🧩 Instalación manual (alternativa)

Si prefieres no usar la Terminal para todo:

1. **Descarga** [`WhisperMax.dmg`](https://github.com/juanlara-aidev/WhisperMax-STT/releases/latest/download/WhisperMax.dmg) desde el [último release](https://github.com/juanlara-aidev/WhisperMax-STT/releases/latest).
2. Ábrelo y **arrastra WhisperMax a la carpeta Aplicaciones**.
3. Como la app no está notarizada por Apple, la primera vez macOS la bloquea. Para destrabarla, pega esta línea en la Terminal y Enter:

   ```bash
   xattr -dr com.apple.quarantine /Applications/WhisperMax.app && open /Applications/WhisperMax.app
   ```

---

## 👋 Primer uso

1. **Inicia sesión en SinergIA**: se abre tu navegador; si ya tienes sesión ahí, solo confirmas (la app nunca ve tu contraseña).
2. **Elige cómo transcribir**: **Local** (privado; descarga el modelo una vez, ~1.5 GB, con barra de progreso) o **Nube** (Groq, sin descarga — necesitas pegar tu API key en Ajustes).
3. **Concede los permisos** que te pide (Micrófono, Accesibilidad y Monitorización de entrada). Es posible que tengas que reabrir la app una vez.
4. **A dictar**: mantén **⌘ derecho**, habla, suéltala. El texto aparece donde tengas el cursor.

Para cambiar de vía, activar la limpieza con IA o editar tu diccionario: ícono de WhisperMax en la barra de menú → **Ajustes…**.

---

## 🐛 Reportar un problema

¿Algo no funciona o tienes una sugerencia? Abre un issue en GitHub:

**[github.com/juanlara-aidev/WhisperMax-STT/issues](https://github.com/juanlara-aidev/WhisperMax-STT/issues)**

Para ayudarnos a resolverlo más rápido, incluye:
- Tu versión de macOS y el modelo de tu Mac (Apple Silicon / Intel).
- Qué intentabas hacer y qué pasó.
- Si aplica, el mensaje de error exacto.

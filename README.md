# ⏱️ Control de Tiempo de Estudio

Aplicación web para registrar y gestionar el tiempo dedicado a estudiar diferentes asignaturas y actividades académicas.

## 📋 Descripción

Esta herramienta te permite crear múltiples cronómetros simultáneos para llevar un registro preciso del tiempo que dedicas a cada asignatura y actividad específica. Ideal para estudiantes universitarios que necesitan controlar su tiempo de estudio y exportar los datos a Excel.

## ✨ Características

- ⏱️ **Múltiples cronómetros simultáneos** - Crea tantos cronómetros como necesites
- ▶️ **Control completo** - Iniciar, pausar y detener cada cronómetro de forma independiente
- 📊 **Estadísticas en tiempo real** - Visualiza sesiones totales, tiempo acumulado y sesión más larga
- 💾 **Guardado automático** - Las sesiones se guardan automáticamente al detener el cronómetro
- 📥 **Exportación a CSV** - Descarga tus registros en formato compatible con Excel
- 📝 **Autocompletado inteligente** - Sugerencias de asignaturas ya utilizadas
- 🎨 **Interfaz moderna** - Diseño oscuro y minimalista

## 🚀 Cómo usar la aplicación

### Método 1: Abrir directamente desde GitHub (Recomendado)

1. Ve al repositorio en GitHub
2. Haz clic en el archivo `index.html`
3. Haz clic en el botón **"Raw"** (arriba a la derecha del código)
4. Guarda la página web (Ctrl+S o Cmd+S) con el nombre `index.html`
5. Abre el archivo guardado con tu navegador (doble clic)

### Método 2: Clonar el repositorio

git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio

Luego abre `index.html` con tu navegador favorito.

### Método 3: GitHub Pages (Para acceso online)

1. Ve a **Settings** de tu repositorio
2. En el menú lateral, haz clic en **Pages**
3. En **Source**, selecciona la rama `main` o `master`
4. Haz clic en **Save**
5. Espera unos minutos y accede a: `https://tu-usuario.github.io/tu-repositorio/`

## 📖 Guía de uso

### 1. Crear un cronómetro

1. Escribe el nombre de la **Asignatura** (ej: "ASD", "SIE", "MASI")
2. Especifica la **Actividad** (ej: "Lección 1", "Laboratorio", "Trabajo")
3. Haz clic en **"Crear Cronómetro"**

### 2. Controlar el cronómetro

- **▶️ Iniciar**: Comienza a contar el tiempo
- **⏸️ Pausar**: Pausa temporalmente (puedes reanudar después)
- **⏹️ Detener y Guardar**: Finaliza la sesión y guarda el registro
- **🗑️ Eliminar**: Borra el cronómetro y todas sus sesiones

### 3. Exportar datos a Excel

1. Haz clic en **"⬇️ Descargar CSV"**
2. Abre el archivo CSV descargado con Excel
3. Copia los datos a tu hoja de cálculo de seguimiento

El CSV incluye:
- Asignatura
- Actividad
- Fecha y hora de la sesión
- Duración formateada (hh:mm:ss)
- Duración en minutos (para cálculos)

## 📊 Integración con Excel

Si tienes un Excel con tus asignaturas y actividades (como en el ejemplo del proyecto):

**Hoja 1**: Asignaturas con evaluaciones y horarios
**Hoja 2**: Registro de tiempo por actividad

El CSV exportado te permite copiar fácilmente las fechas y tiempos a tu Hoja 2 para mantener un registro completo.

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3 (Variables CSS, Flexbox, Grid)
- JavaScript (ES6+)
- No requiere instalación ni dependencias externas

## 💡 Consejos de uso

- **Usa nombres consistentes** para las asignaturas (ej: siempre "ASD" en lugar de "Algoritmos")
- **Detén y guarda** las sesiones al finalizar para que se registren correctamente
- **Exporta regularmente** tus datos para no perderlos (los datos se guardan solo en tu navegador)
- **Pausa el cronómetro** si te interrumpen para mantener registros precisos

## 🔒 Privacidad

Todos los datos se almacenan **localmente en tu navegador**. La aplicación no envía información a ningún servidor externo. Tus datos son completamente privados.

**Nota importante**: Si limpias los datos del navegador o usas modo incógnito, perderás los cronómetros activos. Exporta tus datos regularmente.

## 🐛 Solución de problemas

**Los cronómetros desaparecen al cerrar el navegador**
- Esto es normal. Exporta tus datos antes de cerrar o usa el navegador normalmente (no en modo incógnito).

**El CSV no se abre correctamente en Excel**
- Asegúrate de que Excel esté configurado para usar la coma (,) como separador.
- Puedes usar "Datos > Desde texto/CSV" en Excel para importar correctamente.

**La app no guarda mis sesiones**
- Recuerda hacer clic en "⏹️ Detener y Guardar" para registrar cada sesión.

## 📝 Estructura del proyecto

proyecto/
├── index.html          # Aplicación completa (HTML + CSS + JS)
└── README.md          # Este archivo

## 👥 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún bug o tienes sugerencias de mejora:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -m 'Añade nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de uso libre para fines educativos y personales.

## 🎓 Proyecto creado para

Control de tiempo de estudio de asignaturas universitarias:
- ASD (Algoritmos y Estructuras de Datos)
- SIE (Sistemas de Información Empresarial)
- SI (Sistemas Inteligentes)
- AIA (Aprendizaje e Inferencia Automática)
- MASI (Modelado y Análisis de Sistemas de Información)

---

**¿Necesitas ayuda?** Abre un issue en el repositorio o contacta con el desarrollador.

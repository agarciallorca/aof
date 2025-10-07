# ACTIVIDAD: COMBINACIÓN DE CORRESPONDENCIA
## Email de Confirmación - Torneo Esports 2025

---

## 📚 FICHA TÉCNICA DE LA ACTIVIDAD

- **Duración:** 2 sesiones (50 min cada una)
- **Nivel:** ESO/Bachillerato/FP
- **Software:** LibreOffice Writer + Calc (o Microsoft Word + Excel)
- **Agrupamiento:** Individual o parejas

---

## 🎯 OBJETIVOS DE APRENDIZAJE

Al finalizar la actividad, el alumnado será capaz de:

1. Crear una base de datos estructurada correctamente
2. Identificar qué campos necesita un documento
3. Vincular un documento Writer con una fuente de datos
4. Insertar campos de combinación en posiciones correctas
5. Previsualizar y generar documentos personalizados
6. Exportar el resultado final

---

## 📋 SESIÓN 1: PREPARACIÓN DE DATOS Y DOCUMENTO BASE

### PARTE A: Crear la base de datos (20 min)

**PASO 1:** Abre LibreOffice Calc (o Excel)

**PASO 2:** Crea esta tabla con **exactamente estos nombres de columna** (sin tildes, sin espacios):

| Nickname | Nombre | Apellidos | Email | Juego | Equipo | Rango | Fecha_Torneo | Hora | Sala |
|----------|--------|-----------|-------|-------|--------|-------|--------------|------|------|

**PASO 3:** Rellena con **AL MENOS 8 participantes** inventados. Ejemplo:

| Nickname | Nombre | Apellidos | Email | Juego | Equipo | Rango | Fecha_Torneo | Hora | Sala |
|----------|--------|-----------|-------|-------|--------|-------|--------------|------|------|
| ShadowKill | Carlos | García López | carlos.garcia@email.com | Valorant | Night Wolves | Platino | 15/11/2025 | 16:00 | Sala Gaming A |
| LunaPro | Laura | Martínez Ruiz | laura.martinez@email.com | League of Legends | Phoenix Team | Oro | 15/11/2025 | 17:00 | Sala Gaming B |
| DragonSlayer | Miguel | Fernández Soto | miguel.fernandez@email.com | Fortnite | Solo | Diamante | 15/11/2025 | 16:30 | Sala Gaming A |
| QueenGamer | Ana | López Moreno | ana.lopez@email.com | Valorant | Valkyries | Oro | 15/11/2025 | 18:00 | Sala Gaming C |
| ElitePro99 | David | Sánchez Gil | david.sanchez@email.com | CS2 | Elite Squad | Global | 16/11/2025 | 16:00 | Sala Gaming A |
| NinjaStar | Paula | Rodríguez Vega | paula.rodriguez@email.com | League of Legends | Solo | Platino | 16/11/2025 | 17:30 | Sala Gaming B |
| ThunderBolt | Javier | Gómez Prieto | javier.gomez@email.com | FIFA 24 | Thunder FC | División 2 | 16/11/2025 | 16:00 | Sala Gaming C |
| PhoenixFire | Marta | Díaz Torres | marta.diaz@email.com | Fortnite | Phoenix Rising | Campeón | 16/11/2025 | 18:30 | Sala Gaming A |

**PASO 4:** Guarda el archivo como: `inscritos_torneo.ods` (o `.xlsx`)

**⚠️ IMPORTANTE:**
- Primera fila = nombres de campos (encabezados)
- Sin filas vacías
- Sin combinar celdas

---

### PARTE B: Crear el documento de email (30 min)

**PASO 1:** Abre LibreOffice Writer (nuevo documento)

**PASO 2:** Escribe el siguiente texto (SIN los campos aún, solo el texto):

```
Para: [aquí irá el email]
Asunto: ✅ ¡Inscripción confirmada al Torneo Esports 2025!

─────────────────────────────────────────

Hola [nickname],

¡Bienvenido/a al Torneo Esports 2025!

Tu inscripción ha sido confirmada con los siguientes datos:

👤 DATOS DEL JUGADOR:
   Nombre completo: [nombre] [apellidos]
   Alias: [nickname]
   Email de contacto: [email]

🎮 DATOS DE COMPETICIÓN:
   Juego: [juego]
   Equipo: [equipo]
   Nivel/Rango actual: [rango]

📅 CONVOCATORIA:
   Día: [fecha]
   Hora de inicio: [hora]
   Ubicación: [sala]

⚠️ RECUERDA:
   ✓ Llega 15 minutos antes de tu hora
   ✓ Trae tu DNI o documento de identificación
   ✓ Si juegas en PC, puedes traer tu propio teclado/ratón/auriculares
   ✓ Consulta las reglas completas en: www.torneoesports2025.com

🏆 ¡Nos vemos en el torneo, [nickname]! Que gane el mejor.

Mucha suerte,
Equipo organizador
Torneo Esports 2025

─────────────────────────────────────────
```

**PASO 3:** Dale formato atractivo:
- Título en negrita y color
- Emojis (si quieres)
- Espaciado entre secciones

**PASO 4:** Guarda como: `email_confirmacion.odt` (o `.docx`)

---

## 📧 SESIÓN 2: COMBINACIÓN DE CORRESPONDENCIA

### PARTE C: Vincular la base de datos (15 min)

**En LibreOffice Writer:**

**PASO 1:** Menú → **Herramientas** → **Asistente para combinar correspondencia**

O también:

**PASO 1 (alternativo):** Menú → **Ver** → **Fuentes de datos** (F4)

**PASO 2:** Menú → **Archivo** → **Asistentes** → **Fuente de datos de direcciones**

**PASO 3:** Selecciona "Otra fuente de datos externa"

**PASO 4:** Busca y selecciona tu archivo `inscritos_torneo.ods`

**PASO 5:** Verifica que se vean todos los registros en la parte superior de la pantalla

---

### PARTE D: Insertar campos de combinación (20 min)

**PASO 1:** Coloca el cursor donde pone `[aquí irá el email]`

**PASO 2:** Menú → **Insertar** → **Campos** → **Otros** (Ctrl+F2)

**PASO 3:** Pestaña **Base de datos** → Selecciona el campo **Email** → botón **Insertar**

**PASO 4:** Repite para cada campo:
- `[nickname]` → insertar campo **Nickname**
- `[nombre]` → insertar campo **Nombre**
- `[apellidos]` → insertar campo **Apellidos**
- `[email]` → campo **Email**
- `[juego]` → campo **Juego**
- `[equipo]` → campo **Equipo**
- `[rango]` → campo **Rango**
- `[fecha]` → campo **Fecha_Torneo**
- `[hora]` → campo **Hora**
- `[sala]` → campo **Sala**

**💡 TRUCO:** Los campos insertados aparecerán con **fondo gris** cuando haces clic en ellos.

---

### PARTE E: Previsualizar y generar (15 min)

**PASO 1: Previsualizar**
- Usa las flechas en la barra de herramientas para navegar entre registros
- Verifica que todos los datos se muestran correctamente
- Comprueba que no hay errores de formato

**PASO 2: Generar documentos**

**Opción A - Documento único con todos los emails:**
- Menú → **Herramientas** → **Asistente para combinar correspondencia**
- Elegir "Documento"
- Se creará un documento con todos los emails separados por saltos de página

**Opción B - Emails individuales:**
- Guardar como PDF individuales
- O imprimir directamente

**PASO 3:** Guarda el resultado final

---

## ✅ CRITERIOS DE EVALUACIÓN

| Criterio | Puntos | Descripción |
|----------|--------|-------------|
| **Base de datos** | 2 pts | Estructura correcta, mínimo 8 registros, sin errores |
| **Documento base** | 2 pts | Formato atractivo, texto correcto, bien organizado |
| **Vinculación** | 2 pts | Base de datos correctamente vinculada |
| **Campos insertados** | 2 pts | Todos los campos en posición correcta |
| **Resultado final** | 1.5 pts | Previsualización correcta, sin errores |
| **Presentación** | 0.5 pts | Limpieza, creatividad, profesionalidad |
| **TOTAL** | **10 pts** | |

---

## 🎯 RÚBRICA DETALLADA

### Excelente (9-10):
- Base de datos perfecta con más de 10 registros
- Formato muy atractivo y profesional
- Todos los campos correctos
- Creatividad en el diseño

### Notable (7-8):
- Base de datos correcta con 8-10 registros
- Formato correcto y ordenado
- Campos correctos con algún error menor

### Aprobado (5-6):
- Base de datos con errores menores
- Formato básico pero funcional
- Algunos campos incorrectos o faltantes

### Insuficiente (<5):
- Base de datos con errores graves
- No consigue vincular o insertar campos
- Resultado no funcional

---

## 💡 CONSEJOS PARA EL PROFESORADO

### Errores comunes del alumnado:

1. **Nombres de columnas con espacios o tildes** → No funcionan bien
   - ❌ "Fecha de Torneo"
   - ✅ "Fecha_Torneo"

2. **Filas vacías en la base de datos** → Genera emails en blanco

3. **No actualizar campos** → Mostrar cómo refrescar con F9

4. **Formato perdido** → Explicar que el formato se aplica ANTES de insertar campos

5. **Confusión entre "campo" y "texto"** → Los campos tienen fondo gris al hacer clic

---

## 🚀 EXTENSIONES Y VARIACIONES

### Para alumnado avanzado:

**1. Añadir campos condicionales:**
```
«IF Equipo = "Solo" "Competirás individualmente" "Competirás con tu equipo"»
```

**2. Personalizar el saludo:**
```
«IF Nombre = "Carlos" "Hola crack" "Hola campeón/a"»
```

**3. Añadir imágenes personalizadas** según el juego

**4. Crear etiquetas para carnets** de participante

**5. Generar QR codes** con los datos de cada participante

---

### Para adaptar dificultad:

**Nivel BÁSICO:**
- Solo 4-5 campos
- Base de datos ya creada (se la das tú)
- Plantilla de email ya formateada

**Nivel MEDIO:**
- 8-10 campos
- Crean ellos la base de datos
- Diseñan el email

**Nivel AVANZADO:**
- Campos condicionales
- Múltiples documentos (email + diploma)
- Exportar a diferentes formatos

---

## 📦 ENTREGABLES

El alumnado debe entregar:

1. ✅ Archivo `inscritos_torneo.ods` con los datos
2. ✅ Archivo `email_confirmacion.odt` con campos insertados
3. ✅ Archivo `emails_generados.pdf` con todos los emails combinados
4. ✅ Captura de pantalla de la previsualización

---

## 📝 NOTAS ADICIONALES

### Recursos adicionales:
- Tutorial oficial de LibreOffice sobre combinación de correspondencia
- Vídeos explicativos en el aula virtual
- Ejemplos de otros documentos (diplomas, carnets, etiquetas)

### Temporalización sugerida:
- **Sesión 1 (50 min):** Creación de base de datos y documento base
- **Sesión 2 (50 min):** Vinculación, inserción de campos y generación

### Competencias trabajadas:
- Competencia digital
- Competencia lingüística (redacción profesional)
- Aprender a aprender (seguir procedimientos)
- Iniciativa y emprendimiento (aplicación práctica)

---

*Actividad diseñada para gamificar el aprendizaje de combinación de correspondencia*
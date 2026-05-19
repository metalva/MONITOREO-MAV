# MONITOREO MAV

## Panel de Control para Monitoreo de Agua y Presión

Panel interactivo con autenticación para monitorear dos sistemas independientes de agua y presión, con alarmas visuales y manómetros digitales.

### Características

✨ **Funcionalidades principales:**
- 🔐 Autenticación de usuario
- 🚨 Sistema de alarmas visuales (indicadores LED)
- 📊 Manómetros digitales con control de presión (0-10 bar)
- 📱 Código QR generado dinámicamente
- 🔗 Visualización de URL accesible
- 📋 Copiar URL al portapapeles

### Cómo usar

1. **Ejecutar el servidor local:**
   - Haz doble clic en `iniciar_servidor.bat`
   - Se abrirá el servidor en `http://localhost:8000`

2. **Iniciar sesión:**
   - Usuario: `mav`
   - Contraseña: `1234_mav`

3. **Usar el panel:**
   - Activar/desactivar alarmas para cada sistema
   - Ingresar valores de presión (0-10 bar) y aplicar
   - Ver URL y escanear código QR

### Estructura del proyecto

```
MONITOREO-MAV/
├── index.html              # Página principal del panel
├── iniciar_servidor.bat    # Script para iniciar servidor local
├── mav-img.png            # Logo del sistema
└── README.md              # Este archivo
```

### Tecnologías utilizadas

- **HTML5** - Estructura
- **CSS3** - Estilos y animaciones
- **JavaScript** - Lógica interactiva
- **QRCode.js** - Generación de códigos QR
- **Python** - Servidor web local

### Credenciales por defecto

| Campo | Valor |
|-------|-------|
| Usuario | mav |
| Contraseña | 1234_mav |

### Autor

Creado con ❤️ para monitoreo de sistemas MAV

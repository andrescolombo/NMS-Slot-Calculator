# NMS Slot Calculator

Una calculadora de layout de slots para No Man's Sky que te ayuda a optimizar la disposición de módulos para obtener las mejores estadísticas.

## 🚀 Características

- **Grid de slots interactivo** - Arrastra y suelta módulos para crear tu layout
- **Cálculo automático de estadísticas** - Ve las estadísticas totales en tiempo real
- **Bonificaciones adyacentes** - Los módulos del mismo grupo obtienen bonos cuando están juntos
- **Categorización completa** - Todos los módulos del juego organizados por categorías
- **Exportar/Importar layouts** - Guarda y comparte tus configuraciones favoritas

## 🎮 Cómo Usar

1. **Selecciona una categoría** (Mining, Combat, etc.) en el dropdown izquierdo
2. **Elige un grupo** de módulos en el segundo dropdown
3. **Arrastra módulos** al grid de slots para colocarlos
4. **Ve las estadísticas** que se calculan automáticamente
5. **Hover sobre módulos** para ver estadísticas individuales y bonos adyacentes

## 🛠️ Instalación Local

```bash
# Clonar el repositorio
git clone https://github.com/andrescolombo/NMS-Slot-Calculator.git

# Navegar al directorio
cd NMS-Slot-Calculator

# Iniciar servidor HTTP local
python -m http.server 8080

# Abrir en el navegador
# http://localhost:8080
```

## 📊 Tipos de Estadísticas

- **(+)** Estadísticas **Aditivas**: Se suman directamente (ej: +100 de escudo)
- **(*)** Estadísticas **Multiplicativas**: Se multiplican entre sí (ej: +20% tasa de disparo)

## 🎯 Consejos de Optimización

- **Agrupa módulos similares** para obtener bonificaciones adyacentes
- **Usa patrones cuadrados** para armas (2x2 o 3x3)
- **Combina estadísticas aditivas y multiplicativas** para máximo impacto
- **Experimenta con diferentes layouts** para encontrar la configuración óptima

## 🔧 Tecnologías

- HTML5, CSS3, JavaScript
- jQuery y jQuery UI para interactividad
- JSON para datos de módulos
- Servidor HTTP local para desarrollo

## 📝 Notas

- Basado en el repositorio original de [Ket/NMS-SlotLayout](https://github.com/Ket/NMS-SlotLayout)
- Actualizado con datos de módulos más recientes
- Optimizado para la versión actual de No Man's Sky

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras errores o tienes mejoras, no dudes en crear un issue o pull request.

---

**¡Disfruta optimizando tus naves y herramientas en No Man's Sky!** 🚀

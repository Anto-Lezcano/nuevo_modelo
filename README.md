# 📊 Modelo de Predicción para Función Cuadrática Inversa

**Predice valores de x para y = 2x² - 3x + 1 usando TensorFlow.js**

## 🌟 Características principales

- 🧠 Modelo de red neuronal entrenado en el navegador
- 🔄 Resuelve la función cuadrática inversamente (y → x)
- 📱 Interfaz responsive y amigable
- 📊 Comparación con soluciones analíticas exactas
- ⚡ Entrenamiento en tiempo real con visualización de progreso

## 🚀 Cómo ejecutarlo

1. Clona el repositorio
2. Abre `index.html` en tu navegador web
3. Espera a que el modelo termine de entrenar (≈30 segundos)
4. Ingresa valores de y y obtén las predicciones de x

## 🧠 Detalles del modelo

| Parámetro              | Valor                     |
| ---------------------- | ------------------------- |
| Arquitectura           | 20-20-1 (2 capas ocultas) |
| Función de activación  | ReLU                      |
| Optimizador            | Adam (lr=0.01)            |
| Épocas                 | 50                        |
| Tamaño de lote         | 32                        |
| Muestras entrenamiento | 10,000                    |

## 💡 Ejemplo de uso

```javascript
// Para y = 15, el modelo predice:
≈ 3.1354 (predicción)
≈ 3.1375 y -2.1375 (solución exacta)
```

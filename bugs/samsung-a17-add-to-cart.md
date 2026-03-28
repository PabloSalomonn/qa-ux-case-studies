# 🐞 Bug - Samsung Galaxy A17 5G

## 📋 Descripción
Durante la navegación en el listado de productos, el botón **"Agregar al carrito"**
se activa de forma accidental al realizar scroll vertical.

El problema ocurre con alta frecuencia en este dispositivo, generando múltiples
adiciones no intencionales al carrito en una misma sesión.

No existe una opción inmediata para deshacer la acción, lo que obliga al usuario
a interrumpir su navegación para corregir errores.

---

## 🔁 Pasos para reproducir
1. Abrir la aplicación
2. Buscar cualquier producto
3. Ingresar a un listado de resultados
4. Realizar scroll vertical (lento y rápido)
5. Observar la interacción con los botones

---

## ❌ Resultado actual
- Alta frecuencia de productos agregados sin intención
- Posibilidad de múltiples errores en poco tiempo
- No existe opción de deshacer
- Usuario debe ingresar al carrito para eliminar productos

---

## ✅ Resultado esperado
- El scroll no debe activar taps accidentalmente
- El botón debe requerir una interacción intencional clara
- Debe existir una opción de **"Deshacer"**
- El usuario no debería salir del listado para corregir errores

---

## 📊 Frecuencia
Alta

---

## ⚠️ Impacto
- Alta frustración del usuario
- Interrupción constante del flujo de compra
- Mayor riesgo de abandono

---

## 🧠 Análisis QA
- La sensibilidad táctil del dispositivo amplifica el problema
- El botón está ubicado en una zona crítica (área de scroll)
- No existe separación clara entre gesto y acción
- Falta mecanismo de recuperación (undo)

---

## 📱 Ambiente
- Dispositivo: Samsung Galaxy A17 5G
- Sistema operativo: Android 16
- Versión app: X.X.X





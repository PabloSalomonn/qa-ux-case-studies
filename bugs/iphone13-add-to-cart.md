# 🐞 Bug - iPhone 13

## 📋 Descripción
Durante la navegación en el listado de productos, el botón **"Agregar al carrito"**
puede activarse accidentalmente al realizar scroll vertical.

El problema ocurre de forma intermitente en este dispositivo, generando
adiciones no intencionales al carrito en algunos casos.

No existe una opción inmediata para deshacer la acción, obligando al usuario
a ingresar al carrito para corregir errores.

---

## 🔁 Pasos para reproducir
1. Abrir la aplicación
2. Buscar cualquier producto
3. Ingresar a un listado de resultados
4. Realizar scroll vertical (lento y rápido)
5. Observar la interacción con los botones

---

## ❌ Resultado actual
- Productos se agregan al carrito sin intención
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
Media

---

## ⚠️ Impacto
- Fricción en la experiencia de usuario
- Interrupción del flujo de compra
- Posible frustración o abandono

---

## 🧠 Análisis QA
- El botón está ubicado en una zona crítica (área de scroll)
- No hay separación clara entre gesto de scroll y acción
- Falta mecanismo de recuperación inmediata (undo)

---

## 📱 Ambiente
- Dispositivo: iPhone 13
- Sistema operativo: iOS 26.3.1
- Versión app: Versión app: Mercado Libre para iOS versión 10.518.2

---

## 📎 Evidencia
- Video: iphone13-test.mp4
- Screenshots (opcional)


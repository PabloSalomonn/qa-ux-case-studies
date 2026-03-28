---
name: 🐞 Bug Report - QA Mobile
about: Reporta un bug o issue de UX / funcional en apps móviles con checklist
title: "[Dispositivo] Breve descripción del bug"
labels: bug, ux, mobile
assignees: 
---

## 📋 Descripción
Describe claramente el problema detectado. Explica qué sucede y por qué es un problema.

**Ejemplo:**  
El botón "Agregar al carrito" se activa accidentalmente durante el scroll vertical en listados de productos.

---

## 🔁 Pasos para reproducir
- [ ] Abrir la aplicación
- [ ] Buscar cualquier producto
- [ ] Ingresar a un listado de resultados
- [ ] Realizar scroll vertical (lento y rápido)
- [ ] Observar la interacción con los botones
- [ ] Repetir en ambos dispositivos si aplica

---

## ❌ Resultado actual
- [ ] Describe qué ocurre realmente
- [ ] Productos se agregan al carrito sin intención
- [ ] No hay opción de deshacer
- [ ] Usuario debe ir al carrito para eliminar productos

---

## ✅ Resultado esperado
- [ ] El scroll no activa taps accidentalmente
- [ ] Botón requiere interacción intencional
- [ ] Debe existir opción de **"Deshacer"**
- [ ] Usuario no debe salir del listado para corregir errores

---

## 📊 Frecuencia
- [ ] Baja / Media / Alta
- [ ] (Opcional: número de veces por sesión o % de ocurrencia)

---

## ⚠️ Impacto
- [ ] Fricción en la experiencia de usuario
- [ ] Interrupción del flujo de compra
- [ ] Posible abandono del flujo de compra

---

## 🧠 Análisis QA
- [ ] Botón en zona crítica de scroll
- [ ] Diferencias de sensibilidad táctil según dispositivo
- [ ] Falta mecanismo de recuperación inmediata (undo)
- [ ] Logs o métricas relevantes si aplica

---

## 📱 Dispositivo y ambiente
- Dispositivo: iPhone 13 / Samsung Galaxy A17 5G / otro
- Sistema operativo: iOS XX / Android XX
- Versión app: X.X.X
- Red: Wi-Fi / Datos móviles (opcional)

---

## 📎 Evidencia
- Video: `nombre_video.mp4`
- Screenshots: marcar ubicación del botón, errores, etc.

---

## 💡 Notas adicionales
Cualquier información extra útil: diferencias entre dispositivos, métricas aproximadas (% taps accidentales, tiempo perdido), sugerencias de mejora.

---

## ✅ Checklist QA opcional
- [ ] Reproducido en ambos dispositivos
- [ ] Se verificó tamaño de hit area (≥44px)
- [ ] Se verificó flujo de recuperación / undo
- [ ] Se grabó evidencia (video o screenshot)
- [ ] Se documentó versión de app y OS

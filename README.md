# Sección: ¿Tienes algo que aportar? ¡Súmate!

Esta sección permite que cualquier persona interesada en compartir su experiencia o conocimiento se postule como “sabio” dentro del proyecto **Adopta un Sabio**. Incluye un formulario totalmente funcional conectado a Google Sheets.

## 🎯 Objetivo

Recopilar datos de personas dispuestas a integrarse como sabios en el proyecto, para posteriormente ser evaluadas por el equipo administrador.

## 📋 Campos del formulario

- **nombre** (obligatorio)
- **edad** (obligatorio)
- **area_conocimiento** (obligatorio)
- **email** (obligatorio)
- **telefono** (obligatorio, validado a 10 dígitos)
- **fecha** (con calendario)
- **captcha dinámico** tipo suma con verificación visual ✅

## ✅ Funcionalidades

- Validación completa de campos obligatorios
- Captcha con verificación en tiempo real
- Botón dinámico: “¡Súmate!” → “Cerrar formulario”
- Envío automático a hoja de cálculo `CONSULTAS`, pestaña `SUMATE`
- El campo `estatus` se agrega automáticamente como `"Pendiente"`
- Mensaje de éxito al enviar correctamente
- Se limpia el formulario tras enviar
- El mensaje de éxito se oculta al cerrar el formulario

## 🔗 Conexión activa

El formulario se conecta a través de Google Apps Script a esta URL:


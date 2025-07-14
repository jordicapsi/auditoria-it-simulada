# Auditoría simulada de accesos a sistemas

Este proyecto simula una auditoría IT sobre accesos de usuarios a un sistema corporativo ficticio. Su objetivo es detectar patrones de riesgo y proponer recomendaciones de mejora del control interno, aplicando técnicas de análisis de datos con Python.

---

## 📊 Objetivos

- Analizar eventos de acceso a sistemas (login, logout, intentos fallidos, cambios de configuración, etc.)
- Identificar riesgos como:
  - Accesos fuera de horario laboral
  - Actividad de cuentas inactivas
  - Fallos reiterados de autenticación
- Formular recomendaciones orientadas a la mejora de políticas de seguridad y control de accesos

---

## 📁 Estructura del proyecto

| Archivo                     | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `accesos_simulados.csv`    | Logs de accesos simulados: usuario, hora, acción, IP, éxito/fallo          |
| `usuarios.csv`             | Datos de usuarios: roles, departamento, estado activo/inactivo              |
| `auditoria_accesos.ipynb`  | Análisis completo en Python (Jupyter Notebook)                              |
| `README.md`                | Documentación del proyecto                                                  |

---

## ⚙️ Herramientas utilizadas

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Datos sintéticos generados para simulación
- Análisis orientado a pensamiento crítico y enfoque auditor

---

## 🧠 Análisis realizados

1. **Accesos fuera de horario laboral**  
   Detección de actividades entre las 20:00 y 07:00.

2. **Actividad de usuarios inactivos**  
   Revisión de cuentas desactivadas que han generado actividad posterior.

3. **Fallos de login por usuario**  
   Análisis de errores de autenticación, posibles intentos sospechosos o mal uso.

---

## ✅ Resultados clave

- 42 % de accesos fuera de horario habitual  
- Actividad significativa de un usuario inactivo (`u012`)  
- 61 intentos fallidos de login, con 5 usuarios concentrando la mayoría

---

## 🔐 Recomendaciones

- Bloqueo automático tras múltiples intentos fallidos
- Cierre efectivo de cuentas inactivas
- Alertas para accesos fuera de horario
- Auditorías periódicas de accesos y permisos

---

## 📌 Nota

Este proyecto se basa en datos totalmente simulados. El objetivo es demostrar competencias en análisis de datos, pensamiento crítico y enfoque técnico en contextos reales de auditoría IT y control interno.

---

Desarrollado por [Jordi Capsí](https://www.linkedin.com/in/jordi-capsi) • [Portfolio en GitHub](https://github.com/jordicapsi)

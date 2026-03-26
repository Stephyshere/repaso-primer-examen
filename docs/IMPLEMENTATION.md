# IMPLEMENTATION.md

## 1. Datos del Alumno

**Nombre completo:** [Escribe tu nombre aquí]

**Fecha:** [Fecha del examen]

**Repositorio GitHub:** [URL completa de tu repositorio]

---

## 2. Entorno LOCAL

### Descripción
[Breve descripción de qué servicios corren en LOCAL]

### Capturas de Ejecución

**Docker containers corriendo:**

![Docker PS Local](images/local-docker-ps.png)

**Frontend funcionando:**

![Frontend Local](images/local-frontend.png)

**Backend API funcionando:**

![Backend Local](images/local-backend-api.png)

### URLs de Acceso
- Frontend: `http://localhost:8081`
- Backend: `http://localhost:8080`
- PostgreSQL: `localhost:5432`

---

## 3. Entorno DEV

### Descripción
[Breve descripción de qué servicios corren en DEV]

### Configuración Neon

**Dashboard Neon:**

![Neon Database](images/dev-neon-dashboard.png)

**Connection String utilizado:**
```
postgresql://[usuario]:***@ep-xxxxx.neon.tech:5432/[database]
```

### Capturas de Ejecución

**Docker containers corriendo:**

![Docker PS Dev](images/dev-docker-ps.png)

**Aplicación funcionando vía Proxy:**

![Aplicación via Proxy](images/dev-proxy-app.png)

**API funcionando vía Proxy:**

![API via Proxy](images/dev-proxy-api.png)

### URLs de Acceso
- Aplicación (via proxy): `http://localhost`
- Frontend directo: `http://localhost:8081`
- Backend directo: `http://localhost:8080`

---

## 4. Despliegue en Render

### URLs Públicas de los Servicios

**Backend API:**
- URL: `https://stranger-backend-XXXXX.onrender.com`

**Frontend:**
- URL: `https://stranger-frontend-XXXXX.onrender.com`

**Proxy (Punto de entrada principal):**
- URL: `https://stranger-proxy-XXXXX.onrender.com`

### Capturas de Render

**Dashboard con listado de servicios:**

![Render Services](images/render-services.png)

**Variables de entorno - Backend:**

![Variables Backend](images/render-vars-backend.png)

**Variables de entorno - Proxy:**

![Variables Proxy](images/render-vars-proxy.png)

**Aplicación funcionando (URL pública):**

![App Funcionando](images/render-app-funcionando.png)

**API funcionando (URL pública):**

![API Funcionando](images/render-api-funcionando.png)

---

## 5. Notas Adicionales

**Aquí puedes detallar errores encontrados, decisiones técnicas importantes, o cualquier aspecto relevante de tu implementación.**

### Ejemplo 1

**Descripción:**
[Describe algún error, problema o decisión técnica importante]

**Captura (opcional):**

![Nota 1](images/nota-1.png)

---

### Ejemplo 2

**Descripción:**
[Describe algún error, problema o decisión técnica importante]

**Captura (opcional):**

![Nota 2](images/nota-2.png)

---

## 6. Reflexión Personal

**¿Qué te ha parecido el examen? ¿Qué has aprendido? ¿Qué ha sido lo más difícil?**

[Escribe aquí tu reflexión personal sobre el examen]

---

# Examen de Despliegue - Stranger Things API

Proyecto base para el examen de **Despliegue de Aplicaciones Web**.

## 📋 Descripción del Examen

Desplegar una API REST de personajes de Stranger Things con frontend en diferentes entornos.

**Tareas:**
- Configurar perfiles: **local**, **dev** y **prod** (Render)
- Implementar CRUD de personajes
- Conectar frontend con el backend
- Desplegar con Docker
- Configurar proxy para Render
- Documentar el despliegue

## 🗄️ Base de Datos

Tabla `characters` con campos: id, name, power, power_level, description

**Datos iniciales:** Eleven, Will Byers, Vecna, Demogorgon

## 📁 Estructura del Repositorio

Este repositorio contiene **backend y frontend juntos**, pero se recomienda:

**✅ Mejor práctica:** Repositorios separados
- `stranger-backend` - API REST (Spring Boot)
- `stranger-frontend` - Interfaz de usuario

**⚠️ Alternativa:** Todo en un repositorio
```
proyecto/
├── backend/
│   ├── src/
│   └── pom.xml
└── frontend/
    ├── src/
    └── package.json
```

## 🚀 Entornos

### Local
Desarrollo en tu máquina con PostgreSQL local

### Dev
Entorno de pruebas con Docker Compose

### Prod (Render)
Despliegue en producción con proxy configurado

## 🔧 Configuración Render

Recuerda configurar el **proxy** para que el frontend se comunique con el backend en producción.

## 📦 Tecnologías

- **Backend:** Spring Boot + JPA + PostgreSQL
- **Frontend:** HTML/CSS/JS (o React/Vue según implementes)
- **Despliegue:** Docker + Render

## 📝 Entrega

Completa los endpoints solicitados, configura los tres perfiles y documenta el despliegue.
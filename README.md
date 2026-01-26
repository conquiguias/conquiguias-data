# conquiguias-data

## 📦 Repositorio de Almacenamiento de Datos

Este repositorio contiene **EXCLUSIVAMENTE** los datos de la plataforma ConquiGuias World:

- `data/` - Formularios y configuraciones generales
- `evaluaciones/` - Resultados de exámenes por ID de formulario
- `respuestas/` - Asistencias registradas por usuario
- `images/` - Imágenes de especialidades, firmas y decoración

## 🎯 Propósito

Este repositorio está **separado del código** para evitar deploys innecesarios en Vercel.

- ✅ La API lee y escribe aquí mediante GitHub API
- ✅ Los commits aquí **NO disparan** ningún deployment
- ✅ Los datos persisten de forma segura y versionada

## 🚫 No hacer

- ❌ NO conectar este repo a Vercel
- ❌ NO agregar código aquí (usar el repo principal)
- ❌ NO editar archivos manualmente (la API lo hace automáticamente)

## 🔗 Repositorio de Código

El código de la aplicación está en: [conquiguias/conquiguias](https://github.com/conquiguias/conquiguias)

---

**Migrado desde:** `conquiguias/conquiguias` (25/01/2026)  
**Total de archivos migrados:** 112  
**Estructura preservada:** 100%

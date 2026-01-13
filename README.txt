SISTEMA CRM EDUCATIVO - COMPLEJO VIRTUAL EPE
============================================

DESCRIPCIÓN:
------------
Sistema de Gestión Educativa completo con múltiples roles (Administrador, Plantel, Director, Docente, Participante). Permite la gestión integral de instituciones educativas.

CARACTERÍSTICAS PRINCIPALES:
----------------------------
1. Interfaz multi-rol con permisos diferenciados
2. Gestión completa de:
   - Planteles educativos
   - Directores
   - Docentes
   - Participantes
   - Formaciones/cursos
   - Usuarios del sistema
3. Modo Online/Offline
4. Sincronización de datos
5. Sistema de respaldo automático
6. Generación de reportes (PDF/Excel)
7. Creación de carnets con QR
8. Actualización automática cada 60 segundos
9. Persistencia de datos en LocalStorage

CREDENCIALES DE ACCESO:
-----------------------
Usuario Administrador Principal:
- Email: pabloemiliorico24@gmail.com
- Contraseña: Perp.241
- Rol: Administrador

INSTALACIÓN Y USO:
------------------
1. Guardar el archivo HTML en cualquier carpeta
2. Abrir con cualquier navegador moderno (Chrome, Firefox, Edge)
3. Iniciar sesión con las credenciales de administrador
4. Crear los primeros planteles, directores, docentes, etc.
5. Crear usuarios para cada rol según sea necesario

ESTRUCTURA DE DATOS:
--------------------
El sistema almacena todos los datos en el localStorage del navegador con la clave "complejoVirtualEPE". Se crean respaldos automáticos con timestamp.

FUNCIONALIDADES POR ROL:
------------------------
1. ADMINISTRADOR:
   - Gestión completa de todas las entidades
   - Creación de usuarios para todos los roles
   - Acceso a todas las interfaces
   - Configuración del sistema
   - Generación de reportes
   - Reparación del sistema

2. PLANTEL:
   - Gestión de docentes del plantel
   - Gestión de participantes del plantel
   - Gestión de formaciones del plantel
   - Ver información del plantel
   - Crear nuevos docentes, participantes y formaciones

3. DIRECTOR:
   - Gestión de docentes del plantel
   - Gestión de participantes del plantel
   - Gestión de formaciones del plantel
   - Ver perfil personal
   - Crear nuevos docentes, participantes y formaciones

4. DOCENTE:
   - Ver formaciones asignadas
   - Ver participantes de sus formaciones
   - Ver perfil personal
   - Añadir participantes a sus formaciones

5. PARTICIPANTE:
   - Ver formaciones inscritas
   - Inscribirse a nuevas formaciones
   - Ver perfil personal
   - Darse de baja de formaciones

CONFIGURACIÓN:
--------------
- Intervalo de actualización: 60 segundos (configurable)
- Frecuencia de backup: Diaria (configurable)
- Modo conexión: Online/Offline

REPOSITORIO GITHUB:
-------------------
URL: https://github.com/BEATMORTISX/ComplejoVirtualEPE-SistemaCRM.git

NOTAS IMPORTANTES:
------------------
1. Los datos se guardan automáticamente en el navegador
2. El sistema funciona completamente offline
3. Se pueden importar/exportar datos mediante archivos JSON
4. Los carnets se generan en formato vertical (5.4 x 8.6 cm)
5. El botón GitHub solo está disponible para el administrador

VERSIÓN:
--------
v4.0.0 - Sistema CRM Educativo Completo

DESARROLLADO POR:
-----------------
Complejo Virtual EPE
© 2024 Todos los derechos reservados
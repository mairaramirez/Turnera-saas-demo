# Turnera SaaS Multi-Tenant

Aplicación web desarrollada para Innovum que permite a negocios gestionar reservas online mediante una página pública personalizada y un panel administrativo.

La plataforma fue diseñada para salones de belleza, peluquerías, centros estéticos, consultorios y cualquier negocio que necesite administrar turnos, empleados y servicios desde una única herramienta.

> Proyecto real desarrollado como solución SaaS para la gestión de turnos.
> El código fuente completo es privado.
> Se incluye documentación funcional, capturas del sistema y acceso a una instancia pública autorizada por el cliente.

---

## Caso de uso real

La plataforma se encuentra implementada en negocios reales.

Las capturas y el enlace incluidos en este repositorio corresponden a un cliente que autorizó expresamente la exhibición de la solución con fines de portfolio profesional.

🔗 Acceso público:

https://turnos.innovum.website/?tenant=alkimia

---

## Tecnologías utilizadas

### Frontend

- Next.js
- React
- TypeScript
- CSS Modules

### Backend

- API Routes de Next.js
- Node.js

### Base de Datos

- MySQL
- Prisma ORM

### Infraestructura

- Nginx
- PM2
- VPS Linux
- Cloudflare

---

## Funcionalidades principales

### Página pública de reservas

- Reserva de turnos online
- Selección de categoría
- Selección de servicio
- Selección de fecha
- Disponibilidad automática de horarios
- Confirmación de reserva
- Código único de turno

### Gestión de turnos

- Creación de turnos
- Modificación de turnos
- Cancelación de turnos
- Consulta por código de reserva

### Administración

- Dashboard administrativo
- Gestión de empleados
- Gestión de categorías
- Gestión de servicios
- Gestión de horarios
- Configuración general del negocio

### Personalización visual

- Logo personalizado
- Banner personalizado
- Colores configurables
- Tipografías configurables
- Temas visuales

### Sistema de roles

- Admin
- Manager
- Staff

### Arquitectura SaaS

- Multi-tenant
- Configuración independiente por cliente
- Branding personalizado por negocio

---

## Aspectos técnicos destacados

- Arquitectura multi-tenant
- Manejo de roles y permisos
- Gestión dinámica de disponibilidad
- Validación de reservas
- Persistencia con Prisma ORM
- Configuración visual por tenant
- Manejo de estados de turnos
- Diseño responsive para dispositivos móviles

---

## Mi participación

Participé en el diseño, desarrollo y evolución de la plataforma, trabajando sobre:

- Desarrollo de funcionalidades frontend y backend
- Implementación de APIs y lógica de negocio
- Modelado de datos con Prisma ORM
- Gestión de roles y permisos
- Sistema de reservas y disponibilidad
- Configuración visual multi-tenant
- Corrección de errores y mejoras evolutivas

---

## Capturas del sistema

### Página pública

![Home](screenshots/home-turn.png)

### Selección de horarios

![Horarios](screenshots/horarios.png)

### Confirmación de reserva

![Turno Confirmado](screenshots/turno-final.png)

### Dashboard administrativo

![Dashboard](screenshots/admin.png)

### Personalización visual

![Personalización](screenshots/page.png)

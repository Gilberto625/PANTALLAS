💈 Stylo Barber Connect — Documentación Completa de Módulos y Páginas del Sistema
(Frontend + Pantallas por Rol + Módulos + Flujos)

Este documento detalla todas las páginas, módulos y pantallas que se deben implementar para el sistema Stylo Barber Connect, basado en los requerimientos funcionales y no funcionales del documento oficial.

Su objetivo es servir como guía para desarrollar todo el frontend (web y móvil), definiendo rutas, componentes, vistas y módulos completos.

📁 Estructura General del Sistema

El sistema se compone de 4 roles distintos, cada uno con su propio conjunto de pantallas:

Cliente

Secretaria

Barbero

Administrador

También incluye pantallas públicas accesibles sin registrarse.

🌐 1. Páginas Públicas (sin sesión)
1.1 Inicio / Landing Page

Presentación del negocio

Beneficios

Botones de acción (Agendar / Iniciar sesión / Ver catálogo)

1.2 Catálogo de Servicios (público)

Lista de servicios

Tarjeta con: imagen, nombre, precio, duración

Botón “Ver detalles”

1.3 Detalle de Servicio

Descripción completa

Duración

Precio

Galería

Botón “Agendar cita” (redirige a login si no está autenticado)

1.4 Catálogo de Productos (público)

Lista de productos

Filtros por categoría

Ordenar por precio/popularidad

1.5 Detalle de Producto

Imágenes

Descripción

Precio

Disponibilidad

Botón “Agregar al carrito”

1.6 Login

Email/teléfono

Contraseña

Botón “¿Olvidaste tu contraseña?”

Login con Google y Facebook

1.7 Registro de Cliente

Formulario:

Nombre completo

Apellidos

Fecha de nacimiento

Teléfono

Correo

Contraseña + Confirmación

1.8 Recuperar contraseña

Solicitar correo

Formulario de nueva contraseña

👤 2. Módulo Cliente
2.1 Panel del Cliente (Dashboard)

Próxima cita

Historial rápido

Promociones activas

Accesos rápidos: agendar, productos, pedidos

2.2 Mi Perfil

Datos personales

Editar foto

Dirección

Teléfono

Preferencias de notificaciones

Botón para eliminar cuenta

2.3 Agendar Cita

Flujo:

Selección de servicio

Selección de barbero opcional

Calendario

Horarios disponibles

Anticipo si aplica

Pago

Confirmación

Pantallas:

Selección de servicio

Selección de barbero

Calendario interactivo

Resumen + pago

2.4 Mis Citas

Lista de citas programadas

Estados: pendiente, confirmada, en proceso, completada

Botones:

Reprogramar

Cancelar

Ver detalles

2.5 Reprogramar Cita

Calendario con disponibilidad

Cambio de barbero opcional

Confirmación

2.6 Historial de Citas

Citas anteriores

Valoraciones (opcional futuro)

2.7 Comprar Productos

Pantallas:

Catálogo completo

Carrito

Checkout

Selección de método de entrega

Pago (Mercado Pago, transferencia, tarjeta)

2.8 Apartado de Productos

Seleccionar productos

Elegir anticipo

Pagar

Ver apartados activos

Liquidar apartado

2.9 Mis Compras / Mis Pedidos

Estado del pedido (procesando, enviado, entregado)

Detalles del pedido

Factura / comprobante PDF

👩‍💼 3. Módulo Secretaria
3.1 Dashboard Secretaria

Citas del día

Agenda general

Confirmaciones pendientes

Ventas del día

3.2 Agenda Completa

Vistas:

Día

Semana

Mes

Acciones:

Crear cita manual

Editar cita

Cancelar cita

Mover cita (drag-and-drop opcional)

Asignar barbero y silla

Check-in

3.3 Registrar Cita Manual

Formulario:

Cliente

Servicio

Barbero

Fecha

Hora

Anticipo (si aplica)

Método de pago

3.4 Validación de Pagos por Transferencia

Lista de pagos pendientes

Ver comprobante

Validar / rechazar

Registrar motivo de rechazo

3.5 Ventas Presenciales

Agregar productos/servicios

Registrar pago

Generar comprobante

3.6 Inventario (vista parcial)

Ver existencias

Notificaciones de stock bajo

Registrar entrada

Registrar salida

Ajustes

3.7 Gestión de Catálogo de Productos (vista parcial)

Crear producto

Editar producto

Desactivar producto

Subir imágenes

3.8 Pedidos y Entregas

Ver pedidos activos

Cambiar estado (preparando → enviado → entregado)

Registrar incidencias

🧔‍♂️ 4. Módulo Barbero
4.1 Dashboard Barbero

Citas del día

Citas en tiempo real

Resumen de servicios realizados

4.2 Mi Agenda Personal

Vista diaria/semanal

Citas asignadas

Estado de cada cita

4.3 Gestión de Tiempos de Servicio

Duración de cada servicio

Actualizar tiempos

Guardar cambios

4.4 Notificaciones

Cliente llegó (check-in)

Nueva cita asignada

Cita reprogramada

👑 5. Módulo Administrador
5.1 Dashboard General

Widgets:

Ventas del día

Citas del día

Top servicios

Horarios de mayor demanda

Inventario bajo

5.2 Gestión de Empleados

Registrar empleado

Editar datos

Asignar rol

Ver disponibilidad

Días libres

Especialidades

5.3 Gestión de Servicios

Crear servicio

Editar servicio

Cambiar duración

Activar/desactivar

Eliminar

5.4 Gestión de Productos

Pantallas avanzadas:

Catálogo

Crear producto

Editar producto

Inventario completo

Entradas

Salidas

Ajustes

Alertas

5.5 Gestión de Citas (vista completa)

Agenda global

Configurar políticas:

anticipos

cancelaciones

horarios especiales

días festivos

5.6 Reportes y Métricas

Reportes:

Ventas (diarias/semanales/mensuales)

Ventas por servicio

Ventas por producto

Ventas por barbero

Clientes frecuentes

Horarios pico

Productos más vendidos

Exportar a PDF/Excel

5.7 Configuración General

Horarios de la barbería

Número de sillas

Porcentaje de anticipo

Políticas de cancelación

Promociones

Descuentos

🆘 6. Módulo de Soporte
6.1 FAQ
6.2 Base de conocimientos
6.3 Chat de soporte
6.4 Registrar ticket
6.5 Seguimiento de ticket
📌 Resumen de TODAS las Páginas (lista para frontend)
Páginas Públicas (8)

Inicio

Servicios

Detalle servicio

Productos

Detalle producto

Login

Registro

Recuperar contraseña

Cliente (15)

Dashboard cliente

Perfil

Editar perfil

Agendar: servicio

Agendar: barbero

Agendar: calendario

Agendar: resumen-pago

Mis citas

Reprogramar cita

Historial de citas

Carrito

Checkout

Mis pedidos

Apartados

Detalle pedido

Secretaria (10)

Dashboard secretaria

Agenda general

Crear cita manual

Editar cita

Validar transferencias

Registrar venta

Catálogo productos

Inventario

Pedidos

Entregas

Barbero (4)

Dashboard

Agenda personal

Tiempos de servicio

Notificaciones

Administrador (15)

Dashboard

Empleados (lista)

Crear empleado

Editar empleado

Servicios (lista)

Crear servicio

Editar servicio

Productos (lista)

Crear producto

Editar producto

Inventario

Reportes (lista)

Vista de reporte

Configuración general

Promociones

Soporte (5)

FAQ

Base de conocimientos

Tickets

Nuevo ticket

Chat

TOTAL APROXIMADO: 57 PÁGINAS
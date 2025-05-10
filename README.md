# 🛠️ Documentación Funcional - E-commerce de Autopartes

## 📌 Objetivo General

Desarrollar una plataforma web que permita la comercialización de repuestos y autopartes para vehículos, facilitando la búsqueda, selección, compra y gestión de productos de manera segura y eficiente.

---

## 👤 Accesos y Roles de Usuario

### 1. Visitante (No registrado)

- Acceso al catálogo público de productos.
- Puede buscar y visualizar detalles de productos.
- Puede registrarse o iniciar sesión.

### 2. Cliente Registrado

- Acceso completo al catálogo.
- Gestión de su perfil personal.
- Carrito de compras activo.
- Historial de pedidos.
- Seguimiento de envíos.
- Posibilidad de guardar productos como favoritos.

### 3. Administrador del Sistema

- Gestión completa de productos (alta, baja, modificación).
- Gestión de usuarios (ver, editar, bloquear).
- Control de inventario.
- Seguimiento y control de pedidos.
- Visualización de reportes y estadísticas de ventas.

---

## 🧩 Módulos Funcionales del Sistema

### 🛒 Módulo de Catálogo

- Filtros por categoría, marca, modelo de vehículo, rango de precio.
- Vista previa y detalles de cada producto.
- Ver compatibilidad con modelos específicos.
- Imágenes de alta calidad y descripción técnica.

### 👨‍💻 Módulo de Usuarios

- Registro de usuario con verificación por email.
- Inicio de sesión y recuperación de contraseña.
- Edición de datos personales.
- Gestión de direcciones de envío.

### 💳 Módulo de Carrito y Compras

- Agregar y quitar productos del carrito.
- Modificar cantidad de productos.
- Calcular total y visualizar resumen antes de compra.
- Confirmación y validación de pedidos.

### 🚚 Módulo de Pedidos y Envíos

- Visualización de estado del pedido: Pendiente, Enviado, Entregado.
- Registro de direcciones múltiples de entrega.
- Seguimiento del pedido desde el panel del cliente.

### 💰 Módulo de Pagos (💵 extra - servicio externo de pago)

- Integración con plataformas como PayPal, Stripe y/o pagos por transferencia.
- Validación segura del pago.
- Generación de comprobante electrónico.

### 📦 Módulo de Inventario (Admin)

- Agregar nuevos productos.
- Editar o eliminar productos existentes.
- Control de stock disponible.
- Notificaciones por bajo inventario.

### 📈 Módulo de Reportes (Admin)

- Ventas por período.
- Productos más vendidos.
- Reporte por categoría o marca.
- Actividad de usuarios.

---

## 🎨 Diseño y Usabilidad

- Interfaz responsive (adaptada para móviles, tabletas y escritorio).
- Navegación intuitiva con buscador visible.
- Diseño moderno, enfocado en la experiencia de usuario (UX).
- Carga rápida de páginas y optimización de imágenes.

---

# 💼 Propuesta de Desarrollo

## 🧩 Módulos y Precios por Etapa

| Módulo / Funcionalidad                               | Descripción breve                                                               | Precio (USD)           |
| ---------------------------------------------------- | ------------------------------------------------------------------------------- | ---------------------- |
| 🛒 Catálogo de Productos                             | Vista de productos con filtros, detalles e imágenes.                            | 150                    |
| 🔍 Buscador y Filtros                                | Filtro por categoría, marca, modelo, año, precio.                               | 120                    |
| 👤 Registro e Inicio de Sesión                       | Sistema de autenticación seguro (JWT o similar).                                | 100                    |
| 👛 Carrito de Compras                                | Agregar, eliminar, modificar productos, ver resumen.                            | 100                    |
| 💳 Módulo de Pago                                    | Integración con pasarela de pago (ej. PayPal, Stripe).                          | 100 - pago por consumo |
| 🚚 Gestión de Pedidos y Envíos                       | Registro de direcciones y seguimiento del estado del pedido.                    | 150                    |
| 🧑‍💼 Panel de Administración                           | Crear, editar y eliminar productos, stock y categorías.                         | 100                    |
| 📊 Reportes y Estadísticas (Admin)                   | Reportes de ventas, productos más vendidos, actividad de usuarios.              | 150                    |
| ⚙️ Panel de Configuración General                    | Ajustes básicos del sistema, como logo, datos de contacto, impuestos.           | 50                     |
| 🔒 Seguridad y Control de Accesos                    | Validación, protección contra ataques comunes (CSRF, XSS, etc.).                | 50                     |
| 🚀 Despliegue en Hosting / Dominio / Soporte inicial | Subida a servidor, configuración de dominio y asesoría post-lanzamiento básica. | 100 – 120              |

---

## 💰 Total Aproximado

- **Precio real:** **USD 970 – sin pasarela de pago / despliegue**
- **Precio mínimo negociable:** **USD 700 – sin pasarela de pago / despliegue**

> _Precios negociables por paquete completo. También se puede trabajar por etapas con pagos por avance._

---

## 📞 Contacto y condiciones

- Tiempo estimado de entrega: 2 - 3 meses.
- Se solicita 40% al inicio, 40% a mitad, 20% al finalizar.
- Incluye una ronda de cambios por módulo.
- Soporte adicional o cambios fuera de alcance (mitad del proyecto) se presupuestan aparte.

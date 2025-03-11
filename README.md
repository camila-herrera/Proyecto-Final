# 🚀 Selk Nam Store - Marketplace de Seguridad  

🔗 **Demo del proyecto:** [marketplace-seguridad.onrender.com](https://marketplace-seguridad.onrender.com)  
🔗 **API Backend:** [pf-hito4.onrender.com/api](https://pf-hito4.onrender.com/api)  
🔗 **Ejemplo de endpoint:** [Productos API](https://pf-hito4.onrender.com/api/productos)  

## 🎯 Sobre el Proyecto  
Selk Nam Store es una tienda online de productos de seguridad con un sistema de roles bien definido:  

- 🛑 **Visitantes:** Ven productos sin precios, no pueden comprar.  
- 🛍️ **Usuarios:** Ven precios, pueden comprar con método de pago "Otros".  
- 🏪 **Clientes:** Gestionan productos y pedidos, pero no pueden comprar.  

## 🛠️ Tecnologías Utilizadas  
### 💻 **Frontend**  
- React + Vite ⚡  
- React Router | Bootstrap | Axios | SweetAlert2  

### 🖥️ **Backend**  
- Node.js + Express  
- PostgreSQL | JWT | bcryptjs | CORS | dotenv  

### 🔐 **Autenticación y Seguridad**  
- JSON Web Tokens (JWT)  
- Middleware para protección de rutas  

## 🎭 Demo en Vivo  
### 🏠 **Visitante**  
- Puede ver productos sin precios.  
- No tiene acceso al carrito ni perfil.  

### 🔑 **Usuario (Ejemplo: Camila)**  
- Puede ver precios, agregar productos al carrito y comprar.  
- Tiene acceso a su perfil y a su historial de compras.  
- Solo puede pagar con el método "Otros".  

### 🏪 **Cliente (Ejemplo: Luis)**  
- Puede gestionar productos y pedidos.  
- No tiene acceso al carrito ni perfil.  

## 🚀 Retos y Aprendizajes  
- 🔐 **Manejo de roles:** Control de acceso según permisos.  
- 🛒 **Carrito de compras:** Implementado con Context API.  
- 🔄 **Protección de rutas:** JWT para autenticación segura.  

## 🎯 Conclusión  
Selk Nam Store es una plataforma funcional con control de roles, autenticación segura y experiencia optimizada. Integrando frontend, backend y base de datos, logramos un sistema eficiente y seguro.  

💬 ¡Gracias por tu atención! 🚀🔥  

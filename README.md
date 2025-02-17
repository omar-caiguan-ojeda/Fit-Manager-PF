🏋️‍♂️ Fit-Manager
Gestión integral de gimnasios con autenticación, pagos y administración eficiente
🚀 Descripción
Fit-Manager es una plataforma Full Stack diseñada para la administración de gimnasios, permitiendo la gestión de clientes, entrenadores, rutinas de entrenamiento y pagos. La aplicación combina un backend robusto en NestJS con un frontend moderno en Next.js, ofreciendo una experiencia eficiente e intuitiva.
✨ Características
📋 Gestión de usuarios (clientes, entrenadores y administradores)
🔐 Autenticación segura con JWT y OAuth (Google)
💳 Pagos integrados con MercadoPago y Stripe
📆 Reservas y planificación de entrenamientos
🌎 Subida de imágenes en la nube con Cloudinary
📊 Panel de administración con métricas clave
🛠️ Tecnologías
Backend:
NestJS | TypeScript | PostgreSQL | TypeORM
JWT | Passport.js | Swagger | Nodemailer
MercadoPago | Cloudinary | Multer
Frontend:
Next.js | React | Tailwind CSS | Framer Motion
Axios | Radix UI | SweetAlert2
Infraestructura:
Docker | Render | Google Cloud
📦 Instalación
bash
Copiar
Editar
# Clonar el repositorio
git clone https://github.com/tuusuario/fit-manager.git
cd fit-manager

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env

# Ejecutar el backend
npm run start:dev

# Ejecutar el frontend
cd frontend
npm run dev
🏗️ Contribución
Si deseas contribuir, ¡eres bienvenido! Por favor, abre un issue o envía un pull request con mejoras.
📜 Licencia
Este proyecto está bajo la licencia MIT.
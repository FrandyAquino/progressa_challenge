# 🌐 Customizable News Aggregator - Aplicación web de noticias personalizable

## 🧠 Progressa Challenge - Una solución digital completa

Bienvenidos a **News Aggregator**, es una aplicación de noticias diseñada para ofrecer una experiencia de usuario mejorada a través de un enfoque estético y funcional. Se enfoca en implementar características como la persistencia de preferencias del usuario, animaciones y transiciones suaves, además de un diseño responsivo que incluye un menú hamburguesa. Su objetivo es facilitar el acceso a contenido relevante de noticias mientras se mantiene una interfaz atractiva y fácil de usar.

## 🚀 Funcionalidades

- **Interfaz atractiva** 🎨: Diseño responsivo que se adapta a diferentes dispositivos, ofreciendo una experiencia visualmente agradable.
- **Persistencia de preferencias** 💾: Guarda las configuraciones del usuario para personalizar la experiencia en futuras visitas.
- **Filtrado de noticias** 📱: Permite a los usuarios seleccionar categorías específicas para acceder a contenido relevante.
- **Integración de API de noticias** 📰: Acceso a contenido actualizado y relevante de diversas fuentes informativas.

## 📁 Estructura del Proyecto

```plaintext
ProggresaChallenge/
├── backend/
|   ├── dist/
|   ├── node_modules/
|   ├── src/
|   |   ├── config/
|   |   ├── controllers/
|   |   ├── interfaces/
|   |   ├── models/
|   |   ├── routes/
|   |   ├── shared/
|   |   ├── validators/
|   ├── app.ts
|   ├── server.ts
|   ├── types/
│   ├── .env
│   └── nodemon.json
├── frontend/
|   ├── node_modules/
|   ├── public/
|   ├── src/
|   |   ├── auth/
|   |   ├── components/
|   |   ├── utils/
|   ├── App.tsx
|   ├── axiosConfig.ts
|   ├── main.tsx
└── README.md
```

## 📋 Requisitos

### Backend

- Node.js (versión recomendada: 16 o superior)
- Express (versión: ^4.18.2)
- Mongoose (versión: ^6.8.0)
- dotenv (versión: ^16.0.3)
- cors (versión: ^2.8.5)

### Frontend

- React (versión: ^18.3.1)
- React-DOM (versión: ^18.3.1)
- Axios (versión: ^1.7.7)
- AOS (versión: ^2.3.4)
- Framer Motion (versión: ^11.11.9)
- Lucide React (versión: ^0.452.0)
- Vite (versión: ^5.4.8)
- Tailwind CSS (versión: ^3.4.13)
- TypeScript (versión: ^5.5.3)

### DevDependencies

- ESLint (versión: ^9.11.1)
- TypeScript ESLint (versión: ^8.7.0)
- PostCSS (versión: ^8.4.47)
- Autoprefixer (versión: ^10.4.20)
- Vite Plugins (versión: ^4.3.2)

## 🛠️ Instalación

### Clonar el Repositorio

Para clonar este proyecto, sigue los siguientes pasos:

1. **Clona el repositorio**:

   ```sh
   https://github.com/FrandyAquino/proggresa_challenge.git
   cd proggresa_challenge
   ```

2. **Instala las dependencias del backend**:

   ```sh
   cd backend
   npm install
   ```

3. **Instala las dependencias del frontend**:

   ```sh
   cd ../frontend
   npm install
   ```

4. **Crea el archivo .env**: Dentro de la carpeta backend y agrega las siguientes variables:
   ```sh
   PORT=5000
   MONGO_URI=mongodb+srv://frandyjavieraquino13:kLgQGxZoR1bGzB7N@proggresa.pfpvc.mongodb.net/proggresa?retryWrites=true&w=majority&appName=proggresa
   NEW_API_TOKEN="f8c4d8121f824794a3ca6c4c09230975"
   ```

### 🎥 Uso de la Aplicación

1. **Ejecuta el backend**: y espere hasta que diga MongoDB connected

   ```sh
   cd ../backend
   npm run dev
   ```


2. **Ejecuta el fronted**:

   ```sh
   cd ../frontend
   npm run dev
   ```

3. **Dirigete a**:

   ```sh
   http://localhost:5173/
   ```

4. **Empieza a utilizar la aplicación**: Para poder utilizar los filtros y demás, primero debes registrarte, así que crea tu cuenta.

## 📞 Contacto

Si tienes alguna pregunta, no dudes en contactarme:

- [Frandy Aquino](https://github.com/FrandyAquino) 👨🏽
- [Portafolio](https://frandyaquino.netlify.app/) 🖥️

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.



# 🧬 Pokémon Info Web App

Esta es una aplicación web desarrollada con **React** y **Vite**, que permite a los usuarios buscar y explorar información detallada sobre los Pokémon a través de la API pública [PokéAPI](https://pokeapi.co/).

Esta aplicación es ideal para fanáticos de Pokémon, desarrolladores curiosos y cualquier persona interesada en aprender sobre el consumo de APIs REST con React.

---

## ✨ Características Principales

- 🔎 **Búsqueda de Pokémon** por nombre o ID.
- 📄 **Visualización de datos** como tipo, habilidades, estadísticas base, y sprites oficiales.
- ⚡ Interfaz ligera, moderna y de carga rápida gracias a **Vite**.
- 📡 Consumo de datos en tiempo real desde la **PokéAPI**.

---

## 🧑‍💻 Desarrollado por Anderson  Jaren Flores Ruiz

**Universidad:** Universidad Tecnológica del Perú  
**Curso:** Desarrollo Web  
**Año:** 2024

---

## 🧱 Estructura del Proyecto

El proyecto sigue una arquitectura de componentes típica de React:

```
pokemon-info/
├── public/                 
├── src/                   
│   ├── components/       
│   │   └── PokemonCard.jsx
│   ├── App.jsx           
│   ├── main.jsx           
├── index.html            
├── package.json           
├── vite.config.js         
└── README.md
```

---

## ⚙️ Tecnologías Utilizadas

- ⚛️ **React** – Biblioteca para construir interfaces de usuario.
- ⚡ **Vite** – Empaquetador ultrarrápido para proyectos modernos.
- 🎨 **CSS moderno** – Para un diseño simple y responsivo.
- 🌐 **PokéAPI** – API REST gratuita con datos completos de Pokémon.

---

## 🚀 Cómo Ejecutar el Proyecto

### 🖥️ Requisitos

- Node.js (v16 o superior)
- NPM o Yarn

### 🔧 Pasos

1. **Clonar el repositorio**:

```bash
git clone https://github.com/tu-usuario/pokemon-info.git
cd pokemon-info
```

2. **Instalar las dependencias**:

```bash
npm install
```

3. **Iniciar el servidor de desarrollo**:

```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:5173` para ver la aplicación.

---

## 📡 API Utilizada

- **PokéAPI** – [https://pokeapi.co](https://pokeapi.co)

Ejemplo de consumo:

```javascript
fetch("https://pokeapi.co/api/v2/pokemon/pikachu")
  .then(response => response.json())
  .then(data => console.log(data));
```

---


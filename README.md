# Lab_DB_3

# ¿Cómo correr los scripts?

# Crear una base de datos utilizando pgAdmin o Tablesplus
# Nombrar a la base de datos tienda_componentes

1. Correr los scripts (Tienda de componentes.sql, data.sql y vista_componentes)
2. En tienda de componentes/backend/config modificar el archivo config.json
3. En config.json agregar tus credenciales de postgres (usuario y contraseña)


# Instalación de dependencias

# en el backend
npm install -g nodemon

# en el frontend (carpeta TiendaComponentes)
npm install --save-dev vite


# ¿Cómo correr el programa?

# Para levantar el backend
cd backend
npm run dev

# Para levantar el frontend

cd tienda de componentes
npm run dev
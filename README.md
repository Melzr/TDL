# Trabajo Práctico - Teoría del Lenguaje
### Curso Ferrigno - 2C2021

App web de ecommerce desarrollada en Ruby on Rails.

## Requisitos
- Ruby (versión 3.0.0)
- Rails (versión 6.1.4.1)
- MySQL y MySQLd (mysql2 versión 0.5) 

## Ejecución

### Instalación de dependencias:

```
yarn install
bundle install
```

### Configuración de la base de datos:

Para cargar los datos del archivo seeds.rb (semilla con una cuenta de administrador y autos precargados):

```
rails db:setup
```

Migración de la base de datos:

```
rails db:migrate
```

### Ejecución del servidor:

Para ejecutar el servidor en `http://localhost:3000/`:

```
rails s
```

## Integrantes del grupo

    - Balmaceda, Fernando
    - Craviotto, Mateo
    - Diem, Walter Gabriel
    - Lazzaro, Melina

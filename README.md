# Aerolinea-ACME
Descripción
ACME AIR es una aplicación móvil para reserva y gestión de vuelos diseñada exclusivamente para dispositivos móviles. La aplicación permite a los usuarios buscar vuelos, realizar check-in, ver sus vuelos reservados y gestionar su cuenta.

Características Principales
Interfaz móvil optimizada: Diseño responsive exclusivo para dispositivos móviles

Flujo completo de reserva: Desde búsqueda hasta check-in

Gestión de cuenta: Registro, inicio de sesión y recuperación de contraseña

Visualización de vuelos: Listado de vuelos disponibles y reservados

Estructura del Proyecto

ACME-AIR/
├── index.html          # Página de inicio de sesión
├── create.account.html # Página de registro de usuario
├── recuperarpasword.html # Página de recuperación de contraseña
├── create-password.html # Página para crear nueva contraseña
├── menu.html           # Menú principal después de iniciar sesión
├── flight-search.html  # Búsqueda de vuelos
├── available-flights.html # Listado de vuelos disponibles
├── checkin.html        # Página para realizar check-in
├── my-flights.html     # Página con los vuelos del usuario
├── styles.css          # Hoja de estilos principal
├── estilos.css         # Hoja de estilos secundaria
└── log/                # Directorio de imágenes/logo
    ├── Logo_1.png
    └── logo2.png

## Requisitos Técnicos

- Diseño exclusivo para móviles (muestra mensaje de error en desktop)
- Compatible con navegadores modernos
- No requiere backend (funcionalidad frontend básica)

## Flujo de Navegación

1. **Inicio de Sesión** (`index.html`) → Menú Principal (`menu.html`)
2. **Registro** (`create.account.html`) → Crear Contraseña (`create-password.html`) → Menú Principal
3. **Recuperar Contraseña** (`recuperarpasword.html`) → Crear Contraseña → Menú Principal
4. **Menú Principal** → Búsqueda de Vuelos (`flight-search.html`) → Vuelos Disponibles (`available-flights.html`)
5. **Menú Principal** → Check-In (`checkin.html`)
6. **Menú Principal** → Mis Vuelos (`my-flights.html`)

## Tecnologías Utilizadas

- HTML5
- CSS3 (con Media Queries para detección móvil)
- Diseño responsive

## Notas Importantes

- La aplicación está diseñada para verse exclusivamente en dispositivos móviles
- Al acceder desde un navegador de escritorio, se mostrará un mensaje indicando que solo está disponible para móviles
- Los datos no persisten ya que no hay backend implementado

## Autor

Juan Pablo Cifuentes 

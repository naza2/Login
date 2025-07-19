# Portal de Administración Angular con Explorador de Rick & Morty

![Banner del Proyecto](https://placehold.co/1920x500?text=Portal+de+Administraci%C3%B3n+Angular+con+Explorador+de+Rick+%26+Morty)

Un portal de administración basado en Angular que cuenta con autenticación de usuarios, gestión de perfiles y un extenso explorador de personajes de Rick y Morty. Esta aplicación se integra con una API externa para la autenticación de usuarios y la recuperación de datos de personajes.

## Características

### Sistema de Autenticación
![Pantalla de Login](https://placehold.co/600x400?text=Pantalla+de+Login)
- Inicio de sesión seguro con autenticación basada en API
- Gestión de sesiones
- Rutas protegidas
- Control de acceso basado en roles (si aplica)

### Portal de Administración
![Dashboard de Administración](https://placehold.co/600x400?text=Dashboard+de+Administraci%C3%B3n)
- Visualización del perfil del usuario
- Gestión de cuentas
- Control de sesión

### Explorador de Personajes de Rick & Morty
![Explorador de Personajes](https://placehold.co/600x400?text=Explorador+de+Rick+%26+Morty)
- Funcionalidad de búsqueda avanzada:
  - Filtrar por estado (Vivo, Muerto, Desconocido)
  - Filtrar por especie (Humano, Alienígena, etc.)
- Tabla paginada de personajes que muestra todos los 826 personajes
- Vista detallada de personajes
- Operaciones CRUD (visualizar, editar, eliminar)

## Tecnologías Utilizadas

- **Framework Frontend**: Angular 14+
- **Gestión de Estado**: NgRx (Opcional)
- **Componentes UI**: Angular Material
- **Cliente HTTP**: Angular HttpClient
- **Enrutamiento**: Angular Router
- **Autenticación**: JWT (JSON Web Tokens)
- **Pruebas**: Jest/Karma (Opcional)
- **Integración de API**: Observables de RxJS

## Comenzando

### Requisitos Previos

- Node.js (v16+ recomendado)
- npm (v8+ recomendado) o yarn
- Angular CLI (`npm install -g @angular/cli`)

### Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/angular-admin-portal.git
cd angular-admin-portal

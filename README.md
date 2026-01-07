# PetShop Amigos Peludos

Proyecto de tienda de mascotas desarrollado con Bootstrap 5 y SASS.

##  Instalación

1. Clona el repositorio:
```bash
git clone <tu-repositorio>
cd azterketa-proiektua
```

2. Instala las dependencias:
```bash
npm install
```

##  Uso

### Compilar SASS una vez:
```bash
npm run sass
```

### Modo desarrollo (watch mode):
```bash
npm start
```

Este comando compilará automáticamente los archivos SCSS cada vez que hagas cambios.

##  Estructura del Proyecto
azterketa-proiektua/
├── node_modules/
├── src/
│   ├── scss/
│   │   ├── _variables.scss    
│   │   ├── _mixins.scss        
│   │   ├── _components.scss    
│   │   └── styles.scss         
│   └── css/
│       └── styles.css          
├── index.html                   
├── package.json                
└── README.md                   

##  Características

- **Bootstrap 5**: Sistema de grid responsive
- **SASS**: Preprocesador CSS con variables y mixins
- **Responsive**: Adaptado a móvil, tablet y escritorio
- **Modales**: Información detallada de productos y servicios
- **Navbar responsive**: Con menú hamburguesa en móvil

## 📱 Breakpoints

- **Móvil**: < 768px (1 columna)
- **Tablet**: 768px - 991px (2 columnas)
- **Escritorio**: ≥ 992px (3 columnas)

## 🎨 Paleta de Colores

- **Primary**: #4a90e2
- **Secondary**: #f39c12
- **Accent**: #e74c3c
- **Dark**: #2c3e50
- **Light**: #ecf0f1

## 📝 Licencia


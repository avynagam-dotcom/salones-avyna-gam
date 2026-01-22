# Avyna - Localizador de Salones

Landing page premium para localizar salones autorizados Avyna en la Alcaldía Gustavo A. Madero (CDMX).

## 🚀 Características

- **Mapa Interactivo**: Visualización elegante de salones usando React-Leaflet
- **Diseño Premium**: Estética minimalista con colores dorados, plata, blanco y negro
- **Mobile-First**: Diseño completamente responsive
- **Integración CSV**: Consumo de datos desde archivo CSV local o Google Sheets
- **Navegación**: Botones directos para Google Maps y Waze
- **Animaciones**: Transiciones suaves con Framer Motion

## 📋 Requisitos Previos

- Node.js 18+ 
- npm o yarn

## 🛠️ Instalación

1. Instala las dependencias:
```bash
npm install
```

2. Ejecuta el servidor de desarrollo:
```bash
npm run dev
```

3. Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

## 📊 Formato de Datos CSV

El CSV debe contener al menos las siguientes columnas:
- **Coordenadas** (formato: "lat, lng")
- **Dirección** (opcional)

El archivo debe estar en: `/public/data/salones.csv`

## 🚢 Producción

Para crear una build de producción:

```bash
npm run build
npm start
```

## 📝 Tecnologías

- Next.js 14 (App Router)
- React 18
- TypeScript
- Tailwind CSS
- Framer Motion
- React-Leaflet
- PapaParse

## 📄 Licencia

Proyecto privado para Avyna - Distribución Exclusiva GAM

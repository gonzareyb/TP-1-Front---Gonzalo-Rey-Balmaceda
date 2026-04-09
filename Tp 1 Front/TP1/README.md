Nintendo World

Proyecto frontend desarrollado con Astro como actividad diagnóstico para la materia de Frontend.

Descripción

Sitio web estático con tres secciones principales:

- **Catálogo de juegos de Mario**: Explorá más de 18 juegos de la saga con filtros por consola y género, y búsqueda en tiempo real.
- **Catálogo de consolas Nintendo**: Desde la NES hasta la Switch, con filtros por generación y búsqueda.
- **Dashboard del clima**: Consultá el clima en tiempo real de cualquier ciudad del mundo usando la API de OpenWeatherMap.

Herramientas usadas

- [Astro](https://astro.build/) — Framework principal
- [TypeScript](https://www.typescriptlang.org/) — Tipado estático
- [OpenWeatherMap API](https://openweathermap.org/api) — Datos del clima en tiempo real
- CSS Variables — Sistema de diseño y dark mode
- Google Fonts — Press Start 2P + Nunito

Features

- Dark / Light mode con persistencia en localStorage
- Filtros interactivos con JavaScript
- Búsqueda en tiempo real
- Animaciones CSS
- Diseño responsive
- Fetch a API externa (OpenWeatherMap)
- Componentes reutilizables (CardJuego, CardConsola)

Cómo ejecutarlo

Instalación

1. Cloná el repositorio:
```bash
git clone https://github.com/gonzareyb/TP-1-Front---Gonzalo-Rey-Balmaceda.git
```

2. Navegá a la carpeta del proyecto:
```bash
cd "Tp 1 Front/TP1"
```

3. Instalá las dependencias:
```bash
npm install
```

4. Corré el servidor de desarrollo:
```bash
npm run dev
```

5. Abrí el navegador en `http://localhost:4321`

Deploy

El sitio está deployado en Vercel:
[tp-1-front-gonzalo-rey-balmaceda.vercel.app](https://tp-1-front-gonzalo-rey-balmaceda.vercel.app)

Autor

Gonzalo Rey Balmaceda
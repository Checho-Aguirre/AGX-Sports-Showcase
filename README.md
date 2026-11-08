<p align="center">
  <b>Español</b> · <a href="README.en.md">English</a>
</p>

# AGX Sports

**La app de deporte de resistencia hecha para entrenar como con un coach, sin pagar por ello.**

AGX Sports es una app para running, ciclismo, triatlón y entrenamiento híbrido, creada por **AGX Tech And Code**. Graba tus actividades, analiza tu rendimiento, te conecta con tu comunidad y te arma un plan de entrenamiento personalizado que se adapta a lo que de verdad haces.

Las funciones que otras apps cobran en su suscripción, en AGX Sports son gratis.

Nace en Armenia, Quindío (Colombia), y se diseña desde el primer día para atletas de todo el mundo: varios idiomas, unidades métricas e imperiales, zonas horarias y eventos de cualquier país.

> **Estado:** en diseño. Las capturas y GIFs se irán agregando a medida que terminemos cada pantalla.

> Este repositorio es solo una vitrina. El código fuente de la app es privado.

## Funciones principales

### Grabación y análisis
- Más de 30 deportes, autopausa, splits, vueltas y pantallas de datos configurables.
- GPS confiable en segundo plano y grabación sin conexión que sincroniza después.
- Zonas de frecuencia cardiaca, potencia y ritmo, curva de potencia, fitness, fatiga y forma, ritmo ajustado por pendiente e historial de FTP.
- Resumen de cada actividad con IA.

### AGX Coach (gratis)
- Planes personalizados y adaptativos para ciclismo, running, triatlón y deporte híbrido, basados en ciencia del deporte pública.
- Evaluación inicial, tests guiados (FTP, umbral, ritmo crítico, natación y fuerza) y metas por etapas.
- Calendario de entrenamientos con sesiones estructuradas que puedes enviar al reloj, al ciclocomputador o al rodillo.
- Ajuste por altitud y calor, prevención de lesiones por exceso de carga y feedback semanal.
- Chat con el coach IA, guía de nutrición e hidratación y estrategia de carrera.

### Zona Ciclista
- Sensores Bluetooth directos desde el celular: potenciómetro, banda de FC, cadencia, velocidad y radar.
- Análisis de subidas y puertos icónicos del mundo, viento y clima en la ruta.
- Garaje de bicis con mantenimiento por componente y **registro anti-robo** con verificador de serial.

### Rutas y mapas
- Creador de rutas, rutas sugeridas, mapas de calor y navegación paso a paso.
- Mapas descargables para usar sin señal, pensados para celulares de gama media y pocos datos.

### Comunidad
- Seguir atletas, feed de actividades, likes, comentarios y compartir rutas.
- Copas, trofeos y medallas con niveles, retos, ligas y clubes.
- Tarjetas listas para historias de Instagram y TikTok.

### Importa tu historial
- Trae todas tus actividades desde el archivo de exportación de otras apps y desde Garmin, Polar, Suunto, COROS o archivos GPX, FIT y TCX.

### Privacidad y seguridad primero
- Actividades privadas o solo para seguidores por defecto y zonas de privacidad para ocultar dónde empiezas y terminas.
- Compartir ubicación en vivo con tus contactos y detección de caídas.
- Exporta o borra tu cuenta y todos tus datos en pocos clics.

## Capturas de pantalla

*Próximamente.* Las capturas van en [`screenshots/`](screenshots/) y los GIFs en [`gifs/`](gifs/).

## Stack tecnológico

| Parte | Tecnología |
|---|---|
| App móvil (iOS y Android) | React Native + Expo + TypeScript |
| Web y panel | Next.js en Vercel |
| Backend | Supabase (Auth, Postgres con PostGIS, Storage, Edge Functions) |
| Mapas | MapLibre + OpenStreetMap |
| Datos de salud | Apple HealthKit y Health Connect |
| Idiomas | Español e inglés al lanzar, listo para más |

## Roadmap

- [ ] **Fase 0 — Diseño:** marca, investigación, especificación y diseño de pantallas.
- [ ] **Fase 1 — MVP (Android y iPhone, español e inglés):** grabación GPS, sensores de ciclismo, importación de historial, análisis de potencia y subidas, rutas con mapas sin conexión, privacidad, garaje anti-robo, prevención de lesiones, social básico, copas y medallas, y AGX Coach para ciclismo y running.
- [ ] **Fase 2:** triatlón, rodillo inteligente, segmentos, ligas, clubes, rodadas en grupo, seguridad en vivo, seguimiento en vivo para la familia, calendario mundial de eventos y más idiomas.
- [ ] **Fase 3:** marketplace de coaches humanos y beneficios en la tienda AGX.

## Contacto

📧 **agxtechandcode@gmail.com**

## Licencia

© 2026 AGX Tech And Code. Todos los derechos reservados. Consulta [LICENSE](LICENSE).

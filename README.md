# Descubriendo Santa Rosa

Guía turística interactiva de **Santa Rosa de Calamuchita** (Córdoba, Argentina), pensada para que cualquier persona, de cualquier edad, encuentre lo que busca con uno o dos toques.

🔗 **Ver el sitio:** https://TU-USUARIO.github.io/descubriendo-santa-rosa/

![Portada del sitio](img/fondo.jpg)

## Qué incluye

| Sección | Qué hace |
|---|---|
| **Inicio** | Banner con la ilustración, buscador instantáneo y accesos directos (mapa, llamar, WhatsApp, clima). |
| **¿Qué puedo hacer?** | Actividades filtradas por interés: río, aventura, en familia, cultura y noche. |
| **Mapa en vivo** | Mapa con todos los lugares y la ubicación del usuario en tiempo real, con el lugar más cercano. |
| **Agenda** | Fiestas y eventos de cada temporada. |
| **Historia** | Línea de tiempo desde los comechingones hasta hoy, y el origen del nombre “Calamuchita”. |
| **Dormir y comer** | Calculadora de presupuesto, alojamientos y restaurantes con puntajes, filtros y acceso directo a Google Maps. |
| **Tips** | Clima en vivo, cómo llegar, recorridos de 1 a 3 días y una lista de cosas para llevar. |
| **¿Team montaña o río?** | Test de 5 preguntas que recomienda lugares. |
| **QRs y videos** | Códigos QR que abren la ubicación de cada lugar. |
| **Contacto** | Oficinas de Turismo, WhatsApp, Instagram y teléfonos de emergencia. |

## Decisiones de diseño

- **Menos clics:** buscador en la portada, barra de navegación fija abajo en el celular, accesos directos y botón “Cómo llegar” en cada lugar.
- **Para todas las edades:** botón **Aa** para agrandar la letra, botones grandes y alto contraste.
- **Identidad:** colores del isologo de Santa Rosa (turquesa, naranja, amarillo y lima) y la ilustración en acuarela como imagen principal.
- **Responsive:** se adapta a celular, tablet y computadora.
- **Funciona sin JavaScript:** el contenido se ve igual en visores que no ejecutan scripts.

## Tecnologías

- HTML, CSS y JavaScript, sin frameworks.
- [Leaflet](https://leafletjs.com/) + [OpenStreetMap](https://www.openstreetmap.org/) para el mapa.
- [Open-Meteo](https://open-meteo.com/) para el clima en vivo.
- [QRCode.js](https://davidshimjs.github.io/qrcodejs/) para los códigos QR.
- Tipografías Montserrat, Nunito y Caveat (Google Fonts).

## Estructura

```
descubriendo-santa-rosa/
├── index.html        → todo el sitio
├── README.md         → este archivo
└── img/
    ├── fondo.jpg       → ilustración en acuarela
    ├── logo-claro.png  → isologo con letras negras
    ├── logo-oscuro.png → isologo con letras blancas
    ├── favicon.png     → ícono de la pestaña
    └── icono.png       → ícono para celulares
```

Los datos (lugares, alojamientos, restaurantes, precios y agenda) están al principio del `<script>` en `index.html`, en la sección **DATOS**, para editarlos fácilmente.

## Fuentes de información

- [Portal oficial de Turismo de Santa Rosa de Calamuchita](https://turismo.santarosamuni.com/)
- [Alojamientos habilitados por la Municipalidad](https://turismo360.santarosamuni.com/)
- [TripAdvisor](https://www.tripadvisor.com.ar/Hotels-g312773-Santa_Rosa_de_Calamuchita_Province_of_Cordoba_Central_Argentina-Hotels.html): puntajes de alojamientos y restaurantes (noviembre 2026)
- [AlquilerArgentina](https://www.alquilerargentina.com/C%C3%B3rdoba/Caba%C3%B1as-en-Santa-Rosa-De-Calamuchita/): precio promedio de cabañas

Los precios son de referencia y las coordenadas del mapa son aproximadas.

## Créditos

- El isologo de Santa Rosa de Calamuchita pertenece a la Municipalidad de Santa Rosa de Calamuchita. Se usa con fines académicos.

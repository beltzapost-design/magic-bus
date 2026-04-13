# Magic Bus · Siglo XXI y ½ — Notas de Diseño y Estructura
**Repo:** https://github.com/beltzaexperience/magic-bus  
**URL:** https://beltzaexperience.github.io/magic-bus/  
**Editor:** Luis Beltza · Doneztebe, Nafarroa  
**Estado:** activo y funcionando  

---

## Archivos
- `magic-bus-xxi.html` — estructura HTML principal
- `style.css` — CSS externo
- `BeltzaLogo.png` — puño Beltza Records (alojado en repo)
- `blackbarella.jpg` — ilustración Blackbarella · David Navascues
- `DCPC .jpg` — cartel It's Time · David Navascués

---

## Colores
```
--black:  #0a0a0a
--white:  #f2ede6  (crema)
--red:    #b01a1a
--amber:  #c8922a
--muted:  #666
Fondo artículos: crema #f0e8d8 (mismo que credo Manifiesto)
Texto artículos: #1a1a1a / #333
```

---

## Tipografías
- **Bebas Neue** — topband, brand-slash, marquees, títulos sección
- **Courier Prime** — cuerpo de texto artículos
- (Sin Playfair Display en este proyecto)

---

## Estructura general (de arriba a abajo)
1. **Topband sticky** — BELTZA RECORDS · DONOSTIA _ DONEZTEBE | MANIFIESTO · BELTZA SCENE · BELTZA RECORDS | ☰ hamburguesa
2. **Brand-slash** — MAGIC BUS (negro sobre rojo) + SIGLO XXI Y ½ (rojo sobre negro)
3. **Puño** BeltzaLogo.png
4. **Blackbarella** — ilustración David Navascues
5. **Texto intro** — presentación del proyecto + countdown IGNICIÓN (9·8·7...1·IGNICIÓN con JS)
6. **Cartel DCPC** — It's Time
7. **Marquee portadas** — 11 discos Flickr duplicados para loop
8. **Layout flex** — sidebar izquierda + contenido artículos
9. **Marquee géneros** — SOUL · FUNK · REGGAE... (entre artículos)
10. **Brand-slash inferior** — BELTZA/RECORDS + puño
11. **Footer** — links proyectos + DONOSTIA · Since 1990 · (Death or Glory)

---

## Layout artículos
```
display: flex
├── sidebar izquierda — secciones + buzón contacto + archivo histórico
└── main (contenido) — artículos por sección
```

### Sidebar
- **Secciones:** Música, Política, Digitalismo, Cine, Fotografía, Literatura, Cosmos, Gastronomía, Beltza Style, Euskal Herria, Cómics, Archivo
- **Buzón:** formulario ✉ Escríbenos con confirmación "¡Eskerrik asko!"
- **Archivo histórico:** Magic Bus nº1 (1989), nº2 (1989), nº3 (1990), Beltza Scene (2004), Magic Bus Siglo XXI y ½ (2026)
- **Editor:** Luis Beltza

### Artículos — estructura tipo
- Categoría + tema en pequeño (ej: "Digitalismo · Sistema Mundo")
- Título H2
- Autor (Luis Beltza u otro)
- Imagen principal (Flickr o externa)
- Cuerpo Courier Prime, fondo crema #f0e8d8
- Cita destacada con guión largo — autor · disco · año
- Sección comentarios con formulario
- Marquee géneros separador entre artículos

---

## Artículos publicados
1. **PONZOÑA DIGITAL EN UN SISTEMA MUNDO DIGITALISTA** — Digitalismo · Luis Beltza
2. **KAREN Y LOS REMEDIOS** — Música · Cumbia Amazónica · Luis Beltza
3. **SATÁN LEVANTANDO CON SU MALDAD LA CIVILIZACIÓN PIRAMIDAL** — Política · Afghan Whigs
4. **LA IGNORADA VANGUARDIA ANTIFASCISTA NEGRA DE EE.UU.** — Política · Antifascismo · Molly Crabapple / The Baffler
5. **FREE HUEY** — Política · Oakland 1968 · Black Panther Party · Fotos: Ruth-Marion Baruch
6. **ELECTRO CUMBIA** — Música · Nuevo Punk · Luis Beltza · Lido Pimienta
7. **SPACE IS THE PLACE** — Cosmos · Silver Surfer · Galactus · Jack Kirby
8. **INNER VISIONS** — Archivo · Referencias · Stevie Wonder · Kubrick · First Blood
9. **SAFE FROM HARM** — Música · Massive Attack · Shara Nelson · Blue Lines 1991

---

## Countdown IGNICIÓN
JS animado: 9·8·7·6·5·4·3·2·1·IGNICIÓN con efecto visual de encendido en rojo.

---

## Marquee géneros (entre artículos)
```
SOUL · FUNK · REGGAE · SKA · BLUES · JAZZ · PUNK · NEW WAVE · HIP HOP · 
BOSSA NOVA · DUB · CUMBIA · BRASIL · GARAGE · PSYCHEDELIC · KRAUTROCK · 
FREE JAZZ · NORTHERN SOUL
```

---

## Marquee portadas (fotos Flickr)
Prince Phillip Mitchell · Mito y Comadre · Toquinho & Vinicius de Moraes · Extremadura · Stiff Little Fingers · Buho · Karen y los Remedios · Dillinger · Madness · Arturo Somohano · Anima Latina Vol.2 (duplicados para loop continuo)

---

## Proyectos relacionados
- **Manifiesto:** https://github.com/beltzaexperience/Manifiesto-Beltza
- **UR-SAPIENS:** https://github.com/beltzaexperience/UR-SAPIENS
- **Beltza Records:** https://www.beltzarecords.com
- **Beltza Scene:** https://www.beltzarecords.com/beltzascene
- **Parroquia 13:** https://www.beltzarecords.com/parroquia13

---

## Pendientes
- Añadir link a UR-SAPIENS en topband y footer
- NOTAS.md subido al repo

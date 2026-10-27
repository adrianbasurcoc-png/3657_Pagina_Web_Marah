# Marah – Mockup (Proceso de Aprendizaje 2)

Mockup estático de un sitio web informativo de venta de kéfir de leche, instalado y compilado con npm.

Curso: Programación Web Básica · Periodo 2026-20

## Requisitos
- Node.js 18 o superior (incluye npm)

## Instalación y ejecución
```bash
# 1. Instalar dependencias (Tailwind CSS)
npm install

# 2. Generar el CSS (crea dist/output.css)
npm run build

# 3. Abrir el mockup en el navegador
#    Abrir el archivo src/index.html
```

Si haces cambios y quieres que se actualice solo:
```bash
npm run dev
```

## Estructura del proyecto
```
marah-mockup/
├── package.json          # Dependencias y scripts (build, dev)
├── tailwind.config.js    # Configuración de Tailwind (content, colores de marca, tipografía)
├── src/
│   ├── index.html        # Página (header, hero, secciones, footer)
│   └── styles.css        # Entrada de Tailwind (@tailwind + componentes con @apply)
└── dist/
    └── output.css        # CSS generado por "npm run build"
```

## Notas
- El mockup es estático: no integra PHP, MySQL ni APIs. El buscador y el formulario son maquetas visuales.
- Todo el estilo se hace con clases utilitarias de Tailwind; no se usan estilos inline.
- Es responsivo mediante prefijos `sm:`, `md:` y `lg:`.
- Alcance completo del proyecto: ver el documento de alcance incluido.

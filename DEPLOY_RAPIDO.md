# 🚀 Deploy Rápido — Web Muestras México v2.0

## Opción 1: Netlify Drop (Recomendado — 30 segundos)
1. Ve a https://app.netlify.com/drop
2. Arrastra la carpeta `web_ventas_v2/` (descomprimida) al área de drop
3. Obtendrás una URL tipo `https://webmuestras-abc123.netlify.app`
4. ¡Listo! Comparte esa URL con tus clientes.

## Opción 2: Cloudflare Pages (Recomendado si ya tienes cuenta)
1. Ve a https://dash.cloudflare.com
2. Ve a Pages → Create a project → Direct upload
3. Nombra el proyecto: `web-muestras-mexico`
4. Arrastra la carpeta `web_ventas_v2/`
5. Click Deploy. Listo en 60 segundos.

## Opción 3: GitHub Pages (Gratis pero más lento)
1. Ve a tu repo: https://github.com/veltis-hyper/web-muestras-mexico
2. Ve a Settings → Pages
3. Selecciona Source: Deploy from a branch → main → / (root)
4. Sube el contenido de `web_ventas_v2/` al repo (reemplazando lo existente)
5. Espera 2-3 minutos. La URL será: https://veltis-hyper.github.io/web-muestras-mexico/

## Opción 4: Vercel (Para desarrolladores)
1. Ve a https://vercel.com
2. Importa tu repo de GitHub o haz drag & drop de la carpeta
3. Click Deploy. Listo en 30 segundos.

## Estructura de carpetas para subir
```
web_ventas_v2/
├── index.html              ← Landing maestra
├── empresas/
│   ├── tortilleria_gz/
│   │   ├── index.html
│   │   └── assets/
│   ├── taller_abel/
│   │   ├── index.html
│   │   └── assets/
│   └── ... (30 empresas)
└── materiales_ventas/
    ├── empresas_contacto_v2.xlsx
    ├── propuestas_pdf/
    ├── email_templates/
    └── scripts_y_emails/
```

## ⚠️ Importante
- **NO subas el ZIP**. Descomprímelo primero y sube la carpeta.
- Las URLs individuales de cada empresa serán: `https://TU-DOMINIO.com/empresas/NOMBRE_EMPRESA/`
- Ejemplo: `https://webmuestras.netlify.app/empresas/tortilleria_gz/`
- Guarda la URL principal para compartirla en emails y WhatsApp.

## Contacto
Si necesitas ayuda: contacto@webmuestrasmexico.com

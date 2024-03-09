# TSC Rot-Gold-Casino Nürnberg e.V.

Willkommen auf der GitHub-Seite des Tanzsportclubs Rot-Gold-Casino Nürnberg.

## Zusammenfassung aller wichtigen Links

### Content Management System
- [Production](https://rgc-cms.up.railway.app/admin/)
- [Develop](https://rgc-cms-develop.up.railway.app/admin/)

### Webseite
- [Production](https://rgc-website.vercel.app/)
- [Develop](https://develop.rot-gold-casino.de/)

### Design
[Figma](https://www.figma.com/file/KhKd8CuLWBKf6eTQuswQWf/RGC-Website-Design)

## Plattformen und Services
Wir nutzen für das Hosting und die Entwicklung unserer Webseite unterschiedliche Plattformen und Services.
Als Account wird webmaster@rot-gold-casino.de verwendet.

### Vercel
Für das Hosting des Frontends verwenden wir [Vercel](https://vercel.com/).
Auf dem [Dashboard](https://vercel.com/tsc-rot-gold-casino-nuernberg/rgc-website) können die unterschiedlichen Deployments sowie der Status und die Logs eingesehen werden.
Sobald Änderungen auf GitHub gepusht werden, wird automatisch ein neuer Build gestartet, sodass die Webseite in wenigen Minuten aktualisiert wird.

### Strapi
Für die Verwaltung der Inhalte auf der Webseite verwenden wir [Strapi](https://strapi.io/), das führende Open Source Headless CMS.

### Railway
Für das Hosting des Content-Management-Systems und der Datenbank verwenden wir [Railway](https://railway.app/).
Auf dem [Dashboard](https://railway.app/dashboard) können die unterschiedlichen Deployments sowie der Status und die Logs eingesehen werden.
Sobald Änderungen auf GitHub gepusht werden, wird automatisch ein neuer Build gestartet, sodass das CMS in wenigen Minuten aktualisiert wird.

### Cloudinary
Für das Speichern von Bildern und anderen Medien benutzen wir [Cloudinary](https://cloudinary.com/).
Cloudinary wird von [Strapi als Asset-Server](https://docs.strapi.io/dev-docs/plugins/upload) verwendet und unterstützt die [automatische Bild-Optimierung](https://nextjs.org/docs/app/building-your-application/optimizing/images), sodass Bilder auf der Webseite schnell und effizient geladen werden.

### reCAPTCHA
Wir schützen unsere Webseite vor Spam und Missbrauch mithilfe von [reCAPTCHA](https://www.google.com/recaptcha/about/).
Auf dem [Dashboard](https://www.google.com/recaptcha/admin/site/697230498?hl=de) können Statistiken zu den Anfragen eingesehen werden.

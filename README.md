# robots.txt
File robots.txt yang biasanya saya terapkan pada website berbasis WordPress. Gunakan sebagai titik awal, modifikasi sesuai kebutuhan Anda.

```
User-agent: *

Disallow: /?*
Disallow: /?s=
Disallow: /feed/
Disallow: */feed/
Disallow: /search/
Disallow: /cgi-bin/
Disallow: /cdn-cgi/
Disallow: /wp-json/
Disallow: /wp-admin/
Disallow: /comments/
Disallow: */comments/
Disallow: /trackback/
Disallow: */trackback/
Disallow: /?rest_route=/

Allow: /media/
Allow: /wp-admin/admin-ajax.php

# Ganti dengan URL sitemap website Anda
Sitemap: https://web.site/sitemap.xml
```

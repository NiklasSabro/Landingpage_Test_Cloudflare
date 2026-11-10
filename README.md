# SABRO All-in Relax Landingpage

Statische Landingpage für das All-in Relax Bundle (KUDDE + MJUCK Einlage + MJUCKIS Kissen) mit Code RELAX5.

- Seite: `all-in-relax/index.html` → erreichbar unter `/all-in-relax` (Ziel: content.sabro.de/all-in-relax).
- `/` leitet per `_redirects` auf `/all-in-relax` weiter.
- CSS + JS stecken inline in der Seite, Bilder kommen von cdn.shopify.com.
- Meta Pixel: `151830518671424` („173850589s Pixel“, Werbekonto SABRO GmbH DACH 173850589). Events: PageView, ViewContent, AddToCart. `fbclid` und `utm_*` werden an den Warenkorb-Link auf sabro.de weitergegeben.
- Code und Rabatt anpassen: im Script-Block `OFFER` (`code`, `amount`).

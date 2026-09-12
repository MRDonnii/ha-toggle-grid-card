# Toggle Grid Card

## Neutral mobile preview

![Neutral mobile preview of ha-toggle-grid-card](docs/preview.png)

> Rendered at 390 px mobile width with fictional Home Assistant entities and values. No private dashboard, person, address, camera, or sensor data is included.


Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-toggle-grid-card.js` til `/config/www/ha-toggle-grid-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-toggle-grid-card/ha-toggle-grid-card.js?v=0.4.0
```

Tilføj derefter korttypen `custom:ha-toggle-grid-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT

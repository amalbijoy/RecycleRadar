# RecycleRadar

> Recycling-center discovery front-end prototype using simulated facility data.

## Overview

RecycleRadar is a responsive browser application for exploring recycling facilities, filtering by accepted materials and radius, and learning disposal guidance.

**Current implementation:** the facility catalogue and distances are simulated data. The UI demonstrates the product flow but is not backed by a live municipal or maps database.

## Features

- Search facilities by name
- Filter by material type and radius
- Facility cards with hours, contact details, accepted materials, amenities, and ratings
- Responsive layout
- Simulated location fallback
- Recycling education content

## Tech stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Browser APIs

## Run locally

Open `RecycleRadar.html` in a modern browser.

For more consistent behavior, serve the directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/RecycleRadar.html`.

## Data and limitations

The current version is a UI/logic prototype. Facility names, coordinates, distances, ratings, and contact details are sample data and should not be treated as real-world service information.

## Future work

- Live facility data source
- Real distance calculation
- Map provider integration
- Server-side search and caching
- Formal accessibility audit
- User accounts and saved locations

## License

GPL-3.0

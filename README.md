# RecycleRadar

> Recycling-center discovery front-end prototype using simulated facility data.

## Overview

RecycleRadar demonstrates a browser workflow for searching and filtering recycling facilities by name, material type, and a predefined distance value.

The current application uses **sample data only**. It does not connect to a live municipal recycling database, maps provider, or real location service.

## Features

- Search facilities by name
- Filter by material type
- Filter by a predefined search radius
- Display hours, contact details, accepted materials, amenities, and sample ratings
- Facility detail panel
- Responsive browser layout
- Recycling guidance and quick tips
- Fixed simulated New York City location display

## Data and limitations

The facility records contain sample names, addresses, phone numbers, coordinates, distances, ratings, hours, and amenities.

The displayed distance is taken directly from each sample record; it is **not calculated from the user's actual location**.

The map area is currently a UI placeholder rather than a live interactive map.

## Run locally

Open `RecycleRadar.html` in a modern browser, or serve the directory:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/RecycleRadar.html
```

## Roadmap

- Live recycling-facility data
- Geocoded distance calculation
- Real map integration
- Backend search and caching
- Accessibility testing and refinement
- Saved locations/user accounts

## License

See [LICENSE](LICENSE).

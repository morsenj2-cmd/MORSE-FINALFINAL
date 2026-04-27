# Ferrari

> Exported from [Morse](https://morse.co.in) — deterministic design for generative AI.

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view your site.

## Build for Production

```bash
npm run build
npm run preview
```

## Project Structure

```
├── pages/
│   └── index.jsx         # Main page with genome + layout constants
├── components/
│   ├── GenomeNavbar.jsx  # Navigation bar (dynamic links)
│   ├── GenomeHero.jsx    # Hero section
│   ├── GenomeFeatureGrid.jsx
│   ├── GenomeCardList.jsx
│   ├── GenomeStats.jsx
│   ├── GenomeTestimonial.jsx
│   ├── GenomeCTA.jsx
│   ├── GenomeFooter.jsx  # Footer (dynamic section links)
│   └── icons.jsx         # Genome-styled SVG icons
├── lib/
│   └── navigation.js     # Universal navigation handler
├── styles/
│   └── globals.css       # Tailwind + CSS variables from genome
├── src/
│   └── main.jsx          # React entry point
├── tailwind.config.js
├── vite.config.js
└── index.html
```

## Design Genome

This project was generated with a deterministic design genome:
- **Seed**: `8cef0e3cdf44cd27384f1f59e7885208…`
- **Primary color**: `8cef0e3cdf44cd27384f1f59e7885208374803d23bb11eb05635ef045a8af8f1`

Edit the `genome` constant in `pages/index.jsx` to experiment with different values,
or use Morse to regenerate a new variation.

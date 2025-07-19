#  VenueIQ

VenueIQ is an intelligent booking and demand prediction platform for live music and touring. It enables promoters and artists to identify the best venues and dates, using audience behaviour data and historical ticketing trends to make smarter booking decisions.

This repository is a portfolio showcase, featuring a live demo of the MVP.

📖 [Read the full story behind VenueIQ](https://www.notion.so/VenueIQ-2351d53cfded80e68a4afed09bd24c3e)

## Live Demo

👉 [Explore the VenueIQ Demo](https://venue-iq.vercel.app/)

(The demo highlights three key features — Date Optimisation, Audience Clusters, and Audience Alignment — powered by mocked data to simulate real-world predictions.)

## Screenshots

### Date Optimisation

![Date Optimisation Screenshot](public/screenshots/date-optimisation.png)

### Audience Clusters

![Audience Clusters Screenshot](public/screenshots/date-optimisation.png)

### Audience Alignment

![Audience Alignment Screenshot](public/screenshots/date-optimisation.png)

## Project Architecture

The repository follows a modular Next.js structure with a clear separation of concerns:

venue-iq/
├── public/
│   ├── data/
│   │   └── demand-data.json      # Mock ticketing and demand data
│   └── [various SVG files]       # Public assets
├── src/
│   ├── app/
│   │   ├── audience-alignment/   # Audience alignment feature
│   │   │   └── page.tsx
│   │   ├── audience-clusters/    # Audience clustering feature
│   │   │   └── page.tsx
│   │   ├── globals.css           # Global styles
│   │   ├── layout.tsx            # App layout
│   │   └── page.tsx              # Entry page
│   ├── components/               # Shared UI and feature components
│   │   ├── [content/header components]
│   │   └── ui/                   # Reusable UI primitives
│   │       ├── button.tsx
│   │       └── select.tsx
│   ├── lib/
│   │   └── utils.ts              # Utility functions
│   └── styles/
│       └── design-system.css     # Design system styling
├── package.json                  # Project dependencies
├── tsconfig.json                 # TypeScript configuration
├── next.config.ts                # Next.js configuration
└── [other config files]

## Tech Stack
  - Framework: Next.js 15 with React 19
  - Styling: TailwindCSS with custom design system
  - TypeScript: Full type safety throughout the application
  - Data Simulation: Static JSON files mimicking real ticketing
  and demand trends
  - Hosting: Vercel

## About This MVP

This demo showcases the core concepts of VenueIQ:
	•	Date Optimisation: Identifies venues and dates most likely to achieve high audience turnout.
	•	Audience Clusters: Segments audiences based on behaviour, spending habits, and preferences.
	•	Audience Alignment: Matches shows to the audience segments most likely to convert.

The MVP is powered by mocked data to demonstrate the user experience and platform logic.

## Vision & Next Steps

VenueIQ is designed to evolve into a fully integrated tool for promoters, with upcoming features such as:
	•	Automated Tour Planning: Generating entire optimised tour schedules with travel and rest constraints.
	•	Dynamic Pricing Insights: Forecasting price sensitivity and recommending price points for each audience segment.
	•	Sales Velocity Dashboards: Visualising ticket sales curves and early booking trends.
	•	Platform Integration: Connecting with email, paid social, and ticketing systems to directly target identified audience clusters.

## About

This project was conceived and built by Victoria Ward, combining experience in live music logistics with data-driven design and development to create an intelligent booking and marketing tool.

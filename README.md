# Calgary Barbell 16-Week Program Tracker (V3)

An interactive powerlifting workout tracking web application for the Calgary Barbell 16-Week Training Program, built with React and Vite.

## Features

- **Full 16-Week & Taper Prescriptions**: Auto-calculates percentages based on your custom Training Maxes (Squat, Bench, Deadlift).
- **Unit Support**: Easily toggle between `lb` and `kg` with customizable rounding increments and bar presets.
- **Set & Rest Tracking**: Interactive set check-off with an automatic rest timer bar.
- **Insights & Visual Analytics**:
  - Estimated 1RM progress lines per lift across 16 weeks (using Recharts).
  - Weekly volume / tonnage charts.
  - Personal Record (PR) tracking & history drill-down modal per exercise.
  - Heatmap adherence grid.
- **Calendar View**: Visual month calendar highlighting completed workout dates.
- **Local Persistence**: Saves training maxes, settings, set completions, and custom logs to browser storage (`localStorage`).

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation & Local Setup

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

Open your browser to `http://localhost:5173`.

### Production Build

```bash
npm run build
```

The output bundle will be generated in the `dist/` directory, ready to deploy to GitHub Pages, Vercel, Netlify, or any static host.

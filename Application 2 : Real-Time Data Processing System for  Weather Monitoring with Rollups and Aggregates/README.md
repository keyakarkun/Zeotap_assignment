# Weather Monitoring System

A real-time weather monitoring dashboard that tracks weather conditions across major Indian metros.

## Features

- Real-time weather data from OpenWeatherMap API
- Temperature monitoring and conversion (Kelvin to Celsius)
- Daily weather summaries with aggregates
- Configurable alert thresholds
- Beautiful visualizations using Recharts
- Responsive design with Tailwind CSS

## Prerequisites

- Node.js 16+
- OpenWeatherMap API key

## Setup

1. Clone the repository
2. Create a `.env` file in the root directory with your OpenWeatherMap API key:
   ```
   VITE_OPENWEATHER_API_KEY=your_api_key_here
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Design Choices

- **React + TypeScript**: For type safety and better developer experience
- **Tailwind CSS**: For rapid UI development and consistent styling
- **Recharts**: For beautiful, responsive data visualizations
- **date-fns**: For efficient date manipulation
- **Lucide React**: For consistent, beautiful icons

## Architecture

The application follows a modular architecture:

- `components/`: Reusable UI components
- `types/`: TypeScript interfaces
- `utils/`: Helper functions
- `config/`: Configuration constants

## Testing

Run the test suite:

```bash
npm test
```

## Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## License

MIT
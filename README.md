# ChakauyaFxSignals

A professional forex trading signals platform built with React, TypeScript, and the Deriv API. The platform provides real-time trading signals with technical analysis, stop loss, and take profit levels.

## Features

- Real-time forex price updates via Deriv WebSocket API
- Technical analysis using multiple indicators (RSI, MACD, SMA)
- Automated trading signals with strength indicators
- Stop loss and take profit calculations
- User authentication and preferences
- Price alerts system
- Responsive design for all devices

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- Deriv API
- Supabase
- Technical Indicators Library
- Lightweight Charts
- Zustand for state management

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with your credentials:
   ```
   VITE_DERIV_APP_ID=your_deriv_app_id
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Deployment

The application is deployed on Netlify and can be accessed at: https://sensational-parfait-429282.netlify.app

## License

MIT
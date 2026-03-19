# Mono Trade AI Journal

## Project Overview
Mono Trade AI Journal is a comprehensive trading journal application designed to help traders keep track of their trades, analyze their performance, and improve their trading strategies with the assistance of AI.

## Features
- **Dashboard**: An interactive dashboard displaying key metrics and performance summaries.
- **Trade Journal**: A detailed log of all trades executed, including entry and exit points, profits/losses, and notes.
- **AI Assistant**: An intelligent assistant providing insights and recommendations based on trading patterns.
- **Playbook**: A customizable playbook to outline trading strategies and setups.
- **Economic Calendar**: A calendar showing important economic events that might impact trading.

## Tech Stack
- React
- TypeScript
- Tailwind CSS
- Vite
- Supabase

## Prerequisites
- Node.js (v14 or later)
- npm (v6 or later)
- API keys for external services (e.g., trading platforms, data providers)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/martxvr/monotrade-ai-journal-showcase
   cd monotrade-ai-journal-showcase
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Setup environment variables (see Configuration section below).

## Configuration
- Create a `.env` file in the root of the project and add the required API keys:
  ```
  REACT_APP_API_KEY=your_api_key_here
  ```

## Development
- To run the application locally, execute:
  ```bash
  npm run dev
  ```
- Open your browser and navigate to `http://localhost:3000`.

## Project Structure
```
monotrade-ai-journal-showcase/
├── public/            # Static assets
├── src/               # Main application source
│   ├── components/    # React components
│   ├── hooks/         # Custom hooks
│   ├── pages/         # Application pages
│   └── utils/         # Utility functions
├── .env               # Environment variables
├── package.json       # NPM configuration
└── README.md          # Project documentation
```

## Components
- **Dashboard**: Main landing page summarizing key metrics.
- **TradeJournal**: Interface for logging and reviewing trades.
- **AIComponent**: Displays insights and recommendations from the AI assistant.
- **Playbook**: Allows users to define and manage their trading strategies.
- **Calendar**: Displays upcoming economic events.

## Architecture
- The application follows a component-based architecture, ensuring modularity and reusability. 
- Data flow is managed using React Context API for state management, with local storage for simple use cases and Supabase for cloud storage solutions.

## Security
- Sensitive data, such as API keys, are handled securely using environment variables. Ensure they are not exposed in public repositories.

## Contributing
- Contributions are welcome! Please submit a pull request with a clear description of your changes.

## Support
For support, contact: info@forthscaling.com.

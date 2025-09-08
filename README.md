# AI-Powered Intelligent Pesticide Sprinkling System

A modern web application for plant disease detection and automated pesticide recommendations using AI/ML technologies.

## Features

- **Live Camera Feed**: Real-time camera access with capture functionality
- **Image Upload**: Upload plant leaf images for analysis
- **AI Detection**: Machine learning-based plant disease detection
- **Severity Assessment**: 0-5 scale severity rating system
- **Pesticide Recommendations**: Automated spray intensity suggestions
- **Control Panel**: Manual and automatic spray control modes
- **Analytics Dashboard**: Real-time statistics and historical logs
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Technology Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **ML/AI**: TensorFlow.js with MobileNet
- **Build Tool**: Vite
- **Camera Access**: WebRTC getUserMedia API

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

1. **Camera Mode**: Click "Start Camera" to begin live feed, then "Capture & Analyze"
2. **Upload Mode**: Switch to "Upload Image" tab and drag/drop or select plant images
3. **Analysis**: The AI will detect disease severity and recommend pesticide intensity
4. **Control**: Use manual spray controls or enable auto mode for automatic treatment
5. **Monitoring**: View real-time statistics and historical logs in the dashboard

## Project Structure

```
src/
├── components/          # React components
├── hooks/              # Custom React hooks
├── types/              # TypeScript type definitions
├── utils/              # Utility functions
└── App.tsx             # Main application component
```

## License

MIT License
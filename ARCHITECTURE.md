# Architecture

## Overview

IICFINAL is a browser-based plant disease analysis interface built with React and TypeScript. The application combines image/camera input, client-side ML inference, treatment recommendations, spray controls, and analytics-oriented UI.

## Runtime flow

```text
Camera / Image Upload
        |
        v
   Image Capture
        |
        v
 TensorFlow.js + MobileNet
        |
        v
 Disease / Severity Result
        |
        v
 Recommendation + Control UI
        |
        v
 Analytics / History
```

## Main technologies

- React 18 + TypeScript for the UI
- Vite for development and production builds
- TensorFlow.js + MobileNet for browser-side ML
- `react-webcam` for camera input
- Tailwind CSS for styling
- Recharts for data visualization
- ESLint for code-quality checks

## Engineering notes

The project keeps inference in the client application, avoiding a mandatory application server for the demonstrated workflow. This makes the prototype straightforward to run locally and provides a useful foundation for later separation of the ML service, device-control layer, and persistence layer.

## Future production hardening

For production deployment, the next engineering steps would include a validated disease-classification model, server-side persistence and authentication, explicit safety validation for treatment recommendations, hardware integration behind a controlled API, automated tests, and CI checks.

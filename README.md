# P4 Science Explorer

A comprehensive interactive Singapore Primary 4 Science learning application featuring AI-powered image generation and text-to-speech capabilities.

## Features

- **12 Science Topics**: Comprehensive curriculum covering Primary 4 Singapore science standards
- **Interactive Learning**: 5 tabs per topic (Lesson, Vocabulary, Experiment, Fun Facts, Quiz)
- **Text-to-Speech**: Web Speech API integration for pronunciation support
- **AI-Powered Images**: Higgsfield API integration for generating contextual images
- **Progress Tracking**: localStorage-based progress persistence across sessions
- **Achievement System**: Badge-based completion tracking
- **Offline Support**: Cached images and data enable offline functionality
- **Responsive Design**: Mallow design system with neo-brutalist styling

## Deployment

### Environment Variables

The following environment variable must be set on Vercel:

- `HIGGSFIELD_API_KEY`: API key for image generation service

### Live

Deployed at: https://p4-science.vercel.app

## Development

### Local Testing

1. Open `p4-science.html` directly in a browser
2. Application uses localStorage for state persistence
3. Images are cached in localStorage for offline access

### Browser Requirements

- Modern browser with Web Speech API support (Chrome, Edge, Safari)
- ES6+ JavaScript support
- localStorage enabled

## Architecture

- **Single-file SPA**: Complete application in one HTML file
- **Framework**: Vanilla JavaScript with Web Storage API
- **Styling**: CSS Grid and Flexbox with Mallow design system
- **API Integration**: Higgsfield API for image generation with fallback support

## Topics Covered

1. Classification of Living Things
2. Human Body and Health
3. Reproduction in Plants and Animals
4. Growth and Development
5. Adaptations and Survival
6. Ecosystems and Food Chains
7. Energy and Heat
8. Light and Shadows
9. Forces and Motion
10. Simple Machines
11. Materials and Their Properties
12. Water Cycle and Weather

## License

Private project for educational use.

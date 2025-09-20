# SafeRoute - Safety-First Navigation Prototype

A comprehensive web application that provides intelligent route planning with real-time safety assessment, helping users make informed decisions about their travel routes and transportation modes.

## 🚀 Features

### Core Functionality
- **Interactive Mapping**: Powered by Leaflet.js with OpenStreetMap tiles
- **Route Planning**: Integration with OpenRouteService API for accurate routing
- **Risk Assessment**: Multi-factor safety analysis including:
  - Heat map data
  - Crowd density
  - Weather conditions
  - Incident reports
- **Mode Recommendations**: Smart suggestions for walking, cycling, metro, or cab
- **Incident Reporting**: Community-driven safety reporting system
- **Dark Mode**: Toggle between light and dark themes

### Safety Features
- **Risk Visualization**: Color-coded risk zones (Safe, Moderate, High, Danger)
- **Heatmap Overlay**: Visual representation of high-risk areas
- **Real-time Weather**: Weather-based risk assessment
- **Community Reports**: User-reported incidents and hazards
- **Route Analysis**: Detailed risk breakdown for each route

## 🛠️ Setup Instructions

### Prerequisites
1. **OpenRouteService API Key**: Get your free API key from [OpenRouteService](https://openrouteservice.org/)
2. **OpenWeatherMap API Key** (Optional): Get your free API key from [OpenWeatherMap](https://openweathermap.org/api)

### Installation
1. Clone or download this repository
2. Open `index.html` in a modern web browser
3. Enter your API keys in the top navigation bar
4. Start planning safe routes!

## 📱 How to Use

### Basic Navigation
1. **Enter Locations**: Type your starting point and destination
2. **Add API Keys**: Enter your OpenRouteService API key (required)
3. **Click "Go"**: The app will calculate the safest route
4. **View Recommendations**: See suggested transportation modes

### Safety Features
- **Report Incidents**: Click the warning button (⚠️) to report hazards
- **View Heatmap**: Toggle the heatmap to see risk density
- **Check Risk Zones**: Click anywhere on the map to see local risk levels
- **Dark Mode**: Switch to night mode for better visibility

### Incident Types
- 🚨 **Accident**: Traffic accidents or collisions
- 🕳️ **Pothole**: Road surface damage
- 💡 **Poor Lighting**: Insufficient street lighting
- 👥 **Crowd Surge**: High pedestrian density
- 🚧 **Construction**: Road work or construction zones
- ⚠️ **Crime Alert**: Security concerns

## 🎨 UI Components

### Top Navigation Bar
- **Location Inputs**: Start and destination fields
- **API Key Fields**: OpenRouteService and OpenWeatherMap keys
- **Control Buttons**: Heatmap, Dark mode, and Clear functions

### Floating Action Buttons
- **Report Button** (⚠️): Access incident reporting
- **Clear Button** (🧹): Remove risk zones

### Mode Recommendation Card
- **Smart Suggestions**: AI-powered transportation recommendations
- **Risk Analysis**: Detailed safety breakdown
- **Mode Buttons**: Quick selection of transportation options

### Risk Legend
- **Color Coding**: Visual guide to risk levels
- **Risk Factors**: Explanation of safety calculations

## 🔧 Technical Details

### APIs Used
- **OpenRouteService**: Route calculation and navigation
- **OpenWeatherMap**: Weather data for risk assessment
- **Nominatim**: Geocoding and address resolution

### Risk Calculation
The safety score combines multiple factors:
- **Heat Risk** (30%): Historical incident data
- **Crowd Risk** (30%): Pedestrian density
- **Weather Risk** (20%): Current weather conditions
- **Incident Risk** (20%): User-reported incidents

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🚧 Development Notes

### Mock Data
The prototype includes simulated data for demonstration:
- Heat points around Delhi area
- Crowd density data
- Sample incident reports
- Weather risk simulation

### Customization
- Modify `heatPoints` array for different heat data
- Adjust risk calculation weights in `calculateRisk()`
- Add new incident types in the UI
- Customize map styling and markers

## 📈 Future Enhancements

### Planned Features
- **Real-time Data**: Live traffic and incident feeds
- **User Accounts**: Personalized safety preferences
- **Mobile App**: Native iOS and Android applications
- **Machine Learning**: Improved risk prediction algorithms
- **Social Features**: Community safety ratings and reviews

### API Integrations
- **Google Maps**: Alternative mapping service
- **Traffic APIs**: Real-time congestion data
- **Crime APIs**: Official crime statistics
- **Public Transport**: Real-time transit information

## 🤝 Contributing

This is a prototype for demonstration purposes. For production use:
1. Implement proper error handling
2. Add input validation and sanitization
3. Optimize API calls and caching
4. Add comprehensive testing
5. Implement security measures

## 📄 License

This project is for educational and demonstration purposes. Please ensure you comply with the terms of service for all integrated APIs.

## 🆘 Support

For questions or issues:
1. Check the browser console for error messages
2. Verify your API keys are correct and active
3. Ensure you have a stable internet connection
4. Try refreshing the page if features don't load

---

**SafeRoute** - Making every journey safer, one route at a time. 🛡️

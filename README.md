# 🌍 Tectonix - Exploring Earth's Tremor

**An interactive browser-based educational platform that makes earthquake science engaging and accessible for students through real-time data visualization and interactive learning.**

## 📌 Problem Statement

Traditional earthquake education relies heavily on static textbooks and theoretical concepts, making it difficult for students to understand the dynamic nature of seismic activity. Students lack access to:

- Interactive tools to visualize real earthquake data
- Engaging platforms that combine learning with exploration
- Accessible resources that make complex seismic science intuitive
- Real-time connection between theoretical knowledge and actual geological events

## 🎯 Our Solution

Tectonix bridges the gap between data science and education by providing a **browser-based interactive platform** that transforms earthquake learning from static textbooks to an engaging, data-driven experience. Students can explore, analyze, and understand earthquakes through:

- Real-time earthquake data visualization
- Interactive maps showing global seismic activity
- Customizable filters and analysis tools
- Educational overlays and gamified learning experiences

## ✨ Key Features

### 🌍 Interactive Earthquake Map
- Real-time visualization of global earthquake activity
- Color-coded markers based on magnitude and depth
- Clickable earthquake points with detailed information
- Multiple map layers (satellite, terrain, street view)

### 📈 Data Visualization & Analytics
- Interactive charts showing magnitude distribution
- Time-series analysis of seismic activity
- Depth vs. magnitude scatter plots
- Regional earthquake frequency analysis

### 🔍 Advanced Filtering System
- **Geographic Filters**: Select specific regions, countries, or coordinates
- **Temporal Filters**: Filter by date ranges, recent activity, or historical events
- **Magnitude Filters**: Focus on specific intensity ranges
- **Depth Filters**: Analyze shallow vs. deep earthquakes

### 🎓 Educational Learning Overlays
- Tectonic plate boundaries visualization
- Seismic zones and fault line mapping
- Educational pop-ups explaining earthquake science
- Interactive tutorials and guided explorations

### 🎮 Gamified Learning Experience
- Knowledge-testing quizzes after exploration sessions
- Achievement badges for discovering earthquake patterns
- Interactive challenges to identify high-risk zones
- Progress tracking for educational milestones

### 📱 Responsive Design
- Mobile-friendly interface for learning on-the-go
- Touch-optimized controls for tablets
- Cross-browser compatibility

## 🛠️ Technology Stack

### Frontend
- **React.js** - Modern, component-based UI framework
- **HTML5/CSS3/JavaScript** - Core web technologies
- **Tailwind CSS** - Utility-first CSS framework for rapid styling

### Mapping & Visualization
- **Leaflet.js / Mapbox GL JS** - Interactive mapping library
- **D3.js / Chart.js** - Data visualization and charting
- **GeoJSON** - Geographic data format

### Data Sources
- **USGS Earthquake API** - Real-time earthquake data
- **USGS GeoJSON Feeds** - Standardized earthquake datasets
- **Tectonic Plates Data** - Geographic boundary information

### Optional Backend
- **Node.js** - Server-side JavaScript runtime
- **Express.js** - Web application framework
- **Python** - Data processing and analysis scripts

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/j005d/SkyNet.git
   cd tectonix
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Add your API keys for mapping services (if required)
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Open your browser**
   Navigate to `http://demohost:3000` to start exploring!

### Quick Demo

1. **Explore Recent Earthquakes**: The map loads with recent global earthquake activity
2. **Filter by Region**: Use the sidebar to focus on specific geographic areas
3. **Analyze Patterns**: Click on visualization charts to understand earthquake distributions
4. **Learn Interactively**: Enable educational overlays to see tectonic plates and seismic zones
5. **Test Your Knowledge**: Complete mini-quizzes to reinforce learning

## 📊 Data Sources & APIs

### Primary Data Source
- **USGS Earthquake Hazards Program**
  - Real-time feeds: `https://earthquake.usgs.gov/earthquakes/feed/`
  - Historical data access
  - Multiple format support (GeoJSON, CSV, XML)

### Additional Resources
- **Global Seismic Hazard Assessment Program (GSHAP)**
- **International Seismological Centre (ISC)**
- **Tectonic plate boundary datasets**

## 🎓 Educational Impact

### For Students
- **Visual Learning**: Transform abstract concepts into visual, interactive experiences
- **Real-World Connection**: Connect classroom theory with actual geological events
- **Critical Thinking**: Develop analytical skills through data exploration
- **Global Awareness**: Understand earthquake patterns and disaster preparedness

### for Educators
- **Curriculum Integration**: Align with earth science and geography standards
- **Assessment Tools**: Built-in quizzes and progress tracking
- **Customizable Content**: Adapt lessons for different grade levels
- **Engagement Metrics**: Track student interaction and learning progress

## 🌟 Future Roadmap

### Phase 2 Enhancements
- **3D Visualization**: Interactive 3D models of tectonic plate movements
- **Augmented Reality (AR)**: Overlay earthquake data on real-world environments
- **Virtual Reality (VR)**: Immersive earthquake simulation experiences
- **Multi-language Support**: Localization for global educational access

### Phase 3 Expansion
- **Volcano Integration**: Expand to volcanic activity monitoring and education
- **Tsunami Modeling**: Add tsunami risk assessment and wave propagation visualization
- **Climate Connections**: Explore relationships between seismic activity and climate patterns
- **Collaborative Features**: Enable classroom collaboration and data sharing

### Phase 4 Advanced Features
- **Machine Learning Predictions**: Implement basic earthquake pattern recognition
- **Historical Timeline**: Interactive timeline of significant earthquakes
- **Risk Assessment Tools**: Personal and regional earthquake preparedness calculators
- **API Integration**: Connect with school management systems and learning platforms

## 🤝 Contributing

We welcome contributions from educators, developers, and earth science enthusiasts! Here's how you can help:

### Ways to Contribute
- **Feature Development**: Add new visualization types or educational tools
- **Content Creation**: Develop educational content and quiz questions
- **Bug Fixes**: Report and fix issues to improve user experience
- **Documentation**: Improve guides and educational materials
- **Translation**: Help localize content for different languages

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Style Guidelines
- Follow ESLint configuration for JavaScript/React code
- Use meaningful variable names and comments
- Write unit tests for new features
- Ensure responsive design compatibility

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **USGS Earthquake Hazards Program** for providing comprehensive earthquake data APIs
- **OpenStreetMap Contributors** for open-source mapping data
- **Educational consultants** who provided pedagogical guidance
- **Beta testers** from schools and educational institutions worldwide

## 📞 Contact & Support

- **Project Lead**: [Jaishnav Das] - jaishnavdas005@gmail.com
- **Project Members**: [Prateek Debnath, Rahul Ahmen, Biswarup Goswami]
- **Documentation**: Visit our [Github](https://github.com/j005d/SkyNet)

**Made with ❤️ for earthquake education and disaster awareness**

*Transform earthquake education from static textbooks to an engaging, data-driven, interactive experience with Tectonix!*

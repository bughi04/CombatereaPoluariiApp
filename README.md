# 🌍 CombatereaPoluariiApp - EcoApp România

[![Java](https://img.shields.io/badge/Java-11-orange.svg)](https://www.oracle.com/java/)
[![Maven](https://img.shields.io/badge/Maven-3.x-blue.svg)](https://maven.apache.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![UI Framework](https://img.shields.io/badge/UI-Swing-brightgreen.svg)](https://docs.oracle.com/javase/tutorial/uiswing/)
[![AI Powered](https://img.shields.io/badge/AI-Google%20Gemini-purple.svg)](https://ai.google.dev/)

> **Comprehensive Environmental Platform for Pollution Awareness and Mitigation in Romania**

A sophisticated Java Swing application that combines artificial intelligence, academic research, and interactive visualizations to educate users about environmental protection and provide practical solutions for reducing pollution in Romania.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Architecture](#-architecture)
- [API Integration](#-api-integration)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

**CombatereaPoluariiApp** is an innovative environmental awareness platform designed specifically for the Romanian context. The application integrates cutting-edge AI technology with academic research databases to provide users with:

- **Real-time pollution data** for major Romanian cities
- **AI-powered environmental Q&A** using Google Gemini API
- **Academic article search** from multiple scientific databases
- **Interactive carbon footprint calculator**
- **Educational quizzes** with difficulty levels
- **Practical eco-tips** for sustainable living
- **Data visualization** showing pollution trends over time

The application aims to empower Romanian citizens with knowledge and practical tools to contribute to environmental protection and pollution reduction.

---

## ✨ Key Features

### 🤖 AI-Powered Features

#### 1. **Intelligent Q&A Assistant**
- Specialized AI chatbot for environmental questions
- Context-aware responses about Romanian environmental policies
- Integration with Google Gemini 1.5 Flash API
- Supports queries about:
  - Climate change and CO2 emissions
  - Renewable energy solutions
  - Waste management and recycling
  - Sustainable agriculture
  - Water and soil protection

#### 2. **AI Article Summaries**
- Automatic generation of research paper summaries
- Extracts key insights from scientific articles
- Provides practical applications for Romanian context
- Multi-tab interface showing:
  - Full summary
  - AI-generated condensed summary
  - Key points extraction

### 📚 Academic Research Integration

#### 3. **Scientific Article Search**
- Multi-source academic database integration:
  - **Semantic Scholar API** - Open academic search
  - **CrossRef API** - DOI-based scholarly content
  - **CORE API** - Open access research papers
- Advanced filtering by:
  - Source (Google Scholar, PubMed, All)
  - Environmental keywords
  - Publication date
- Direct links to original papers
- Citation information and abstracts

#### 4. **Curated Environmental Articles**
- Pre-loaded scientific articles on:
  - CO2 reduction through renewable energy
  - Sustainable urban transportation
  - Waste management and circular economy
  - Air purification through urban green spaces
  - Water pollution and ecological treatment
  - Sustainable agriculture
- Each article includes:
  - Full citation with authors and year
  - Detailed summary
  - Practical action items
  - Google Scholar links

### 🌱 Environmental Tools

#### 5. **Carbon Footprint Calculator**
- Comprehensive CO2 emission calculation based on:
  - **Transportation**: car, flights, bus, train kilometers
  - **Energy**: electricity and gas consumption
  - **Lifestyle**: dietary choices (omnivore, vegetarian, vegan)
- Personalized recommendations for reduction
- Comparison with Romanian national average (4.5 tons/year)
- Visual breakdown by category
- Target alignment with Paris Agreement goals

#### 6. **Interactive Pollution Map**
- Real-time Air Quality Index (AQI) for 10 Romanian cities:
  - București, Cluj-Napoca, Timișoara, Iași, Constanța
  - Brașov, Galați, Ploiești, Craiova, Oradea
- Detailed pollutant measurements:
  - PM2.5 and PM10 (particulate matter)
  - NO2 (nitrogen dioxide)
  - CO (carbon monoxide)
- Color-coded city markers (green/orange/red)
- Health recommendations based on air quality
- Visual map with city locations

#### 7. **Pollution Trends Analyzer**
- Historical data visualization with line charts
- Customizable parameters:
  - Pollutant type (PM2.5, PM10, NO2, SO2, CO, O3)
  - City selection
  - Time range (week, month, 3 months, year)
- Statistical analysis:
  - Average, maximum, minimum values
  - Trend detection (increasing/decreasing/stable)
  - Percentage changes over time
- AI-generated insights and recommendations

### 📖 Educational Features

#### 8. **Environmental Quiz**
- Three difficulty levels:
  - **Easy**: Basic environmental concepts
  - **Medium**: Romanian environmental policies and data
  - **Advanced**: Technical climate science and statistics
- 25+ questions covering:
  - Climate change
  - Renewable energy
  - Pollution types and sources
  - Romanian environmental programs
  - Biodiversity and conservation
- Immediate feedback with explanations
- Performance scoring and tracking
- Personalized recommendations

#### 9. **Daily Eco-Tips**
- 25+ practical tips for sustainable living
- Categories include:
  - Energy efficiency
  - Water conservation
  - Transportation
  - Recycling
  - Food and agriculture
  - Technology and digital footprint
- Each tip includes:
  - Specific Romanian data and context
  - Measurable impact (CO2 saved, money saved)
  - Actionable steps
  - Government programs (Casa Verde, Rabla Plus)
- Random tip generator
- Category filtering
- Visual statistics dashboard

### 💡 Practical Solutions

#### 10. **Solutions Hub**
- 50+ practical solutions organized by category:
  - 🏠 **Home**: Energy efficiency, insulation, recycling
  - 🚗 **Transportation**: Electric vehicles, public transport, cycling
  - 🏢 **Office**: Digitalization, energy management, telecommuting
  - 🌳 **Community**: Tree planting, education, advocacy
  - 💧 **Water Protection**: Filtration, conservation, pollution prevention
  - 🌾 **Sustainable Agriculture**: Organic farming, biodiversity
- Each solution includes:
  - Detailed description with Romanian context
  - Quantified benefits (energy savings, CO2 reduction)
  - Cost information and ROI
  - Government incentive programs
  - Implementation steps

### 🎨 User Experience

#### 11. **Modern UI/UX**
- **Dual Theme Support**:
  - Light mode: Clean, bright interface
  - Dark mode: Reduced eye strain for extended use
- Smooth transitions and animations
- Gradient backgrounds and modern card designs
- Custom-styled buttons with hover effects
- Responsive layouts adapting to window size
- Intuitive navigation with dropdown menus

#### 12. **Multi-Panel Architecture**
- Home dashboard with key statistics
- Easy navigation between features
- Breadcrumb navigation
- Context-sensitive help
- Welcome dialog on first launch
- Feature tours for new users

---

## 🔧 Technology Stack

### Core Technologies
- **Java 11** - Modern Java features and stability
- **Swing** - Rich desktop UI framework
- **Maven 3.x** - Dependency management and build automation

### Libraries & Dependencies

#### UI & Graphics
- **Java AWT/Swing** - Native UI components
- Custom graphics with `Graphics2D` for:
  - Gradient backgrounds
  - Rounded corners
  - Shadow effects
  - Chart rendering

#### Data Processing
- **org.json (20231013)** - JSON parsing for API responses
- Custom data models for articles, search results, quiz questions

#### Logging
- **SLF4J 2.0.9** - Logging facade
- **Logback 1.4.11** - Logging implementation

#### Testing
- **JUnit Jupiter 5.10.0** - Unit testing framework

### External APIs

#### AI Integration
- **Google Gemini 1.5 Flash API** 
  - Natural language processing
  - Environmental question answering
  - Article summarization
  - Context-aware responses

#### Academic Research
- **Semantic Scholar API**
  - Open academic paper search
  - Citation metadata
  - Author information
  
- **CrossRef API**
  - DOI-based lookup
  - Publication metadata
  - Journal information
  
- **CORE API**
  - Open access research papers
  - Full-text search
  - Download links

### Design Patterns
- **MVC Architecture** - Separation of concerns
- **Service Layer Pattern** - Business logic isolation
- **Repository Pattern** - Data access abstraction
- **Observer Pattern** - UI updates and events
- **Factory Pattern** - UI component creation
- **Strategy Pattern** - Algorithm selection (AI responses)
- **CardLayout Pattern** - Multi-panel navigation

---

## 📥 Installation

### Prerequisites

Before installing CombatereaPoluariiApp, ensure you have:

- **Java Development Kit (JDK) 11 or higher**
  ```bash
  java -version  # Should show version 11 or higher
  ```

- **Apache Maven 3.x**
  ```bash
  mvn -version  # Should show Maven 3.x
  ```

- **Git** (for cloning the repository)
  ```bash
  git --version
  ```

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/CombatereaPoluariiApp.git
cd CombatereaPoluariiApp
```

### Step 2: Configure API Keys

The application requires a Google Gemini API key for AI features.

1. Get a free API key from [Google AI Studio](https://makersuite.google.com/app/apikey)

2. Open the file:
   ```
   src/main/java/org/example/combatereapoluariiapp/src/service/AIService.java
   ```

3. Find the line:
   ```java
   private static final String API_KEY = "";
   ```

4. Replace with your API key:
   ```java
   private static final String API_KEY = "YOUR_GEMINI_API_KEY_HERE";
   ```

### Step 3: Build the Project

```bash
# Clean and compile the project
mvn clean compile

# Run tests (optional)
mvn test

# Package the application
mvn package
```

This will create an executable JAR file in the `target/` directory.

### Step 4: Run the Application

#### Option A: Using Maven
```bash
mvn exec:java -Dexec.mainClass="org.example.combatereapoluariiapp.src.CombatereaPoluariiApp"
```

#### Option B: Using JAR file
```bash
java -jar target/combatereapoluariiapp-1.0.0.jar
```

#### Option C: Using Maven wrapper (recommended)
```bash
# Unix/Linux/Mac
./mvnw exec:java

# Windows
mvnw.cmd exec:java
```

### Optional: Create Desktop Shortcut

**Windows:**
1. Right-click on `combatereapoluariiapp-1.0.0.jar`
2. Create shortcut
3. Move to Desktop

**Linux:**
Create a `.desktop` file:
```ini
[Desktop Entry]
Name=EcoApp România
Comment=Environmental Awareness Platform
Exec=java -jar /path/to/combatereapoluariiapp-1.0.0.jar
Icon=/path/to/icon.png
Terminal=false
Type=Application
Categories=Education;Science;
```

**macOS:**
Create an Automator application or use the JAR directly.

---

## 🚀 Usage

### First Launch

When you first launch the application, you'll see:

1. **Welcome Dialog** - Overview of features
2. **Home Dashboard** - Statistics and introduction
3. **Theme Selection** - Choose light or dark mode (☀️/🌙 button)

### Navigation

The application uses a **top navigation bar** with these sections:

#### Main Navigation
- 🏠 **Acasă** (Home) - Dashboard with statistics
- 📚 **Articole** (Articles) - Scientific articles with AI summaries
- 💡 **Soluții** (Solutions) - Practical environmental solutions
- 🔍 **Căutare** (Search) - Search academic databases
- 🤖 **AI Q&A** - Chat with the environmental AI assistant
- ℹ️ **Despre** (About) - Information about the project

#### Feature Dropdowns
- 🌱 **Funcții Eco** (Eco Features)
  - 🧮 Calculator Carbon - Calculate your carbon footprint
  - 🗺️ Harta Poluării - View air quality in Romanian cities
  - 💡 Sfaturi Eco Zilnice - Get daily eco-friendly tips

- 📊 **Date & Quiz** (Data & Quiz)
  - 📈 Evoluția Poluării - View pollution trends over time
  - 🧠 Quiz Ecologic - Test your environmental knowledge

### Feature Guides

#### Using the Carbon Calculator

1. Navigate to **Funcții Eco** → **Calculator Carbon**
2. Enter your annual data:
   - Transportation (km by car, flight, bus, train)
   - Home energy (kWh of electricity and gas per month)
   - Diet type (omnivore, vegetarian, vegan)
3. Click **🧮 Calculează** (Calculate)
4. Review your results:
   - Total CO2 footprint
   - Breakdown by category
   - Personalized recommendations
5. Compare with Romanian average (4.5 tons/year)

#### Searching Academic Articles

1. Navigate to **🔍 Căutare** (Search)
2. Enter environmental keywords (e.g., "renewable energy pollution")
3. Select source:
   - Toate sursele (All sources) - Comprehensive
   - Google Scholar - Academic papers
   - PubMed - Medical/health research
4. Click **🔍 Caută** (Search)
5. Browse results with:
   - Title, authors, and year
   - Abstract preview
   - Citation source
6. Click **📖 Deschide Articol** to read full paper

#### Chatting with the AI Assistant

1. Navigate to **🤖 AI Q&A**
2. Read the tips for better questions
3. Type your environmental question (e.g., "Cum pot reduce energia acasă?")
4. Press **Enter** or click **🤖 Întreabă**
5. The AI will:
   - Analyze your question
   - Search its environmental knowledge
   - Provide a detailed answer with Romanian context
   - Include specific programs (Casa Verde, Rabla Plus)
   - Suggest actionable steps

Example questions:
- "Care sunt cele mai bune panouri solare pentru România?"
- "Cum pot reduce emisiile de CO2 din transport?"
- "Ce programe guvernamentale există pentru eficiență energetică?"

#### Taking the Environmental Quiz

1. Navigate to **Date & Quiz** → **Quiz Ecologic**
2. Select difficulty:
   - **UȘOR**: Basic concepts (recycling, climate basics)
   - **MEDIU**: Romanian data and policies
   - **AVANSAT**: Technical details and statistics
3. Click **🚀 Începe Quiz-ul**
4. Answer 10 questions:
   - Read each question carefully
   - Select one answer
   - Click **Următoarea** (Next)
5. Read explanations after each question
6. View final score and recommendations

#### Viewing Pollution Trends

1. Navigate to **Date & Quiz** → **Evoluția Poluării**
2. Configure parameters:
   - **Poluant**: Select pollutant (PM2.5, PM10, NO2, SO2, CO, O3)
   - **Oraș**: Choose Romanian city
   - **Perioada**: Set time range
3. Click **📊 Actualizează** (Update)
4. Analyze the interactive chart:
   - Line graph showing values over time
   - Statistical summary (average, max, min)
   - Trend analysis (increasing/decreasing)
   - AI-generated insights

### Tips for Best Experience

- **Use Dark Mode** for evening usage (reduces eye strain)
- **Enable AI Features** by adding your Gemini API key
- **Explore All Tabs** in the Articles section for full insights
- **Take the Quiz** at different difficulty levels to learn progressively
- **Share Articles** using the built-in sharing feature
- **Calculate Your Footprint** monthly to track improvements
- **Read Daily Tips** for continuous learning

---

## 🏗️ Architecture

### Project Structure

```
combatereapoluariiapp/
├── src/
│   └── main/
│       ├── java/
│       │   ├── module-info.java
│       │   └── org/example/combatereapoluariiapp/src/
│       │       ├── CombatereaPoluariiApp.java      # Main entry point
│       │       ├── constants/
│       │       │   └── ThemeConstants.java         # UI colors and themes
│       │       ├── data/
│       │       │   └── DataRepository.java         # Static data storage
│       │       ├── model/
│       │       │   ├── Article.java                # Article data model
│       │       │   ├── SearchResult.java           # Search result model
│       │       │   └── CarbonFootprintCalculator.java  # Calculator logic
│       │       ├── service/
│       │       │   ├── AIService.java              # Google Gemini integration
│       │       │   └── ArticleSearchService.java   # Multi-API search
│       │       └── ui/
│       │           ├── MainFrame.java              # Main window
│       │           ├── UIUtils.java                # Reusable UI components
│       │           └── panels/
│       │               ├── HomePanel.java          # Dashboard
│       │               ├── ArticlesPanel.java      # Basic articles
│       │               ├── EnhancedArticlesPanel.java  # AI-powered articles
│       │               ├── SolutionsPanel.java     # Practical solutions
│       │               ├── ArticleSearchPanel.java # Search interface
│       │               ├── QAPanel.java            # AI chat
│       │               ├── CarbonCalculatorPanel.java  # Carbon calc
│       │               ├── PollutionMapPanel.java  # Air quality map
│       │               ├── PollutionTrendsPanel.java  # Data charts
│       │               ├── EcoTipsPanel.java       # Daily tips
│       │               ├── EnvironmentalQuizPanel.java # Quiz
│       │               └── AboutPanel.java         # About info
│       └── resources/
├── target/                   # Compiled classes and JAR
├── pom.xml                   # Maven configuration
├── mvnw                      # Maven wrapper (Unix)
├── mvnw.cmd                  # Maven wrapper (Windows)
└── README.md                 # This file
```

### Design Patterns Used

#### 1. **Model-View-Controller (MVC)**
- **Model**: `Article`, `SearchResult`, `CarbonResult`
- **View**: All `*Panel` classes in `ui.panels`
- **Controller**: `MainFrame`, service classes

#### 2. **Service Layer**
- `AIService` - Handles all AI interactions
- `ArticleSearchService` - Manages API calls
- Isolates business logic from UI

#### 3. **Repository Pattern**
- `DataRepository` - Centralized data access
- Static methods for articles and solutions
- Easy to extend with database later

#### 4. **Factory Pattern**
- `UIUtils.createStyledButton()` - Button creation
- `UIUtils.createStatCard()` - Stat card creation
- Ensures consistent UI elements

#### 5. **Observer Pattern**
- Event listeners on buttons
- Combo box listeners for dynamic updates
- CompletableFuture for async operations

#### 6. **Strategy Pattern**
- Multiple search strategies (Semantic Scholar, CrossRef, CORE)
- Fallback mechanisms for API failures

#### 7. **CardLayout Pattern**
- `MainFrame` uses CardLayout for panel switching
- Smooth transitions between features
- Memory-efficient (only active panel rendered)

### Component Relationships

```
CombatereaPoluariiApp (Main)
    ↓
MainFrame (Window Manager)
    ├── Navigation Bar
    ├── Theme Toggle
    └── CardLayout Container
        ├── HomePanel ──→ DataRepository (stats)
        ├── EnhancedArticlesPanel ──→ AIService, DataRepository
        ├── ArticleSearchPanel ──→ ArticleSearchService
        ├── QAPanel ──→ AIService
        ├── CarbonCalculatorPanel ──→ CarbonFootprintCalculator
        ├── PollutionMapPanel ──→ Static city data
        ├── PollutionTrendsPanel ──→ Generated data + charts
        ├── EcoTipsPanel ──→ Static tips database
        ├── EnvironmentalQuizPanel ──→ Static questions
        └── SolutionsPanel ──→ DataRepository

Services:
    AIService
        ├── Google Gemini API
        ├── HTTP requests
        └── JSON parsing

    ArticleSearchService
        ├── Semantic Scholar API
        ├── CrossRef API
        ├── CORE API
        └── Result aggregation
```

### Data Flow

#### AI Q&A Flow
```
User Question → QAPanel → AIService → Gemini API → JSON Response 
    → Parse & Format → Update UI → Display Answer
```

#### Article Search Flow
```
Search Query → ArticleSearchPanel → ArticleSearchService
    ├── Semantic Scholar API ┐
    ├── CrossRef API         ├→ Aggregate Results → Remove Duplicates
    └── CORE API             ┘     → Sort by Relevance → Display
```

#### Carbon Calculation Flow
```
User Input → CarbonCalculatorPanel → CarbonFootprintCalculator
    ├── Transport Emissions (kg CO2)
    ├── Energy Emissions (kg CO2)
    └── Lifestyle Emissions (kg CO2)
        → Sum Total → Compare to Average → Generate Recommendations
```

### Threading Model

- **Main Thread**: UI rendering and event handling
- **CompletableFuture**: Async operations for:
  - AI API calls (prevents UI freezing)
  - Article searches (parallel API requests)
  - Heavy calculations
- **SwingUtilities.invokeLater()**: Safe UI updates from background threads

### Error Handling Strategy

1. **Network Errors**: Graceful fallbacks, retry mechanisms
2. **API Errors**: Display user-friendly messages, use cached data
3. **Invalid Input**: Validation with helpful error messages
4. **Missing API Keys**: Clear instructions for configuration

---

## 🔌 API Integration

### Google Gemini API

#### Configuration
```java
// In AIService.java
private static final String API_URL = 
    "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent";
private static final String API_KEY = "YOUR_API_KEY_HERE";
```

#### Features Used
- **Natural Language Understanding**: Context-aware environmental queries
- **Romanian Language Support**: Fluent responses in Romanian
- **Specialized Prompting**: Environmental expert persona
- **Content Safety**: Built-in filtering for appropriate responses

#### Request Format
```json
{
  "contents": [{
    "parts": [{
      "text": "Customized prompt + user question"
    }]
  }],
  "generationConfig": {
    "temperature": 0.7,
    "topK": 40,
    "topP": 0.95,
    "maxOutputTokens": 1024
  },
  "safetySettings": [...]
}
```

#### Rate Limits
- Free tier: 60 requests per minute
- Application implements request queuing
- Fallback responses for quota exceeded

### Semantic Scholar API

#### Endpoint
```
https://api.semanticscholar.org/graph/v1/paper/search
```

#### Features
- Open access to 200M+ papers
- Author information and citations
- Abstracts and publication venues
- No API key required (public access)

#### Query Parameters
```
?query=<search_terms>
&limit=10
&fields=title,authors,year,abstract,url,venue
```

### CrossRef API

#### Endpoint
```
https://api.crossref.org/works
```

#### Features
- DOI-based paper lookup
- Publication metadata
- Citation information
- Journal details

#### Query Format
```
?query=<search_terms>
&rows=8
&sort=relevance
&order=desc
```

#### Best Practices
- Include User-Agent header
- Respect rate limits (50 requests/second)
- Use descriptive queries

### CORE API

#### Endpoint
```
https://api.core.ac.uk/v3/search/works
```

#### Features
- Open access research papers
- Full-text search
- Download links
- Metadata extraction

#### Query Format
```
?q=<search_terms>
&limit=5
```

### API Error Handling

All API integrations include:

1. **Timeout Handling**: 10-15 second timeouts
2. **Retry Logic**: Up to 3 retries with exponential backoff
3. **Fallback Data**: Curated content when APIs unavailable
4. **User Feedback**: Loading states and error messages
5. **Logging**: Detailed logs for debugging

---

## 📸 Screenshots

### Main Dashboard
*Home screen showing environmental statistics and call-to-action*

**Light Mode:**
- Clean, modern interface
- Vibrant colors and gradients
- Easy-to-read text

**Dark Mode:**
- Reduced eye strain
- Professional appearance
- Energy efficient for OLED screens

### Carbon Footprint Calculator
*Interactive calculator with real-time results*

Features shown:
- Input form for transportation, energy, and lifestyle
- Visual breakdown by category
- Comparison with national average
- Personalized recommendations

### Pollution Map
*Interactive map of Romania showing air quality*

Elements visible:
- City markers color-coded by AQI
- Detailed pollutant measurements
- Health recommendations
- Legend explaining air quality levels

### AI Chat Interface
*Conversational AI assistant for environmental questions*

Displays:
- Chat history with user and AI messages
- Contextual suggestions
- Romanian-language responses
- Formatted answers with bullet points

### Academic Search
*Multi-database article search interface*

Shows:
- Search bar with filters
- Results with abstracts
- Source badges (Semantic Scholar, CrossRef, CORE)
- Direct links to papers

### Environmental Quiz
*Interactive quiz with multiple difficulty levels*

Includes:
- Progress bar
- Multiple choice questions
- Immediate feedback
- Final score and recommendations

### Daily Eco-Tips
*Practical daily tips for sustainable living*

Features:
- Large tip display with icon
- Category badges
- Quick stats (money saved, CO2 reduced)
- Navigation between tips

### Pollution Trends
*Data visualization showing pollution over time*

Components:
- Interactive line chart
- Customizable parameters
- Statistical analysis
- AI-generated insights

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute

1. **Report Bugs**: Open an issue with details and reproduction steps
2. **Suggest Features**: Propose new environmental features or improvements
3. **Translate**: Help translate to other languages
4. **Improve Documentation**: Fix typos, add examples, clarify instructions
5. **Write Code**: Submit pull requests for new features or bug fixes

### Development Setup

1. Fork the repository
2. Create a feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Make your changes
4. Run tests:
   ```bash
   mvn test
   ```
5. Commit with clear messages:
   ```bash
   git commit -m "Add AmazingFeature: description"
   ```
6. Push to your fork:
   ```bash
   git push origin feature/AmazingFeature
   ```
7. Open a Pull Request

### Code Style Guidelines

- **Java Naming**:
  - Classes: `PascalCase`
  - Methods: `camelCase`
  - Constants: `UPPER_SNAKE_CASE`
- **Indentation**: 4 spaces
- **Comments**: JavaDoc for public methods
- **Max Line Length**: 120 characters

### Adding New Features

When adding new panels or features:

1. Create new panel class in `ui.panels`
2. Register in `MainFrame.initializeUI()`
3. Add navigation button if needed
4. Update this README

### Testing

- Write unit tests for business logic
- Test UI manually in both light/dark modes
- Verify API integrations with mock data
- Check cross-platform compatibility

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### MIT License Summary

- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

---

## 🙏 Acknowledgments

### APIs and Services
- **Google Gemini** - AI-powered environmental assistance
- **Semantic Scholar** - Academic paper search
- **CrossRef** - DOI and citation data
- **CORE** - Open access research papers

### Inspiration
- Romanian environmental NGOs and activists
- European Union Green Deal initiatives
- UN Sustainable Development Goals
- Paris Agreement climate targets

### Data Sources
- Romanian Environmental Protection Agency
- European Environment Agency
- World Health Organization air quality guidelines
- Romanian Government environmental programs

---

## 📞 Contact & Support

### Project Maintainer
- **GitHub**: [yourusername](https://github.com/yourusername)
- **Email**: your.email@example.com

### Getting Help

1. **Documentation**: Read this README thoroughly
2. **Issues**: Check [existing issues](https://github.com/yourusername/CombatereaPoluariiApp/issues)
3. **Discussions**: Join our [GitHub Discussions](https://github.com/yourusername/CombatereaPoluariiApp/discussions)
4. **Email**: Contact the maintainer for private inquiries

### Reporting Security Issues

If you discover a security vulnerability, please email privately to:
**security@example.com**

Do NOT open a public issue for security concerns.

---

## 🗺️ Roadmap

### Version 2.0 (Planned)

- [ ] **Database Integration**: PostgreSQL for user data persistence
- [ ] **User Accounts**: Save calculations, quiz progress, bookmarks
- [ ] **Mobile App**: React Native version for Android/iOS
- [ ] **Web Version**: Browser-based application
- [ ] **Real-time Data**: Live pollution sensors via IoT integration
- [ ] **Social Features**: Share achievements, create groups
- [ ] **Gamification**: Points, badges, leaderboards
- [ ] **Multi-language**: English, Hungarian, German translations

### Version 2.1 (Future)

- [ ] **Machine Learning**: Predict pollution trends
- [ ] **Push Notifications**: Air quality alerts
- [ ] **Augmented Reality**: AR pollution visualization
- [ ] **Blockchain**: Carbon credit tracking
- [ ] **API for Developers**: Open API for third-party apps

---

## 📊 Project Statistics

- **Lines of Code**: ~8,500
- **Number of Classes**: 25+
- **Features**: 12 major features
- **API Integrations**: 4 external services
- **Panels**: 11 interactive panels
- **Quiz Questions**: 25+ with 3 difficulty levels
- **Eco-Tips**: 25+ practical tips
- **Solutions**: 50+ categorized solutions
- **Cities Covered**: 10 Romanian cities
- **Pollutants Tracked**: 6 types (PM2.5, PM10, NO2, SO2, CO, O3)

---

## 🌍 Environmental Impact

By using this application, users can:

- **Learn** about environmental issues affecting Romania
- **Calculate** and reduce their personal carbon footprint
- **Discover** practical solutions for sustainable living
- **Access** cutting-edge environmental research
- **Track** pollution trends in their city
- **Educate** themselves through interactive quizzes
- **Implement** daily eco-friendly practices
- **Contribute** to Romania's climate goals

**Estimated Impact**: If 10,000 users each reduce their carbon footprint by just 10%, that's a collective reduction of **450 tons of CO2 per year** - equivalent to planting **20,000 trees**!

---

## 🎯 Goals and Vision

### Mission
To empower Romanian citizens with knowledge, tools, and practical solutions to combat pollution and contribute to a sustainable future.

### Vision
A Romania where every citizen is aware of their environmental impact and actively participates in pollution reduction through informed decisions and sustainable practices.

### Values
- **Education First**: Knowledge is power
- **Science-Based**: Relying on research and data
- **Action-Oriented**: Practical, implementable solutions
- **Accessible**: Free and open to all
- **Romanian Context**: Tailored to local needs and programs

---

<div align="center">

**Made with 💚 for the environment and 🇷🇴 Romania**

[![Star this repo](https://img.shields.io/github/stars/yourusername/CombatereaPoluariiApp?style=social)](https://github.com/yourusername/CombatereaPoluariiApp)
[![Follow on GitHub](https://img.shields.io/github/followers/yourusername?style=social)](https://github.com/yourusername)

*Together, we can make a difference! 🌱*

</div>

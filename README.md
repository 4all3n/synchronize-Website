# Synchronize Event Website

A modern, responsive website for the **Synchronize 2024** technical event featuring various competitions and activities.

## 🎯 About the Project

Synchronize is a dynamic tech event website built with cutting-edge web technologies. It showcases multiple event categories, schedules, gallery, and factions. The website features smooth scrolling, interactive modals, image sliders, and a fully responsive design optimized for mobile, tablet, and desktop views.

## ✨ Features

- **Responsive Design**: Mobile-first approach with Tailwind CSS for seamless experience across all devices
- **Interactive Navigation**: Dynamic menu with smooth transitions
- **Image Gallery**: Beautiful image slider for event highlights
- **Event Categories**: Multiple competitions including:
  - Agora (Debate/Discussion)
  - CodeVerse (Coding Competition)
  - Weblynx (Web Development)
  - Synergia (Team Events)
  - ByteQuest (Algorithm Challenges)
  - TechHunt (Tech Treasure Hunt)
  - Val (Valorant Gaming)
  - Video Competition
  - Photography Competition
  - IoT Workshop
  - Inspiration Session

- **Event Schedule**: Day-wise schedule across multiple days
- **Faction System**: Team-based competition structure
- **Smooth Animations**: CSS animations and transitions for enhanced UX
- **Dark Theme**: Modern dark mode design for reduced eye strain

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: 
  - Tailwind CSS (v4.0.0)
  - Custom CSS for animations and effects
- **Icons**: SVG-based icons for clean, scalable graphics
- **Build Tool**: Tailwind CSS utility-first framework

## 📁 Project Structure

```
synchronize-Website/
├── index.html           # Main landing page
├── day1.html           # Day 1 schedule
├── day2.html           # Day 2 schedule
├── factions.html       # Team/Faction information
├── gallery.html        # Event gallery
├── script.js           # JavaScript functionality
├── style.css           # Custom styles
├── slider.css          # Slider-specific styles
├── slider.js           # Slider functionality
├── tailwind.config.js  # Tailwind configuration
├── myConfig.js         # Custom configuration
├── package.json        # Dependencies
├── color.txt           # Color palette reference
└── res/               # Resources directory
    ├── logos/         # Logo assets
    ├── slide/         # Slider images
    └── *.png          # Event images
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- A modern web browser

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd synchronize-Website
```

2. Install dependencies:
```bash
npm install
```

3. Build Tailwind CSS (if needed):
```bash
npm run build
```

## 📱 How to Run

### Development Mode
Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js (http-server)
npx http-server
```

Then navigate to `http://localhost:8000` (or appropriate port)

### Navigation
- **Home**: Landing page with event introduction
- **Day 1**: First day schedule and events
- **Day 2**: Second day schedule and events
- **Factions**: Team/faction information
- **Gallery**: Event photo gallery and highlights

## 🎨 Design Features

- **Colors**: Custom color scheme optimized for tech events (based on color.txt)
- **Typography**: Clean, modern font stack
- **Animations**: Smooth transitions and scroll effects
- **Mobile Optimization**: Touch-friendly interface and responsive layouts

## 📝 Key Components

### Navigation
- Fixed header with Synchronize logo
- Mobile hamburger menu with slide-in animation
- Smooth scrolling between sections

### Event Modals
- Interactive popups for event details
- Information about competitions and activities
- Responsive modal design

### Image Gallery
- Auto-rotating image slider
- Event highlights and venue photos
- Schedule images

## 🔧 Configuration Files

- **tailwind.config.js**: Tailwind CSS customization
- **myConfig.js**: Application-specific configuration
- **color.txt**: Color palette definitions

## 📝 License

This project is part of the Synchronize 2024 event.

## 👥 Contributing

For contributions or issues, please contact the event organizers.

## 📧 Contact

For more information about the Synchronize event, visit the main website or contact the event team.

---

**Last Updated**: February 16, 2026
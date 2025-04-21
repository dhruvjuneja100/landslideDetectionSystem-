# LandslideShield

LandslideShield is an AI-powered landslide detection and early warning system designed to protect vulnerable communities through advanced monitoring and timely alerts.

## 🌟 Features

- **Real-time Monitoring**: Continuous assessment of ground conditions, rainfall patterns, and soil moisture using advanced sensors and satellite data.
- **Risk Mapping**: Detailed visualization of landslide-prone areas with risk level indicators based on geological and environmental factors.
- **Early Warnings**: Timely alerts and notifications to residents and authorities when landslide risk reaches critical levels.
- **AI Prediction**: Machine learning models analyze multiple parameters to predict landslide probability with high accuracy.
- **Historical Analysis**: Access to past landslide data and patterns to improve future prediction models and understand trends.
- **Community Integration**: Engagement with local communities for feedback, ground truth verification, and emergency response coordination.

## 🧠 AI Models

LandslideShield utilizes several advanced machine learning models:
- **U-Net**: Semantic segmentation for identifying landslide-prone terrains
- **DeepLabV3+**: Advanced image segmentation for high-resolution mapping
- **Random Forest**: Multi-parameter analysis for risk assessment
- **SVM (Support Vector Machine)**: Classification of terrain stability
- **XGBoost**: Prediction enhancements using gradient boosting

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS, Shadcn UI components
- **Backend**: Express.js, Node.js
- **Maps**: Leaflet for interactive mapping
- **Database**: PostgreSQL with Drizzle ORM
- **State Management**: React Query
- **Routing**: Wouter
- **Build Tools**: Vite, TypeScript

## 📱 Application Pages

- **Home**: Introduction to the project and its key features
- **About**: Information about the technology, team, and mission
- **Risk Map**: Interactive map displaying landslide-prone areas with risk levels
- **Dashboard**: Visualization of landslide data and statistics
- **Alerts**: Real-time warnings and notification management
- **Feedback**: Form for user input and community engagement
- **Help**: Resources and information for users

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LandslideShield.git
   cd LandslideShield
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the database:
   ```bash
   npm run db:push
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

6. Start the production server:
   ```bash
   npm run start
   ```

## 📊 API Endpoints

- `POST /api/feedback`: Submit user feedback
- `GET /api/feedback`: Retrieve all feedback entries

## 👥 Development Team

### NWC Department, SRM University
- Dhruv Juneja (RA2311030010184)
- Sahil Kumar (RA2311030010170)
- Vansh Chugh (RA2311030010199)

### CTECH Department, SRM University
- Grisha Sethi (RA2311003010142)

## 🙏 Acknowledgments

We gratefully acknowledge the support from SRM University, the National Disaster Management Authority, and local environmental agencies for their guidance and resources.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details. 
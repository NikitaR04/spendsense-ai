<!-- <div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/077c4f6f-fb69-44ee-adb7-f7da616e0946

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev` -->

# 💸 SpendSense AI
### Intelligent Personal Finance Management System

**Plan Smarter. Spend Better. Save Effortlessly.**

SpendSense AI is an AI-powered personal finance management application designed to simplify budgeting, improve savings discipline, and support informed financial decision-making.

The platform combines deterministic financial calculations with AI-powered recommendations to provide users with actionable insights into income allocation, expense management, savings goals, and purchase affordability.

---

## 📌 Project Overview

Traditional budgeting methods often lack structure, consistency, and personalized financial guidance. SpendSense AI addresses these challenges through an integrated financial management platform that enables users to organize their finances, monitor financial progress, and evaluate important purchasing decisions.

The application follows a privacy-first approach, allowing manual financial data entry without requiring mandatory bank account integration.

## ✨ Key Features

### 1. 📊 Interactive Financial Dashboard
- Comprehensive overview of monthly financial health.
- Monthly take-home income tracking.
- Visual representation of income distribution.
- Annual and multi-year savings projections.
- Emergency fund and financial goal progress tracking.
- AI-generated financial insights.

### 2. ⚖️ Smart Income Allocation
A deterministic allocation engine distributes monthly income across six financial categories.

| Financial Category | Default Allocation |
|---|---:|
| Essentials | 45% |
| Emergency Fund | 10% |
| Core Savings | 20% |
| Travel Fund | 10% |
| Financial Goals | 5% |
| Lifestyle | 10% |
| **Total** | **100%** |

**Capabilities:**
- Interactive percentage adjustment sliders.
- Automatic income rebalancing.
- Real-time allocation calculations.
- Visual financial distribution through doughnut charts.
- Live percentage and balance validation.

### 3. 🛡️ Emergency Fund Planner
- Customizable emergency fund targets.
- Emergency savings progress tracking.
- Essential expense coverage calculations.
- Estimated time-to-target calculations.
- Additional emergency contribution management.

### 4. 🎯 Financial Goals Planner
- Creation and management of financial goals.
- Custom savings targets and deadlines.
- Monthly contribution calculations.
- Goal completion progress tracking.
- Financial feasibility and shortfall analysis.

### 5. ✈️ Travel Fund Planner
- Dedicated travel savings management.
- Destination and estimated trip cost configuration.
- Target travel date selection.
- Accumulated savings tracking.
- Travel goal feasibility calculations.

### 6. 🤖 AI Financial Agent
Integrated with Google's Gemini API, the AI Financial Agent provides contextual financial decision support.

**Capabilities:**
- Natural-language financial queries.
- Context-aware purchase affordability evaluation.
- Estimated financial and cash-flow impact.
- Benefits and risk analysis.
- Alternative financial scenario comparisons.
- Structured recommendations and suggested action plans.

**Example Use Case:**

Evaluating the affordability of purchasing a smartphone worth ₹1,00,000 based on current income, savings, and financial commitments.

### 7. 🔮 What-If Financial Simulator
A financial simulation module designed to evaluate hypothetical changes before making real-world financial commitments.

**Simulation Parameters:**
- Salary increases or decreases.
- Rent adjustments.
- Changes in monthly savings.
- Additional loan or EMI commitments.
- Travel-related expenses.

The simulator compares current and projected financial positions to demonstrate the potential impact on monthly surplus and savings.

---

## 🏗️ System Architecture

The application follows a layered architecture integrating frontend components, deterministic financial calculations, and AI-powered decision support.

| Layer | Description |
|---|---|
| Presentation Layer | React-based interactive dashboard and UI components |
| Data Processing Layer | Input validation and application state management |
| Financial Logic Layer | Deterministic calculations and income allocation |
| AI Intelligence Layer | Gemini API integration for financial recommendations |
| Visualization Layer | Charts, progress indicators, and financial reports |

### Application Workflow

```text
User Input
    |
    v
Income, Expenses & Financial Goals
    |
    v
Data Processing & Validation
    |
    v
Deterministic Financial Engine
    |
    v
AI-Powered Decision Support
    |
    v
Interactive Financial Dashboard
    |
    v
Actionable Financial Insights
```

---

## 🛠️ Technology Stack

| Technology | Application |
|---|---|
| React | Frontend development |
| TypeScript | Type-safe application logic |
| Tailwind CSS | UI styling |
| Vite | Development server and build tooling |
| Node.js | Backend runtime |
| Express.js | Backend server |
| Google Gemini API | AI-powered financial analysis |
| SVG | Financial visualizations |

---

## 🚀 Installation & Setup

### Prerequisites

- Node.js (LTS recommended)
- npm
- Git
- Visual Studio Code (recommended)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/spendsense-ai.git
```

### 2. Navigate to the Project Directory

```bash
cd spendsense-ai
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory and configure the Gemini API key.

```env
GEMINI_API_KEY=your_gemini_api_key
```

Generate an API key through [Google AI Studio](https://aistudio.google.com/apikey).

**Security Note:** API credentials must remain in environment variables and must never be committed to the Git repository.

### 5. Start the Development Server

```bash
npm run dev
```

### 6. Access the Application

Open the following address in a web browser:

```text
http://localhost:3000
```

---

## 🔐 Privacy & Security

SpendSense AI adopts a privacy-first financial management approach.

- Manual financial data entry.
- No mandatory bank account linking.
- No bank credentials required.
- Environment-based API key configuration.
- Separation of financial calculations and AI-powered recommendations.

---

## 🔭 Future Enhancements

The following capabilities are proposed for future development:

- Machine learning-based expense prediction.
- Monthly PDF financial analytics and reports.
- Long-term wealth planning and SIP recommendations.
- Predictive spending anomaly detection.
- Optional consent-based bank account integration.
- Enhanced personalized financial recommendations.

---

## 👥 Project Team

**B.Tech Computer Science – Capstone Project**

| Team Member | Contribution |
|---|---|
| Nikita Rani | AI Integration & Smart Recommendations |
| Avika Singh | Application Logic & Financial Management |
| Ayushi Panda | Product Research & Project Planning |
| Anchal Kumari | UI/UX Design & Frontend Architecture |

---

## 🎯 Project Objective

SpendSense AI aims to bridge the gap between traditional budgeting and intelligent financial planning by combining structured income allocation, goal-based savings management,

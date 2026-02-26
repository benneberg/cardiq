# CardIQ
EMBED

![Demo](https://demo-forge.preview.emergentagent.com/renders/42f2a8e7-da34-4030-aa40-e5dc9df7b89f_db0f5230-1f11-492b-894d-5b9a51a16221.gif)
**An AI-Powered Microlearning Platform with Neo-Brutalist Design**

CardIQ is a smart learning platform that transforms any topic into bite-sized, gamified lessons using AI. Perfect for corporate training, onboarding, skill development, and self-directed learning.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

-----

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Use Cases](#use-cases)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

-----

## 🎯 Overview

CardIQ leverages advanced AI to create personalized learning experiences that adapt to your needs. Whether you’re learning GitHub Copilot, mastering a new framework, or onboarding employees to company processes, CardIQ breaks down complex topics into manageable, engaging lessons.

### Why CardIQ?

- **Microlearning**: Bite-sized lessons that fit into busy schedules
- **AI-Generated Content**: Custom curriculum created by expert AI
- **Gamification**: Track progress and stay motivated
- **Expert on Demand**: AI chat assistant for instant help
- **Mobile-First**: Learn anywhere, anytime
- **Zero Installation**: Pure HTML/CSS/JS - runs in any browser

-----

## ✨ Features

### Core Functionality

- **🎨 Neo-Brutalist Design**: Bold, high-contrast interface optimized for focus and readability
- **🤖 AI Curriculum Generation**: Automatically creates comprehensive lesson plans on any topic
- **📚 Smart Card System**: Lessons organized as interactive cards with difficulty levels
- **📊 Progress Tracking**: Visual progress bar showing completion status
- **🎲 Daily Random Tip**: Reinforcement learning with daily featured lessons
- **✅ Completion Tracking**: Mark cards as done and track your learning journey
- **📝 Personal Notes**: Add annotations to each lesson for future reference
- **💬 AI Expert Chat**: Context-aware assistant that knows your topic inside-out
- **🔍 Search & Filter**: Find specific lessons quickly (All/Pending/Completed)
- **🎯 Multi-Topic Management**: Switch between different learning paths
- **💾 Export/Import**: Share curricula with team members
- **📱 Mobile-First**: Responsive design optimized for all devices
- **🔒 Local Storage**: All data stored securely in your browser

### Learning Experience

Each lesson card includes:

- **Clear Title**: Descriptive and concise
- **Detailed Content**: 2-3 paragraph explanations
- **Key Points**: 3-5 essential takeaways
- **Difficulty Level**: Beginner, Intermediate, or Advanced
- **Time Estimate**: Expected completion time
- **Interactive Actions**: Mark done, add notes, ask AI

-----

## 🛠 Technology Stack

### Frontend

- **HTML5**: Semantic markup structure
- **CSS3**: Custom neo-brutalist styling with CSS variables
- **JavaScript (ES6+)**: Vanilla JS for maximum performance
- **Bootstrap 5.3.0**: Responsive grid system and utilities
- **Font Awesome 6.4.0**: Icon library

### AI & APIs

- **Groq API**: Fast inference for LLM interactions
  - Supported models: Llama, Mixtral, Gemma, and more
  - Streaming responses for real-time chat
  - Configurable temperature and token limits
- **OpenAI-Compatible API**: Standard chat completion format

### Data Storage

- **LocalStorage API**: Client-side data persistence
- **JSON**: Data serialization for export/import

### Design Philosophy

- **Mobile-First**: Progressive enhancement from small screens up
- **Neo-Brutalism**: High contrast, bold borders, functional aesthetics
- **Accessibility**: Semantic HTML and keyboard navigation support
- **Performance**: Zero dependencies beyond CDN resources

-----

## 🚀 Getting Started

### Prerequisites

1. **Web Browser**: Modern browser with JavaScript enabled (Chrome, Firefox, Safari, Edge)
1. **Groq API Key**: Free account at [console.groq.com](https://console.groq.com)

### Installation

CardIQ requires **zero installation**! Simply:

1. **Download** the HTML file
1. **Open** it in your web browser
1. **Configure** your Groq API key
1. **Start learning**!

### Quick Start

```bash
# Clone or download the repository
git clone https://github.com/yourusername/cardiq.git

# Open the file
open cardiq.html

# Or serve locally
python -m http.server 8000
# Then visit http://localhost:8000
```

-----

## 📖 How to Use

### 1. Initial Setup

**Configure API Access:**

1. Click the **Settings** icon (⚙️) in the top-right corner
1. Enter your **Groq API Key**
1. Click **“SAVE & FETCH MODELS”**
1. Select your preferred **LLM model** (recommend: `llama-3.3-70b-versatile`)
1. Adjust **temperature** (creativity) and **max tokens** (response length) if desired

**Optional Configuration:**

- Add a **custom system prompt** to modify AI behavior
- Adjust generation parameters for your learning style

### 2. Create Your First Topic

**Launch Topic Wizard:**

1. Click **“NEW”** button next to the topic selector
1. Fill in the topic creation form:
- **Topic Name**: e.g., “GitHub Copilot AI in VS Code”
- **Target Audience**: e.g., “Software Developers, Intermediate Level”
- **Learning Objectives**: What should students master?
- **Number of Lessons**: 5-50 cards (default: 12)
- **Additional Context**: Specific requirements or focus areas
1. Click **“GENERATE TOPIC & LESSONS”**
1. Wait for AI to create your curriculum (~30 seconds)

**Example Topic:**

```
Name: GitHub Copilot AI in VS Code - Complete Guide
Audience: Professional Software Developers
Objectives: 
- Master Copilot agent vs chat modes
- Create custom configuration files
- Write effective prompts for code generation
- Enable internet search tools
- Optimize autocomplete settings
- Work with multi-repository projects
- Build custom agents
Lesson Count: 15
```

### 3. Learn with Cards

**Navigate Your Lessons:**

- **Daily Tip**: Featured random lesson at the top (changes daily)
- **Progress Bar**: Shows X/Y completed with percentage
- **Search**: Find specific lessons by keyword
- **Filter Tabs**: View All, Pending, or Completed cards

**Interact with Cards:**

- **Mark Done**: Check off completed lessons (turns green)
- **Add Notes**: Personal annotations for future reference
- **Ask AI**: Quick button to discuss card topic in chat

### 4. Use the AI Expert Chat

**Get Instant Help:**

1. Click the **Chat** icon (💬) in the top-right
1. Ask questions about your current topic
1. AI expert responds with context-aware answers
1. Conversation history maintained per topic

**Example Questions:**

- “Can you explain more about agent thinking mode?”
- “Show me an example of a custom .copilot-instructions.md file”
- “What’s the difference between workspace and user settings?”

### 5. Track Your Progress

**Monitor Learning:**

- **Progress Bar**: Visual representation of completion
- **Card Counter**: “5/12 Completed (42%)”
- **Filter by Status**: See only pending or completed lessons
- **Personal Notes**: Review your annotations

### 6. Manage Multiple Topics

**Switch Between Learning Paths:**

1. Use the **topic dropdown** at the top
1. Each topic maintains separate:
- Lesson cards
- Progress tracking
- Chat history
- Personal notes

**Share Topics:**

1. Go to **Settings** → **Data Management**
1. Click **“EXPORT ALL DATA”** to save JSON file
1. Share with colleagues
1. They can **“IMPORT DATA”** to receive your curriculum

-----

## 💡 Use Cases

### Corporate Training

- **New Tool Adoption**: GitHub Copilot, Cursor AI, Linear, Notion
- **Framework Onboarding**: React, Vue, Svelte, Next.js
- **Platform Migration**: AWS to Azure, Jenkins to GitHub Actions
- **Best Practices**: Security protocols, code review standards

### Employee Onboarding

- **Company Processes**: HR workflows, approval chains
- **Tech Stack**: Internal tools and frameworks
- **Team Culture**: Communication norms, meeting structures
- **Product Knowledge**: Feature deep-dives, architecture

### Certification Preparation

- **AWS/Azure/GCP**: Cloud certification study guides
- **Programming Languages**: Python, JavaScript, Rust
- **Security**: CISSP, CEH, Security+
- **Project Management**: PMP, Scrum Master

### Self-Directed Learning

- **Career Development**: New skills, technologies
- **Hobby Projects**: Game development, 3D modeling
- **Language Learning**: Programming languages, human languages
- **Personal Growth**: Productivity, communication

### Example Topics You Can Create

- “TypeScript Advanced Patterns for React Developers”
- “Docker & Kubernetes: From Beginner to Production”
- “Writing Effective Documentation for Open Source”
- “SQL Optimization: Performance Tuning Guide”
- “Figma to Code: Designer-Developer Workflow”
- “API Design Best Practices with REST & GraphQL”
- “Mental Models for System Architecture”

-----

## 🚧 Future Improvements

### High Priority

#### Enhanced Learning Features

- [ ] **Spaced Repetition Algorithm**: Re-surface cards based on forgetting curve
- [ ] **Quiz Mode**: Test knowledge with AI-generated questions
- [ ] **Learning Streaks**: Gamification with daily learning goals
- [ ] **Card Ratings**: Let users rate usefulness/difficulty
- [ ] **Bookmarks**: Star favorite cards for quick access
- [ ] **Learning Path Recommendations**: AI suggests next topics

#### Content Generation

- [ ] **Image Generation**: Visual diagrams for complex concepts
- [ ] **Code Examples**: Syntax-highlighted, runnable code snippets
- [ ] **Video Integration**: Embed relevant YouTube/tutorial videos
- [ ] **Interactive Exercises**: Practice problems with validation
- [ ] **Web Search Integration**: Auto-fetch latest documentation
- [ ] **Multi-Language Support**: Generate lessons in user’s language

#### Collaboration Features

- [ ] **Team Workspaces**: Shared topics across organization
- [ ] **Progress Sharing**: Compare learning with colleagues
- [ ] **Comments on Cards**: Team discussions
- [ ] **Topic Templates**: Pre-built curricula library
- [ ] **Instructor Mode**: Track student progress
- [ ] **Assignment System**: Assign specific lessons to team members

### Medium Priority

#### UI/UX Enhancements

- [ ] **Dark/Light Theme Toggle**: User preference
- [ ] **Custom Color Schemes**: Personalize neo-brutalist palette
- [ ] **Accessibility Mode**: Enhanced contrast, screen reader support
- [ ] **Keyboard Shortcuts**: Power user navigation
- [ ] **Card Layouts**: Grid, list, compact views
- [ ] **Drag-and-Drop Reordering**: Custom lesson sequence

#### Technical Improvements

- [ ] **Offline Mode**: PWA with service worker
- [ ] **Cloud Sync**: Optional account for multi-device
- [ ] **PDF Export**: Print-friendly lesson summaries
- [ ] **CSV/Markdown Export**: Alternative export formats
- [ ] **API Integration**: Connect to LMS platforms
- [ ] **Performance Optimization**: Virtual scrolling for large topics

#### Analytics & Insights

- [ ] **Learning Analytics Dashboard**: Time spent, completion rates
- [ ] **Knowledge Gaps Analysis**: AI identifies weak areas
- [ ] **Study Recommendations**: Optimal learning schedule
- [ ] **Progress Reports**: Weekly/monthly summaries
- [ ] **Heatmap Visualization**: Activity patterns
- [ ] **Comparison Metrics**: Benchmark against peers

### Low Priority

#### Advanced Features

- [ ] **Voice Input**: Speech-to-text for chat
- [ ] **Mobile Apps**: Native iOS/Android versions
- [ ] **Browser Extension**: Learn from any webpage
- [ ] **Slack/Discord Integration**: Learning bot
- [ ] **Notion Integration**: Sync with Notion workspace
- [ ] **Calendar Integration**: Schedule learning sessions
- [ ] **Pomodoro Timer**: Built-in focus sessions
- [ ] **Achievement Badges**: Gamification rewards
- [ ] **Leaderboards**: Competitive learning (opt-in)

#### AI Enhancements

- [ ] **Multi-Model Support**: OpenAI, Anthropic, local models
- [ ] **RAG Integration**: Search documentation in real-time
- [ ] **Adaptive Difficulty**: AI adjusts based on performance
- [ ] **Personalized Learning Paths**: Custom sequencing per user
- [ ] **Concept Mapping**: Visual knowledge graphs
- [ ] **Prerequisite Detection**: Auto-recommend foundational topics

#### Developer Experience

- [ ] **Plugin System**: Extensible architecture
- [ ] **Custom Themes**: CSS variable overrides
- [ ] **Webhook Support**: Integrate with external systems
- [ ] **GraphQL API**: Programmatic access
- [ ] **Component Library**: Reusable UI components
- [ ] **Testing Suite**: Automated tests for reliability

-----

## 🤝 Contributing

Contributions are welcome! Here’s how you can help:

### Bug Reports

1. Check existing issues first
1. Provide clear reproduction steps
1. Include browser/OS information
1. Add screenshots if applicable

### Feature Requests

1. Describe the problem you’re solving
1. Explain your proposed solution
1. Consider implementation complexity
1. Discuss alternatives

### Code Contributions

1. Fork the repository
1. Create a feature branch (`git checkout -b feature/amazing-feature`)
1. Commit your changes (`git commit -m 'Add amazing feature'`)
1. Push to branch (`git push origin feature/amazing-feature`)
1. Open a Pull Request

### Guidelines

- Maintain neo-brutalist design aesthetic
- Keep mobile-first approach
- Ensure browser compatibility
- Add comments for complex logic
- Test across devices
- Update README if needed

-----

## 📄 License

MIT License

Copyright (c) 2025 Lukas Benneberg

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

-----

## 👨‍💻 Author

**Lukas Benneberg**

- Created CardIQ to democratize AI-powered learning
- Passionate about educational technology and developer tools
- Believer in microlearning and gamification for effective knowledge retention

-----

## 🙏 Acknowledgments

- **Groq**: Fast inference API powering the AI features
- **Bootstrap**: Responsive framework foundation
- **Font Awesome**: Beautiful iconography
- **Neo-Brutalism Movement**: Design inspiration

-----

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/cardiq/issues)
- **Documentation**: This README
- **API Docs**: [Groq Documentation](https://console.groq.com/docs)

-----

## 🌟 Star the Project

If you find CardIQ useful, please consider giving it a star on GitHub! It helps others discover the project and motivates continued development.

-----

**Made with ❤️ and brutal design by Lukas Benneberg**

*Last Updated: September 2025*

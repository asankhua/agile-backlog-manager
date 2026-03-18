# Agile Backlog Manager Pro 🚀

A modern, feature-rich agile project management tool built with vanilla JavaScript and Tailwind CSS. Perfect for teams who want a simple yet powerful solution for sprint planning, task tracking, and team collaboration.

![Agile Backlog Manager Pro](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Built With](https://img.shields.io/badge/Built%20With-Vanilla%20JS%20%7C%20Tailwind%20CSS-orange.svg)

## ✨ Features

### 🎯 Core Agile Management
- **Hierarchical Task Structure**: Epics → Features → Stories → Bugs
- **Smart Points Rollup**: Automatic point calculation from child tasks
- **Sprint Lifecycle Management**: Complete sprint workflow from planning to completion
- **Team Capacity Tracking**: Visual workload management and capacity planning

### 📊 Views & Dashboards
- **Kanban Board**: Drag-and-drop task management across workflow stages
- **Backlog View**: Comprehensive task prioritization and sprint planning
- **Roadmap View**: Strategic epic visualization and long-term planning
- **Burndown Analytics**: Real-time sprint progress visualization

### 👥 Team Management
- **Member Profiles**: Customizable team avatars and capacity settings
- **Workload Dashboard**: Visual capacity utilization indicators
- **Task Assignment**: Intelligent workload distribution
- **Performance Tracking**: Team velocity and productivity metrics

### 📈 Reporting & Analytics
- **Sprint Reports**: Automated report generation with email integration
- **Retrospective Tools**: Built-in retrospective capture and history
- **Velocity Tracking**: Historical performance analysis
- **Export Capabilities**: Copy and email functionality

### 🎨 User Experience
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Real-time Updates**: Instant UI feedback and state synchronization
- **Dark Mode Support**: Easy on the eyes during long work sessions

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- No installation required - runs entirely in the browser!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/agile-backlog-manager-pro.git
   cd agile-backlog-manager-pro
   ```

2. **Run locally**
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Or simply open index.html in your browser
   open index.html
   ```

3. **Access the application**
   - Navigate to `http://localhost:8000`
   - Or open `index.html` directly in your browser

### Production Deployment

#### GitHub Pages (Recommended)
1. Push to your GitHub repository
2. Enable GitHub Pages in repository settings
3. Select the main branch as source
4. Access at `https://yourusername.github.io/agile-backlog-manager-pro`

#### Firebase Hosting
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Initialize Firebase: `firebase init hosting`
3. Deploy: `firebase deploy`

## 📖 Usage Guide

### Getting Started

1. **Setup Your Team**
   - Open Settings → Add team members with capacity
   - Customize member avatars and workload limits

2. **Create Your First Epic**
   - Click "New Item" → Select "Epic" type
   - Add high-level project goals

3. **Build Your Task Hierarchy**
   - Create Features under Epics
   - Add Stories under Features
   - Track Bugs linked to Stories

4. **Plan Your Sprint**
   - Go to Backlog view
   - Click "Plan S{number}" on tasks
   - Monitor capacity utilization

### Daily Workflow

#### Sprint Planning
```mermaid
graph LR
    BACKLOG[Backlog] --> PLAN[Plan Sprint]
    PLAN --> KANBAN[Kanban Board]
    KANBAN --> WORK[Daily Work]
```

#### Task Management
- **To Do**: Tasks ready for development
- **Development**: Active work in progress
- **Testing**: Quality assurance phase
- **Done**: Completed and verified

#### Sprint Completion
- Move all completed tasks to "Done"
- Click "Complete Sprint" button
- Add retrospective notes
- Review sprint analytics

### Advanced Features

#### Points Calculation
The system automatically calculates points for parent tasks:
- **Stories/Bugs**: Use assigned points (1, 2, 3, 5, 8, 13)
- **Features**: Sum of all child story points
- **Epics**: Sum of all child feature points

#### Capacity Management
- Each team member has a capacity limit
- Visual indicators show overload (red) or availability (green)
- Automatic workload balancing recommendations

#### Sprint History
- All completed sprints are archived automatically
- Retrospective notes preserved for future reference
- Historical velocity tracking for better planning

## 🏗️ Architecture

### Technology Stack
- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Icons**: Feather Icons
- **Storage**: LocalStorage (demo) / Firebase (production)
- **Deployment**: GitHub Pages, Firebase Hosting

### Data Models
```javascript
// Task Structure
{
  id: "EPIC-101",
  type: "epic",
  title: "Platform Launch",
  status: "backlog",
  points: 0,  // Auto-calculated
  parentId: null,
  assignee: "u1",
  sprint: null
}

// Team Member
{
  id: "u1",
  name: "Alice",
  capacity: 20,
  color: "bg-indigo-500"
}
```

### Key Features Implementation
- **Drag & Drop**: HTML5 Drag and Drop API
- **State Management**: Custom event-driven architecture
- **Data Persistence**: LocalStorage with Firebase sync
- **Responsive Design**: Tailwind CSS utility classes

## 🔧 Configuration

### Firebase Integration (Optional)
For cloud sync and multi-user support:

1. Create Firebase project at https://console.firebase.google.com
2. Enable Firestore Database
3. Update configuration in `index.html`:
   ```javascript
   const firebaseConfig = {
     apiKey: "your-api-key",
     authDomain: "your-project.firebaseapp.com",
     projectId: "your-project-id",
     // ... other config
   };
   ```

### Customization Options

#### Branding
- Update colors in Tailwind configuration
- Modify logo and title in HTML header
- Customize team member avatar colors

#### Workflow Stages
- Modify `COLUMNS` array in JavaScript
- Update CSS classes for new stages
- Adjust drag-and-drop handlers

#### Points System
- Modify Fibonacci sequence in task form
- Update calculation logic for custom schemes
- Adjust capacity planning algorithms

## 🧪 Testing

### Automated Tests
Run the test suite:
```bash
open test.html  # In browser
```

### Manual Testing Checklist
- [ ] Task creation and hierarchy
- [ ] Drag-and-drop functionality
- [ ] Sprint completion workflow
- [ ] Team capacity management
- [ ] Data persistence
- [ ] Cross-browser compatibility

### Performance Testing
- Test with 100+ tasks
- Verify smooth animations
- Check memory usage
- Validate response times

## 🤝 Contributing

We welcome contributions! Please follow these guidelines:

### Development Workflow
1. Fork the repository
2. Create feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open Pull Request

### Code Standards
- Use semantic HTML5 elements
- Follow JavaScript ES6+ standards
- Maintain Tailwind CSS utility-first approach
- Add comments for complex logic
- Ensure cross-browser compatibility

### Bug Reports
- Use GitHub Issues for bug reports
- Include browser version and steps to reproduce
- Add screenshots if applicable
- Provide error console logs

## 📝 Roadmap

### Upcoming Features
- [ ] Real-time collaboration
- [ ] Advanced reporting dashboard
- [ ] Integration with external tools (Jira, GitHub)
- [ ] Mobile application (React Native)
- [ ] Advanced workflow customization
- [ ] Time tracking integration
- [ ] Advanced analytics and insights

### Technical Improvements
- [ ] Progressive Web App (PWA) features
- [ ] Offline functionality
- [ ] Enhanced security features
- [ ] Performance optimizations
- [ ] Accessibility improvements
- [ ] Internationalization support

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Tailwind CSS** - For the amazing utility-first CSS framework
- **Feather Icons** - For the beautiful icon set
- **Firebase** - For the backend services (when used)
- **GitHub** - For hosting and version control

## 📞 Support

- **Documentation**: Check the [ARCHITECTURE.md](ARCHITECTURE.md) for technical details
- **Issues**: Report bugs via GitHub Issues
- **Discussions**: Use GitHub Discussions for questions and ideas
- **Email**: Contact at [your-email@example.com]

---

**Built with ❤️ for agile teams who value simplicity and productivity**

---

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/agile-backlog-manager-pro&type=Date)](https://star-history.com/#yourusername/agile-backlog-manager-pro&Date)

---

*If you find this tool helpful, please consider giving it a ⭐ on GitHub!*

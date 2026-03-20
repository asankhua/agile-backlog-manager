# Agile Backlog Manager Pro 🚀

> **Professional Agile Project Management Tool** - Sprint planning, task tracking, and team collaboration made simple.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Built With](https://img.shields.io/badge/built%20with-Vanilla%20JS%20%7C%20Tailwind%20CSS-orange.svg)
![Chrome](https://img.shields.io/badge/chrome-90+-blue.svg)
![Firefox](https://img.shields.io/badge/firefox-88+-orange.svg)
![Safari](https://img.shields.io/badge/safari-14+-red.svg)

![Agile Backlog Manager Pro Banner](https://via.placeholder.com/1200x400/6366f1/ffffff?text=Agile+Backlog+Manager+Pro)

---

## 📖 Table of Contents

- [Overview](#overview)
- [Key Features](#-key-features)
- [Live Demo](#-live-demo)
- [Quick Start](#-quick-start)
- [Usage Guide](#-usage-guide)
- [Technology Stack](#-technology-stack)
- [Architecture](#-architecture)
- [Deployment](#-deployment)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🎯 Overview

Agile Backlog Manager Pro is a **professional-grade, browser-based agile project management tool** designed for teams who need powerful sprint planning capabilities without the complexity of enterprise tools. Built entirely with vanilla JavaScript and modern web technologies, it runs completely in your browser—no installation or server required!

### What Makes It Special?

✅ **Zero Installation** - Just open the HTML file and start working  
✅ **Smart Points Rollup** - Automatic calculation from child tasks to parents  
✅ **Complete Sprint Lifecycle** - Plan, execute, complete, and learn from retrospectives  
✅ **Team Capacity Tracking** - Visual workload management prevents burnout  
✅ **Multiple Views** - Backlog, Kanban board, Roadmap, and Burndown charts  
✅ **100% Free & Open Source** - MIT license, deploy anywhere

### Perfect For:

- 🚀 **Startups** needing lightweight agile tools
- 👨‍💻 **Development teams** managing sprints
- 📚 **Students** learning agile methodologies
- 🎓 **Educators** teaching scrum practices
- 🌍 **Remote teams** needing simple collaboration tools

## ✨ Key Features

### 🎯 Core Agile Management
- **Hierarchical Task Structure**: Epics → Features → Stories → Bugs with automatic parent-child relationships
- **Smart Points Rollup**: Real-time calculation from child tasks to epic level using Fibonacci sequence (0, 1, 2, 3, 5, 8, 13)
- **Sprint Lifecycle Management**: Complete workflow from planning → active → review → completion with retrospectives
- **Team Capacity Tracking**: Visual workload indicators showing under/over allocation in real-time

### 📊 Views & Dashboards
- **Kanban Board**: Drag-and-drop task management across customizable workflow stages (To Do → Dev → Testing → Done)
- **Backlog View**: Comprehensive task prioritization with RICE scoring and sprint planning tools
- **Roadmap View**: Strategic epic visualization for long-term planning and stakeholder reviews
- **Burndown Analytics**: Real-time sprint progress visualization with ideal velocity tracking

### 👥 Team Management
- **Member Profiles**: Customizable team avatars with color coding and capacity settings
- **Workload Dashboard**: Visual capacity utilization indicators (green < 80%, yellow 80-100%, red > 100%)
- **Task Assignment**: Intelligent workload distribution with drag-and-drop simplicity
- **Performance Tracking**: Team velocity and productivity metrics across sprints

### 📈 Reporting & Analytics
- **Sprint Reports**: Automated report generation with email integration and stakeholder updates
- **Retrospective Tools**: Built-in retrospective capture (what went well / what to improve)
- **Velocity Tracking**: Historical performance analysis for better sprint planning
- **Export Capabilities**: Copy reports to clipboard or dispatch via email

### 🎨 User Experience
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile browsers
- **Modern UI**: Clean, intuitive interface with smooth animations and glass-morphism effects
- **Real-time Updates**: Instant UI feedback with debounced state synchronization
- **Dark Mode Support**: Easy on the eyes during long work sessions (coming soon)
- **Keyboard Shortcuts**: Power user features (Ctrl+K search, Ctrl+N new task, 1-2-3 view switching)

## 🌐 Live Demo

### Try It Now!
No installation required - choose your preferred method:

**Option 1: Direct Browser Access**
```bash
# Simply open the HTML file directly
open index.html
```

**Option 2: Local Development Server**
```bash
# Using Python (pre-installed on Mac/Linux)
python3 -m http.server 8000
# Navigate to: http://localhost:8000

# Using Node.js
npx serve .
# Navigate to: http://localhost:3000
```

**Option 3: Production Deployment**
- **GitHub Pages**: https://asankhua.github.io/agile-backlog-manager (Coming soon)
- **Firebase Hosting**: Deploy in minutes with free tier

## 🚀 Quick Start

### Prerequisites
✅ **Modern Web Browser** - Chrome 90+, Firefox 88+, Safari 14+, Edge 90+  
✅ **No Installation Required** - Runs entirely in the browser!  
✅ **JavaScript Enabled** - All modern browsers have this by default  
✅ **LocalStorage Support** - For data persistence (enabled by default)

### Installation & Setup

#### Method 1: Clone and Run Locally

1. **Clone the Repository**
```bash
git clone https://github.com/asankhua/agile-backlog-manager.git
cd agile-backlog-manager
```

2. **Start a Local Server** (Choose one)

**Using Python:**
```bash
# Python 3.x (pre-installed on Mac/Linux)
python3 -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
# Using serve package
npx serve .

# Or using http-server
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

3. **Access the Application**
- Navigate to `http://localhost:8000` in your browser
- Or open `index.html` directly (some features may be limited)

#### Method 2: Direct File Access (Simplest)

```bash
# Mac/Linux
open index.html

# Windows
start index.html

# Or drag and drop index.html into your browser
```

### Production Deployment

#### GitHub Pages (Recommended - Free)

1. Push to your GitHub repository:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: Select `main` branch
   - Click Save
   
3. Access at: `https://yourusername.github.io/agile-backlog-manager`

#### Firebase Hosting (Free Tier)

1. Install Firebase CLI:
```bash
npm install -g firebase-tools
```

2. Initialize and Deploy:
```bash
firebase login
firebase init hosting
# Select: Use existing project or create new
# Public directory: . (current directory)
# Single-page app: Yes
firebase deploy --only hosting
```

Access at: `https://your-project.web.app`

#### Netlify (Free Tier)

1. Drag and Drop:
   - Visit https://app.netlify.com/drop
   - Drag the entire project folder
   
2. Or Connect Git:
   - Import from GitHub
   - Automatic deployments on push

Access at: `https://your-site.netlify.app`

## 📖 Usage Guide

### Getting Started - Your First Sprint

#### Step 1: Setup Your Team (2 minutes)

1. Click the **⚙️ Settings** button in the top-right corner
2. Add team members:
   - Enter name (e.g., "Alice Johnson")
   - Set capacity (story points per sprint, e.g., 20)
   - Choose avatar color
3. Repeat for all team members (recommended: 3-7 people)
4. Click **Save Configuration**

**Pro Tip:** Start with default team (Alice, Bob, Charlie) to learn the system!

#### Step 2: Create Your First Epic (1 minute)

1. Click **➕ New Item** button
2. Select **Type: Epic**
3. Enter title: "Platform Modernization"
4. Add description: High-level initiative description
5. Click **Confirm**

#### Step 3: Build Task Hierarchy (3 minutes)

**Add Features under Epic:**
1. Click on your epic to edit
2. Or create new item → Type: Feature
3. Select parent epic from dropdown
4. Add features like "Authentication System", "Dashboard UI"

**Add Stories under Features:**
1. Create new item → Type: Story
2. Select parent feature
3. Estimate story points (Fibonacci: 1, 2, 3, 5, 8, 13)
4. Assign to team member
5. Set priority (Low, Medium, High, Critical)

**Pro Tip:** Use templates! Click **🐛 Bug Template** or **✨ Feature Template** for pre-filled structures.

#### Step 4: Plan Your Sprint (2 minutes)

1. Navigate to **Backlog** view (click view picker or press `1`)
2. Review tasks in backlog
3. Click **Plan Sprint** button on tasks you want to include
4. Monitor team capacity indicator at top:
   - 🟢 Green: Under capacity (< 80%)
   - 🟡 Yellow: Optimal (80-100%)
   - 🔴 Red: Overallocated (> 100%)
5. Adjust assignments until capacity is balanced

#### Step 5: Start Working! (Daily)

1. Switch to **Kanban Board** view (press `2`)
2. Drag tasks across columns:
   - **To Do** → Ready for work
   - **Dev In Progress** → Currently working
   - **Testing** → QA/review phase
   - **Done** → Complete and verified
3. Update task details by clicking on cards
4. Track progress in real-time

### Daily Workflow Examples

#### Morning Standup
1. Open Kanban board
2. Review each column
3. Identify blockers (tasks stuck in Testing)
4. Reassign tasks if needed
5. Update sprint day counter in Settings

#### During the Day
- Update task status as you work
- Add comments/descriptions to tasks
- Log blocked dependencies
- Track time spent (manual)

#### End of Day
1. Check capacity dashboard
2. Review burndown chart (Analytics button)
3. Note accomplishments
4. Plan tomorrow's priorities

### Advanced Features

#### Smart Points Rollup
The system automatically calculates points for parent tasks:

```
Epic: Platform Launch (21 points)
├─ Feature: Auth System (13 points)
│  ├─ Story: OAuth Integration (8 points)
│  └─ Bug: Login Error Fix (5 points)
└─ Feature: Dashboard (8 points)
   └─ Story: Chart Components (8 points)
```

**How it works:**
- Stories/Bugs use their assigned points
- Features sum up all child story/bug points
- Epics sum up all child feature points

#### Capacity Management
Each team member has a capacity limit (default: 20, 15, 15 points).

**Visual Indicators:**
- 🟢 **Green** (< 80%): Available for more work
- 🟡 **Yellow** (80-100%): Optimal workload
- 🔴 **Red** (> 100%): Overallocated, needs rebalancing

**Example:**
```
Alice: ████████████████░░ 18/20 pts (90%) - Optimal
Bob:   ████████████████████ 16/15 pts (107%) - Overloaded!
Charlie: ██████████░░░░░░░░ 10/15 pts (67%) - Available
```

#### Sprint Completion Workflow

1. **Prepare for Completion:**
   - Move all completed tasks to "Done" column
   - Verify all done criteria met
   
2. **Click "Complete Sprint" Button:**
   - Opens completion modal
   - Shows sprint summary
   
3. **Add Retrospective Notes:**
   - **What Went Well:** Celebrate wins!
   - **What to Improve:** Learning opportunities
   
4. **Confirm Completion:**
   - Sprint archived to history
   - Velocity calculated
   - Next sprint auto-created

#### Sprint History & Analytics

Access completed sprints in Backlog view (scroll down):

**Each sprint shows:**
- Sprint number and completion date
- Total velocity (points completed)
- List of completed tasks
- Retrospective notes

Use this data for:
- Velocity trending
- Future sprint planning
- Team performance reviews

### Keyboard Shortcuts Power User Guide

| Shortcut | Action | Description |
|----------|--------|-------------|
| `Ctrl/Cmd + K` | 🔍 Search | Open advanced search modal |
| `Ctrl/Cmd + N` | ➕ New Task | Quick task creation |
| `Ctrl/Cmd + /` | 🎯 Filters | Focus filter dropdowns |
| `Escape` | ❌ Close | Close any open modal |
| `1` | 📋 Backlog | Switch to backlog view |
| `2` | 📊 Kanban | Switch to board view |
| `3` | 🗺️ Roadmap | Switch to roadmap view |

### Best Practices

#### ✅ Do's
- Break down epics into small, manageable stories
- Estimate using Fibonacci sequence (1, 2, 3, 5, 8, 13)
- Update task status daily
- Keep descriptions clear and actionable
- Use priorities effectively (Critical > High > Medium > Low)
- Review burndown charts mid-sprint
- Conduct retrospectives religiously

#### ❌ Don'ts
- Don't create tasks larger than 13 points (split them)
- Don't skip sprint planning
- Don't ignore capacity warnings
- Don't forget to move tasks across columns
- Don't mix sprint goals mid-sprint

### Advanced Features

#### Points Calculation System
The system automatically calculates points for parent tasks using the Fibonacci sequence:

**Story/Bug Level:**
- Uses assigned points directly (1, 2, 3, 5, 8, 13)

**Feature Level:**
- Sums all child story and bug points
- Example: Feature with 3 stories (5pts, 3pts, 2pts) = 10 points

**Epic Level:**
- Sums all child feature points
- Example: Epic with 2 features (10pts, 8pts) = 18 points

#### Capacity Management & Workload Balancing
Each team member has a configurable capacity limit in story points.

**Visual Indicators:**
- 🟢 **Green (< 80%)**: Under capacity - available for more work
- 🟡 **Yellow (80-100%)**: Optimal workload - well balanced
- 🔴 **Red (> 100%)**: Overallocated - needs immediate rebalancing

**Workload Dashboard Example:**
```
Alice:   ████████████████░░ 18/20 pts (90%)  ✅ Optimal
Bob:     ████████████████████ 16/15 pts (107%) ⚠️ Overloaded!
Charlie: ██████████░░░░░░░░ 10/15 pts (67%)  💡 Available
```

#### Sprint History & Retrospectives
All completed sprints are automatically archived with:
- Sprint number and completion date
- Total velocity (points completed)
- List of completed tasks with details
- Retrospective notes (what went well / what to improve)

Use historical data for:
- Velocity trending across sprints
- Future sprint planning accuracy
- Team performance reviews
- Continuous improvement tracking

## 🏗️ Architecture

For detailed technical architecture, see [ARCHITECTURE.md](ARCHITECTURE.md)

### Technology Stack

#### Frontend (100% Browser-Based)
- **HTML5** - Semantic markup and structure
- **Tailwind CSS v3.x** (via CDN) - Utility-first styling framework
- **Feather Icons** (v1.0.22) - Lightweight icon library
- **Vanilla JavaScript ES6+** - Zero-dependency application logic
- **Google Fonts** - Inter font family for modern typography

#### Data Persistence Layer
- **LocalStorage API** (Default) - Client-side storage (~5-10MB capacity)
  - Keys: `agile_v50_tasks`, `agile_v50_team`, `agile_v50_sprint`, `agile_v50_history`
  - No server required, works offline
  - Data persists across browser sessions
  
- **Firebase Firestore** (Optional - Production Ready)
  - Real-time cloud database
  - Multi-user synchronization
  - Requires manual configuration in `index.html`

#### External Dependencies (CDN)
```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Feather Icons -->
<script src="https://unpkg.com/feather-icons"></script>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
```

### System Architecture Overview

```
┌─────────────────────────────────────────────────┐
│           Presentation Layer                    │
│  ┌──────────┬──────────┬──────────────────┐    │
│  │ Backlog  │  Kanban  │    Roadmap       │    │
│  │   View   │   Board  │      View        │    │
│  └──────────┴──────────┴──────────────────┘    │
│              Modal Components                   │
│  (Task Edit, Settings, Search, Reports)         │
└─────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────┐
│          Application Controller                 │
│  ┌──────────┬──────────┬──────────────────┐    │
│  │   Task   │  Sprint  │     Team         │    │
│  │ Manager  │ Manager  │   Manager        │    │
│  └──────────┴──────────┴──────────────────┘    │
│  ┌──────────┬──────────┬──────────────────┐    │
│  │  Search  │ Analytics│    Activity      │    │
│  │  Engine  │  Engine  │     Logger       │    │
│  └──────────┴──────────┴──────────────────┘    │
└─────────────────────────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────┐
│            Data Access Layer                    │
│  ┌──────────────────┬──────────────────────┐   │
│  │ LocalStorage     │  Firebase Adapter    │   │
│  │ Adapter          │  (Optional)          │   │
│  └──────────────────┴──────────────────────┘   │
└─────────────────────────────────────────────────┘
```

### Key Design Patterns

#### State Management Pattern
```javascript
// Global State (Reactive)
let tasks = [];                    // All task objects
let team = [...DEFAULT_TEAM];      // Team members with capacity
let sprintConfig = { number: 1, days: 14, current: 4 };
let sprintHistory = [];            // Completed sprints archive
let activityLog = [];              // Audit trail (last 100 actions)

// State Update Flow
updateState() → savePersistence() → refreshView() → updateDashboard()
```

#### Event-Driven Architecture
- User actions trigger event handlers (`onclick`, `onchange`)
- Events update global state
- State changes automatically persist to LocalStorage/Firebase
- Views re-render based on state updates
- Dashboard updates in real-time

#### Component Hierarchy
```
App (index.html)
├── Header
│   ├── Logo & Title
│   ├── View Picker
│   ├── Capacity Tracker
│   └── Action Buttons (Search, Reports, Analytics, Settings, New Item)
├── Quick Filters Bar
├── Workload Dashboard (Team Members)
├── Main Viewport
│   ├── Backlog View
│   │   ├── Epic Cards (Expandable)
│   │   └── Completed Sprints Archive
│   ├── Kanban Board View
│   │   ├── Sprint Progress Bar
│   │   └── Column Containers (Todo, Dev, Testing, Done)
│   └── Roadmap View
│       └── Epic Timeline
└── Footer
    ├── Copyright & License
    └── System Status

Modals (Overlay Components)
├── Task Edit Modal
├── Settings Modal
├── Search Modal
├── Report Modal
└── Burndown Analytics Modal
```

## 🔧 Configuration

### Firebase Integration (Optional - For Multi-User Support)

By default, the app uses LocalStorage for single-user demo mode. To enable cloud sync and multi-user collaboration:

#### Step 1: Create Firebase Project

1. Visit [Firebase Console](https://console.firebase.google.com)
2. Click **"Add project"**
3. Enter project name and follow setup wizard
4. Enable **Firestore Database**
5. Copy your Firebase configuration object

#### Step 2: Update index.html

Locate the Firebase configuration section in `index.html` (search for `firebaseConfig`) and update:

```javascript
const firebaseConfig = {
  apiKey: "your-api-key-here",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "123456789",
  appId: "1:123456789:web:abcdef123456"
};
```

#### Step 3: Set Up Firestore Security Rules

In Firebase Console → Firestore Database → Rules:

```javascript
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{collection}/{document} {
      allow read, write: if request.auth != null;
    }
  }
}
```

#### Step 4: Enable Authentication (Optional)

For multi-user support with authentication:

1. Go to Firebase Console → Authentication
2. Enable Email/Password or Google Sign-In
3. Update `index.html` with auth logic

### Customization Options

#### Branding & Theming

**Change Primary Colors:**
```html
<!-- In index.html, find and modify Tailwind config -->
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        colors: {
          primary: '#6366f1', // Change from indigo to your brand color
          secondary: '#4f46e5'
        }
      }
    }
  }
</script>
```

**Update Logo:**
```html
<!-- Replace icon in header section -->
<div class="bg-gradient-to-br from-indigo-600 to-indigo-700">
  <i data-feather="grid"></i> <!-- Change to another Feather icon -->
</div>
```

#### Workflow Customization

**Modify Status Columns:**
```javascript
// In index.html, find COLUMNS constant (around line 397)
const COLUMNS = [
    { id: 'todo', title: 'To Do', icon: 'clipboard', color: 'text-blue-500' },
    { id: 'dev', title: 'Dev In Progress', icon: 'code', color: 'text-indigo-500' },
    { id: 'testing', title: 'Testing', icon: 'activity', color: 'text-purple-500' },
    { id: 'done', title: 'Done', icon: 'check-circle', color: 'text-emerald-500' }
];

// Add custom column:
{ id: 'review', title: 'Code Review', icon: 'eye', color: 'text-pink-500' }
```

**Customize Story Points:**
```javascript
// Modify Fibonacci sequence in task form (around line 227)
<select id="task-points">
    <option value="0">0 pts</option>
    <option value="1">1 pt</option>
    <option value="2">2 pts</option>
    <option value="3">3 pts</option>
    <option value="5">5 pts</option>
    <option value="8">8 pts</option>
    <option value="13">13 pts</option>
    <!-- Add custom values -->
    <option value="20">20 pts</option>
    <option value="40">40 pts</option>
</select>
```

**Adjust Sprint Duration:**
```javascript
// Default sprint settings (around line 412)
sprintConfig = { 
    number: 1, 
    days: 14,    // Change to your preferred duration
    current: 0 
};
```

#### Task Type Customization

Add custom task types by modifying the type selector:

```html
<select id="task-type">
    <option value="epic">Epic</option>
    <option value="feature">Feature</option>
    <option value="story">Story</option>
    <option value="bug">Bug</option>
    <!-- Add custom types -->
    <option value="spike">Spike</option>
    <option value="chore">Chore</option>
</select>
```

## 🧪 Testing

### Current Testing Approach (Manual)

Since this is a lightweight, browser-based application without a build system, testing is primarily manual:

#### Visual Testing Checklist
- [ ] All views render correctly (Backlog, Kanban, Roadmap)
- [ ] Modals open and close properly
- [ ] Drag-and-drop works in target browsers
- [ ] Capacity indicators show correct colors
- [ ] Sprint progress bar updates accurately
- [ ] Burndown chart renders with data

#### Functional Testing Checklist
- [ ] Create tasks of all types (Epic, Feature, Story, Bug)
- [ ] Edit task details and save changes
- [ ] Move tasks between status columns
- [ ] Plan sprint from backlog
- [ ] Complete sprint with retrospective
- [ ] Add/edit team members
- [ ] Search and filter functionality
- [ ] Generate and copy reports
- [ ] Data persists after page reload

#### Cross-Browser Testing
Test on minimum supported versions:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

#### Performance Testing
- Load time under 2 seconds
- Smooth animations at 60fps
- No memory leaks after extended use
- LocalStorage operations complete under 100ms

### Automated Testing (Planned)

Future versions may include automated tests using:

**Unit Tests (Jest):**
```javascript
describe('getEffectivePoints', () => {
  test('returns points for story', () => {
    const task = { type: 'story', points: 5 };
    expect(getEffectivePoints(task)).toBe(5);
  });
  
  test('rolls up points from children', () => {
    // Test implementation
  });
});
```

**Integration Tests (Testing Library):**
```javascript
test('creates new task successfully', async () => {
  render(<App />);
  fireEvent.click(screen.getByText('New Item'));
  // Continue test scenario
});
```

**E2E Tests (Playwright/Cypress):**
```javascript
test('full sprint lifecycle', async ({ page }) => {
  await page.goto('/');
  await page.click('[data-testid="new-item"]');
  // Complete workflow test
});
```

### Debugging Tips

**Browser Console Commands:**
```javascript
// Check current state
console.log({ tasks, team, sprintConfig });

// Clear all data
localStorage.clear();
location.reload();

// Export data for backup
JSON.stringify({
  tasks: tasks,
  team: team,
  sprint: sprintConfig,
  history: sprintHistory
});

// Import data (paste into console)
const data = /* paste exported JSON */;
localStorage.setItem('agile_v50_tasks', JSON.stringify(data.tasks));
localStorage.setItem('agile_v50_team', JSON.stringify(data.team));
location.reload();
```

**Common Issues & Solutions:**

| Issue | Cause | Solution |
|-------|-------|----------|
| Drag-and-drop not working | Browser compatibility | Use Chrome/Firefox/Edge; Safari 14+ |
| Data lost on refresh | LocalStorage cleared | Check browser settings; not in incognito mode |
| Modal won't close | JavaScript error | Open DevTools console, check for errors |
| Capacity shows incorrect | Tasks not assigned | Ensure assignee is set on all sprint tasks |
| Slow performance | Too many tasks (>200) | Archive old sprints; consider Firebase migration |

## 🤝 Contributing

We welcome contributions from the community! Please follow these guidelines:

### Development Workflow

#### 1. Fork the Repository
```bash
# Click "Fork" on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/agile-backlog-manager.git
cd agile-backlog-manager
```

#### 2. Create a Feature Branch
```bash
git checkout -b feature/amazing-feature
# Example: feature/add-dark-mode
# Example: feature/firebase-integration
```

#### 3. Make Your Changes
- Edit `index.html` (all code is in this single file)
- Follow existing code style and conventions
- Add comments for complex logic
- Test thoroughly in multiple browsers

#### 4. Commit Changes
```bash
git add .
git commit -m "feat: add amazing feature"

# Use Conventional Commits format:
# feat: New feature
# fix: Bug fix
# docs: Documentation changes
# style: Code style (formatting)
# refactor: Code refactoring
# test: Adding tests
# chore: Build/config changes
```

#### 5. Push and Create Pull Request
```bash
git push origin feature/amazing-feature
```

Then on GitHub:
- Navigate to your fork
- Click "Compare & pull request"
- Describe your changes
- Reference any related issues
- Submit PR

### Code Standards

#### JavaScript Style Guide
- Use ES6+ features (arrow functions, template literals, destructuring)
- Consistent naming: camelCase for variables/functions, UPPER_CASE for constants
- Add JSDoc comments for complex functions
- Keep functions small and focused (< 50 lines ideal)

```javascript
// ✅ Good
const DEFAULT_TEAM = [...];

function calculateTeamUtilization() {
    // Implementation
}

// ❌ Avoid
var team = [];  // Use const/let
function CalcTeamUtil () {  // Use descriptive names
```

#### HTML/CSS Standards
- Semantic HTML5 elements
- Tailwind utility classes over custom CSS
- Responsive design (mobile-first approach)
- Accessible markup (ARIA attributes where needed)

```html
<!-- ✅ Good -->
<button onclick="openModal()" class="bg-indigo-600 hover:bg-indigo-700">
  <i data-feather="plus"></i> New Item
</button>

<!-- ❌ Avoid inline styles -->
<div style="color: blue; font-size: 16px;">  <!-- Use Tailwind classes -->
```

#### Testing Requirements
Before submitting a PR:
- [ ] Test in Chrome, Firefox, Safari, Edge
- [ ] Verify responsive design on mobile/tablet
- [ ] Check keyboard navigation
- [ ] Ensure data persistence works
- [ ] No console errors or warnings
- [ ] Performance acceptable with 100+ tasks

### Bug Reports

Use GitHub Issues to report bugs:

**Bug Report Template:**
```markdown
**Describe the bug**
Clear description of what happened

**To Reproduce**
Steps to reproduce:
1. Go to '...'
2. Click on '...'
3. Scroll down to '...'
4. See error

**Expected behavior**
What should have happened

**Screenshots**
If applicable, add screenshots

**Environment:**
- Browser: [e.g., Chrome 91]
- OS: [e.g., macOS 11.4]
- Device: [e.g., Desktop, iPhone 12]

**Additional context**
Any other details about the problem
```

### Feature Requests

We love new ideas! Submit feature requests using this template:

```markdown
**Is your feature request related to a problem?**
Describe the problem (e.g., "I'm frustrated when...")

**Describe the solution you'd like**
What you want to happen

**Describe alternatives you've considered**
Other solutions you've thought about

**Additional context**
Any other details, mockups, or examples
```

### Pull Review Process

1. **Automated Checks**: CI runs (once implemented)
2. **Code Review**: Maintainer reviews code quality
3. **Testing**: Manual testing of feature
4. **Feedback**: Reviewer provides feedback
5. **Revisions**: Address feedback and update PR
6. **Merge**: Approved PR merged to main

Typical review time: 2-5 business days

## 📝 Roadmap

See [ARCHITECTURE.md](ARCHITECTURE.md) for detailed technical roadmap with timelines.

### Upcoming Features (2024-2025)

#### Phase 1: Enhanced Collaboration (Q2 2024)
- [ ] **Real-time Multi-user Support**
  - Firebase integration for live sync
  - WebSocket-based updates
  - Conflict resolution
  
- [ ] **User Authentication**
  - Email/password login
  - Google OAuth
  - Role-based access (Admin, Member, Viewer)
  
- [ ] **Team Collaboration**
  - Task comments and discussions
  - @mentions for team members
  - Activity feed notifications

#### Phase 2: Advanced Features (Q3 2024)
- [ ] **Advanced Reporting Dashboard**
  - Cumulative flow diagrams
  - Velocity trend charts
  - Custom report builder
  
- [ ] **External Integrations**
  - GitHub Issues synchronization
  - Jira import/export
  - Slack notifications
  - Microsoft Teams integration
  
- [ ] **Time Tracking**
  - Manual time logging
  - Timer integration
  - Timesheet reports

#### Phase 3: Platform Expansion (Q4 2024)
- [ ] **Mobile Applications**
  - React Native iOS app
  - React Native Android app
  - Offline-first architecture
  
- [ ] **Progressive Web App (PWA)**
  - Service worker implementation
  - Offline functionality
  - Push notifications
  - Install to home screen
  
- [ ] **Desktop Apps**
  - Electron wrapper (Windows/Mac/Linux)
  - System tray integration
  - Global keyboard shortcuts

#### Phase 4: Enterprise Features (Q1 2025)
- [ ] **Advanced Workflow Customization**
  - Custom status columns
  - Custom task types
  - Custom fields and metadata
  - Automation rules
  
- [ ] **Portfolio Management**
  - Multiple project boards
  - Cross-project dependencies
  - Resource allocation
  - Executive dashboards
  
- [ ] **AI-Powered Insights**
  - Sprint planning recommendations
  - Velocity predictions
  - Bottleneck detection
  - Automated retrospective insights

### Technical Improvements
- [ ] TypeScript migration for type safety
- [ ] Module bundling with Webpack/Vite
- [ ] Comprehensive test suite (Jest, Playwright)
- [ ] CI/CD pipeline automation
- [ ] Virtual scrolling for large datasets
- [ ] WCAG 2.1 AA accessibility compliance
- [ ] Internationalization (i18n) support
- [ ] Dark mode theme

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What MIT License Means

✅ **You can:**
- Use this software for personal or commercial projects
- Modify and adapt the code
- Distribute copies
- Sublicense or sell modified versions
- Use in private/proprietary projects

⚠️ **You must:**
- Include the original copyright notice
- Include a copy of the MIT License
- Preserve the license text in all copies

📜 **Full License Text:**
```
MIT License

Copyright (c) 2024 Ashish Kumar Sankhua

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👨‍💻 Author

**Ashish Kumar Sankhua**

- GitHub: [@asankhua](https://github.com/asankhua)
- Project: [Agile Backlog Manager Pro](https://github.com/asankhua/agile-backlog-manager)

### Acknowledgments

- Built with [Tailwind CSS](https://tailwindcss.com)
- Icons by [Feather Icons](https://feathericons.com)
- Font by [Google Fonts](https://fonts.google.com)

---

## 🙏 Support

### Show Your Support

If you find this project useful, consider supporting:

⭐ **Star the Repository** - Helps others discover the project  
🐛 **Report Bugs** - Help improve quality  
💡 **Suggest Features** - Share your ideas  
📢 **Spread the Word** - Tell your team and friends  
🤝 **Contribute** - Submit PRs for features or fixes

### Contact & Communication

- **Issues**: Use [GitHub Issues](https://github.com/asankhua/agile-backlog-manager/issues) for bugs and feature requests
- **Discussions**: Participate in community discussions (coming soon)
- **Email**: (Optional - add your contact info here)

---

## 📊 Project Statistics

- **Total Lines of Code**: ~1040 (single file!)
- **File Count**: 1 HTML file (contains all HTML, CSS, JS)
- **Dependencies**: 0 npm packages (uses CDN only)
- **Bundle Size**: ~85 KB (uncompressed)
- **Load Time**: < 2 seconds on modern browsers
- **Browser Support**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+

---

## 🎓 Learning Resources

### Learn the Technologies Used

**HTML5 & Semantic Markup:**
- [MDN HTML Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

**Tailwind CSS:**
- [Official Documentation](https://tailwindcss.com/docs)
- [Tailwind UI Components](https://tailwindui.com/components)

**Vanilla JavaScript ES6+:**
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [ES6 Features Overview](https://github.com/lukehoban/es6features)

**Agile & Scrum:**
- [Scrum Guide](https://scrumguides.org/)
- [Atlassian Agile Coach](https://www.atlassian.com/agile)

---

## 🔗 Related Projects

Looking for similar tools?

- **Trello** - Visual collaboration tool
- **Jira** - Enterprise agile platform
- **Azure DevOps** - Microsoft's development platform
- **Linear** - Modern issue tracking
- **ClickUp** - All-in-one productivity platform

**Why Choose Agile Backlog Manager Pro?**
- ✅ Completely free and open source
- ✅ No installation or setup required
- ✅ No account creation needed
- ✅ Works offline (LocalStorage mode)
- ✅ Simple and lightweight
- ✅ Perfect for small teams and learning

---

---

**Last Updated**: March 20, 2026  
**Version**: 1.0.0  
**Status**: Production Ready ✅

---

Made with ❤️ by Ashish Kumar Sankhua

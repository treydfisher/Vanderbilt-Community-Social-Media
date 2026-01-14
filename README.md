# Student-Orgs-Social-Media

A short-form content inspired social media platform designed exclusively for the Vanderbilt University community. Connect with professors, discover events, and engage with student organizations through short-form video content and posts.

## 📱 Overview

This platform brings together the Vanderbilt community by enabling:
- **Professors** to share class updates, announcements, and educational content
- **Event Organizers** to highlight speakers, workshops, and campus events
- **Student Organizations** to promote events, share updates, and build community

## ✨ Features

### Core Functionality
- **Short-Form Video Content**: Post and view TikTok-style vertical videos
- **User Profiles**: Customizable profiles for professors, organizations, and students
- **Feed System**: Personalized feed with content from followed accounts
- **Event Highlighting**: Special features for promoting and discovering campus events
- **Engagement Tools**: Like, comment, share, and save posts
- **Search & Discovery**: Find content, users, and events across the platform

### User Roles
- **Professors**: Post class-related content, announcements, and educational materials
- **Student Organizations**: Share event updates, organization news, and community content
- **Event Organizers**: Highlight speakers, workshops, and special events
- **Students**: Engage with content, follow accounts, and discover campus happenings

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher) or Python (v3.8 or higher) - depending on your tech stack
- npm/yarn or pip - package manager
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Student-Orgs-Social-Media.git
   cd Student-Orgs-Social-Media
   ```

2. **Install dependencies**
   ```bash
   # If using Node.js
   npm install
   # or
   yarn install
   
   # If using Python
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   ```bash
   # Create a .env file with necessary configuration
   cp .env.example .env
   # Edit .env with your database credentials, API keys, etc.
   ```

4. **Run the application**
   ```bash
   # Development server
   npm run dev
   # or
   python app.py
   ```

## 🏗️ Project Structure

```
Student-Orgs-Social-Media/
├── README.md
├── .env.example
├── src/                    # Source code
│   ├── components/         # Reusable UI components
│   ├── pages/              # Page components
│   ├── services/           # API services
│   └── utils/              # Utility functions
├── public/                 # Static assets
└── docs/                   # Documentation
```

## 🎯 Usage

### For Professors
1. Create a professor account
2. Verify your Vanderbilt affiliation
3. Start posting class updates, announcements, or educational content
4. Engage with student questions and feedback

### For Student Organizations
1. Register your organization
2. Get verified as an official Vanderbilt organization
3. Post event announcements, meeting updates, and organization highlights
4. Build your community and increase engagement

### For Event Organizers
1. Create an event post
2. Add event details, date, time, and location
3. Highlight speakers and special features
4. Promote your event to the Vanderbilt community

## 🔧 Configuration

### Environment Variables
- `DATABASE_URL`: Database connection string
- `JWT_SECRET`: Secret key for authentication
- `AWS_ACCESS_KEY`: AWS credentials for media storage (if applicable)
- `AWS_SECRET_KEY`: AWS secret key
- `PORT`: Server port (default: 3000)

## 🤝 Contributing

We welcome contributions from the Vanderbilt community! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow the existing code style
- Write clear commit messages
- Add tests for new features
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Team

- Vanderbilt University Community

## 📧 Contact

For questions, suggestions, or support, please open an issue on GitHub or contact the development team.

## 🗺️ Roadmap

- [ ] User authentication and authorization
- [ ] Video upload and processing
- [ ] Feed algorithm and personalization
- [ ] Event management system
- [ ] Notification system
- [ ] Analytics dashboard
- [ ] Mobile app (iOS/Android)

## 🙏 Acknowledgments

- Inspired by TikTok's short-form video format
- Built for the Vanderbilt University community
- Special thanks to all contributors and early adopters

---

**Note**: This platform is designed exclusively for the Vanderbilt University community. All users must have a valid Vanderbilt affiliation to participate.

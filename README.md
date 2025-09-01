# 🧠 MindMend - Advanced Mental Health Support Platform

A comprehensive, AI-powered mental health support system designed for colleges and universities, featuring real-time analytics, interactive tools, and professional-grade mental health resources.

## ✨ **Enhanced Features**

### 🏛️ **Institutional Dashboard**
- **Secure Login System**: Institution-specific access with demo credentials
- **Student Analytics**: Comprehensive tracking of mental health metrics
- **Risk Assessment**: AI-powered identification of at-risk students
- **Real-time Data**: Live statistics and trend analysis
- **Administrative Tools**: Student management and reporting capabilities

**Demo Login:**
- Institution Code: `DEMO123`
- Username: `admin`
- Password: `password123`

### 👥 **Enhanced Support Groups**
- **Live Sessions**: Real-time indicators for ongoing sessions
- **Group Analytics**: Member counts, online status, activity rates
- **Smart Group Management**: Status indicators (Active/Paused/Full)
- **Chat Previews**: Recent activity snippets from each group
- **Waitlist System**: For groups at full capacity

### 🎮 **Stress Booster Games (3 Working Games)**
- **🎈 Balloon Popping**: Timed challenge with score tracking
- **🏀 Stress Ball Squeeze**: 60-second squeezing challenge
- **🫁 Breathing Exercise**: Guided breathing with visual cues
- **Score Persistence**: Local storage for high scores
- **Responsive Design**: Works on all devices

### 🧠 **Advanced Mood Detector**
- **Real Camera Integration**: Working webcam with getUserMedia API
- **TensorFlow.js AI**: Face landmark detection and analysis
- **Real-time Emotion Detection**: Facial expression analysis
- **AI Insights**: Personalized recommendations based on emotions
- **Detailed Analytics**: Emotion breakdown with confidence scores
- **Face Overlay**: Visual feedback showing detected features

### 📚 **Enhanced Resource Library**
- **Advanced Search**: Multi-criteria filtering system
- **Responsive Design**: Optimized for PC and mobile
- **Interactive Cards**: Hover effects and animations
- **Download System**: Various resource formats available
- **Category Management**: Organized resource classification

## 🚀 **Quick Start**

### **Local Development**
```bash
# Clone the repository
git clone <your-repo-url>
cd "Wellness connect webpage"

# Start local server
python -m http.server 8000

# Open in browser
http://localhost:8000
```

### **Access Enhanced Features**
- **Main Platform**: `http://localhost:8000/`
- **Institutional Dashboard**: `http://localhost:8000/institutional_dashboard.html`
- **Support Groups**: `http://localhost:8000/support_groups.html`
- **Stress Booster Games**: `http://localhost:8000/stress_booster_game.html`
- **Mood Detector**: `http://localhost:8000/mood_detector.html`
- **Resource Library**: `http://localhost:8000/resource_library.html`

## 🛠️ **Technical Stack**

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **AI/ML**: TensorFlow.js, Face Landmarks Detection
- **UI Framework**: Custom CSS with Glassmorphism design
- **Responsive Design**: Mobile-first approach
- **Real-time Features**: WebRTC, Canvas API
- **Data Storage**: Local Storage, Session Storage

## 📱 **Responsive Design**

All pages are fully responsive and optimized for:
- **Desktop**: Full-featured experience
- **Tablet**: Touch-optimized interface
- **Mobile**: Mobile-first responsive design
- **All Browsers**: Cross-browser compatibility

## 🔐 **Security Features**

- **Institutional Authentication**: Secure login system
- **Data Privacy**: Anonymous student tracking
- **Session Management**: Secure logout functionality
- **Permission-based Access**: Role-based dashboard access

## 📊 **Analytics & Insights**

- **Student Engagement**: Usage patterns and trends
- **Mental Health Metrics**: Stress levels, mood patterns
- **Resource Effectiveness**: Impact measurement
- **Risk Assessment**: Early intervention identification
- **Performance Tracking**: Service utilization analytics

## 🎯 **Use Cases**

### **For Colleges & Universities**
- **Mental Health Monitoring**: Track student well-being
- **Resource Management**: Optimize mental health services
- **Early Intervention**: Identify at-risk students
- **Compliance Reporting**: Generate institutional reports
- **Staff Training**: Professional development resources

### **For Students**
- **Stress Relief**: Interactive games and exercises
- **Mood Tracking**: AI-powered emotional analysis
- **Peer Support**: Connect with support groups
- **Resource Access**: Comprehensive mental health library
- **Self-Assessment**: Confidential screening tools

## 🚀 **Deployment**

### **Vercel Deployment**
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy to Vercel
vercel --prod
```

### **GitHub Pages**
```bash
# Push to GitHub
git add .
git commit -m "Enhanced MindMend platform with AI features"
git push origin main

# Enable GitHub Pages in repository settings
```

## 🔧 **Configuration**

### **Environment Variables**
- `VERCEL_PROJECT_ID`: Vercel project identifier
- `AI_MODEL_URL`: TensorFlow.js model endpoint
- `INSTITUTION_CODE`: Default institution code

### **Customization**
- **Branding**: Update colors and logos
- **Features**: Enable/disable specific modules
- **Analytics**: Configure tracking parameters
- **Security**: Adjust authentication settings

## 📈 **Performance Features**

- **Lazy Loading**: Optimized resource loading
- **Caching**: Browser-level caching strategies
- **Compression**: Optimized assets and images
- **CDN Ready**: Vercel edge network optimization

## 🧪 **Testing**

### **Browser Compatibility**
- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)

### **Device Testing**
- ✅ Desktop (1920x1080+)
- ✅ Tablet (768px-1024px)
- ✅ Mobile (320px-767px)
- ✅ Touch Devices

## 🤝 **Contributing**

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 **License**

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 **Support**

For support and questions:
- **Documentation**: Check this README
- **Issues**: Open GitHub issues
- **Contact**: Reach out to the development team

## 🎉 **Acknowledgments**

- **TensorFlow.js** for AI capabilities
- **Vercel** for hosting and deployment
- **Open Source Community** for inspiration and tools

---

**Built with ❤️ for better mental health support in education**

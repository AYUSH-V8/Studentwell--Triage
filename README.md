# StudentWell - AI-Powered Psychological Triage System

## 🧠 Overview
StudentWell is an **AI-powered psychological triage system** designed for universities to identify students at risk of mental health issues. It combines a simple assessment interface with an admin dashboard for monitoring student well-being.

## ✨ Features
- **Student Assessment**: 3-question mental health screening
- **AI Risk Scoring**: Automatic risk classification (Low/Medium/High)
- **Admin Dashboard**: View all student assessments with risk levels
- **Local Storage**: No database setup required - uses browser storage
- **Password Protected**: Secure admin access
- **Responsive Design**: Works on desktop and mobile



## 📋 How to Use
### For Students:
1. Go to **"Student Assessment"** tab
2. Enter your Student ID
3. Answer 3 simple questions (click buttons 0-4)
4. Click **Submit Assessment**
5. View your personalized risk assessment and suggestions

### For Administrators:
1. Go to **"Admin Dashboard"** tab  
2. Enter password: `admin123`
3. View all student assessments in table format
4. See risk statistics (High/Medium/Low counts)

## 🔐 Default Credentials
- **Admin Password**: `admin123` (change in code if needed)
- **Student IDs**: Any text/number (auto-created on first assessment)

## 🏗️ Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Storage**: Browser LocalStorage
- **Deployment**: Single HTML file - no server needed
- **AI Logic**: Custom scoring algorithm

## 📊 Assessment Logic
- **3 Questions**: Depression, Anxiety, Sleep quality
- **Scoring**: 0-4 per question (12 points total)
- **Risk Levels**:
  - **Low Risk**: 0-4 points ("Doing well")
  - **Medium Risk**: 5-8 points ("Consider counseling")
  - **High Risk**: 9-12 points ("Contact counseling immediately")

## 🎯 Target Users
- **Universities**: Campus mental health programs
- **Schools**: Student well-being monitoring
- **Counseling Centers**: Early intervention tool
- **Researchers**: Anonymous mental health data collection

## ⚠️ Important Notes
- **Not a diagnostic tool**: This is for triage, not diagnosis
- **Privacy**: All data stays in browser (LocalStorage)
- **Confidential**: Student IDs are not transmitted anywhere
- **Limitation**: Browser-based - data lost if cache cleared




## 🌟 Benefits
- **Early Intervention**: Identify at-risk students early
- **Scalable**: No server costs, runs anywhere
- **Privacy-Focused**: Data never leaves user's computer
- **Easy Deployment**: Just upload HTML file to any web server
- **Zero Maintenance**: No database administration needed

## 🤝 Contributing
1. Fork the repository
2. Create feature branch
3. Make improvements
4. Submit pull request

## 📄 License
Open source - free for educational and non-commercial use

## ⚡ Live Demo
Simply open the  file in any modern browser!

---

**Note**: For production use in universities, consider:
1. Adding encryption for data storage
2. Connecting to a real database
3. Implementing user authentication
4. Adding reporting features
5. Consulting with mental health professionals

---
*Developed for UNICEF-inspired mental health initiatives*

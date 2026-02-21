# 🎓 Online Mock Test Platform

A modern, feature-rich online examination platform designed for conducting mock tests with real-time monitoring, customizable configurations, and an intuitive user interface.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## ✨ Features

### 🎯 Test Configuration
- **Multiple Test Types**: Choose from NCERT-based, KCET pattern, or general mock tests
- **Flexible Question Counts**: Select 25, 40, 60, or 90 questions per subject
- **Multi-Subject Support**: Physics, Chemistry, and Mathematics sections
- **Dynamic Duration**: Automatic timer adjustment based on question count
  - 25 questions → 90 minutes
  - 40 questions → 120 minutes
  - 60 questions → 180 minutes
  - 90 questions → 240 minutes

### 👤 Student Profile Management
- College/Institution logo upload
- Student photo upload
- Name and roll number registration
- Personalized exam interface

### 📝 Exam Interface
- **Fullscreen Mode**: Immersive exam experience with automatic fullscreen
- **Real-time Timer**: Countdown timer with warning alerts
- **Question Navigation**: Easy navigation between questions
- **Question Palette**: Visual status tracking for all questions
- **Mark for Review**: Flag questions for later review
- **Answer Status Tracking**:
  - ✅ Answered
  - ❌ Not Answered
  - 🔖 Marked for Review
  - ⚪ Not Visited

### 🎨 Modern UI/UX
- Clean, professional interface
- Responsive design
- Smooth animations and transitions
- Color-coded status indicators
- Font Awesome icons

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server-side dependencies required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Prasidhpshetty7/mock-test-platform.git
cd mock-test-platform
```

2. Open `exam.html` in your browser:
```bash
# On Windows
start exam.html

# On macOS
open exam.html

# On Linux
xdg-open exam.html
```

### Deployment

#### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

3. For production:
```bash
vercel --prod
```

#### Deploy to Netlify

1. Drag and drop the project folder to [Netlify Drop](https://app.netlify.com/drop)

Or use Netlify CLI:
```bash
npm i -g netlify-cli
netlify deploy --prod
```

#### Deploy to GitHub Pages

1. Push to GitHub
2. Go to Settings → Pages
3. Select branch and save

## 📁 Project Structure

```
mock-test-platform/
├── exam.html          # Main application file (single-file app)
├── app.html           # Alternative configuration interface
├── index.html         # Landing page
├── vercel.json        # Vercel deployment configuration
├── package.json       # Project metadata
├── README.md          # Documentation
└── LICENSE            # MIT License
```

## 🎮 Usage

### Step 1: Configure Test
1. Select test type (NCERT/KCET/Mock)
2. Choose question count per subject (25/40/60/90)
3. Review test summary
4. Click "Continue to Profile Setup"

### Step 2: Profile Setup
1. Upload college/institution logo
2. Enter full name
3. Enter roll number/ID
4. Upload student photo
5. Click "Start Exam"

### Step 3: Take Exam
1. Exam enters fullscreen mode automatically
2. Answer questions using the interface
3. Use navigation buttons to move between questions
4. Mark questions for review if needed
5. Monitor time remaining
6. Submit test when complete

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icon library
- **Fullscreen API**: Immersive exam experience

## 🎨 Customization

### Modify Question Bank
Edit the `sampleQuestion` object in `exam.html`:
```javascript
const sampleQuestion = {
    text: "Your question here",
    options: ["Option A", "Option B", "Option C", "Option D"]
};
```

### Change Color Scheme
Update CSS variables in the `<style>` section:
```css
/* Primary colors */
--primary: #2563eb;
--success: #10b981;
--warning: #f59e0b;
--danger: #ef4444;
```

### Adjust Timer Duration
Modify the `durationMap` in the configuration:
```javascript
const durationMap = { 25: 90, 40: 120, 60: 180, 90: 240 };
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Prasidh P Shetty**

- GitHub: [@Prasidhpshetty7](https://github.com/Prasidhpshetty7)
- Website: [prasidhshetty.in](https://prasidhshetty.in)

## 🙏 Acknowledgments

- Font Awesome for icons
- Inspiration from real examination platforms
- Modern web design principles

## 📧 Support

For support, email through [prasidhshetty.in](https://prasidhshetty.in) or open an issue on GitHub.

## 🔮 Future Enhancements

- [ ] Backend integration for result storage
- [ ] Question bank management system
- [ ] Analytics dashboard
- [ ] Multi-language support
- [ ] PDF result generation
- [ ] Email notifications
- [ ] Admin panel
- [ ] Question randomization
- [ ] Negative marking configuration
- [ ] Mobile app version

---

⭐ Star this repository if you find it helpful!

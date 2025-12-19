# target-scoring-app-2025

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
Web-based target scoring application for shooting training

---

## 📋 Overview

Target Scoring App is a web-based application designed to support shooting training activities by recording, calculating, and managing shooting scores. This system is intended to replace manual recording processes and improve data accuracy and documentation.

---

## ✨ Features

### Core Features
- ✅ Web-based interface for shooting data input
- ✅ Automatic recording and calculation of shooting scores
- ✅ Personnel database management (import/export)
- ✅ Multi-session support (Long Barrel / Pistol)
- ✅ Multi-iteration training tracking (up to 3 sessions per personnel)
- ✅ Real-time accuracy calculation
- ✅ Detailed ring scoring (R1-R10) with miss tracking

### Data Management
- ✅ **Offline Mode**: Local storage with CSV export
- ✅ **Online Mode**: Auto-sync to Google Form/Sheets
- ✅ **Sync Queue**: Automatic retry when connection restored
- ✅ Connection status indicator
- ✅ Manual sync capability

### User Experience
- ✅ Mobile-optimized interface
- ✅ Auto-complete personnel search
- ✅ Variable bullet count support
- ✅ Input validation and warnings
- ✅ Multi-device simultaneous usage

---

## 🚀 Installation

### Quick Start
1. Download `target-scoring-app-2025.html`
2. Open with **Via Browser** (Android) or **Chrome** (PC/Mac)
3. Import your personnel database
4. Start scoring!

### Google Form Setup (Optional - for Online Sync)

**Important:** You must create your own Google Form to use online sync features.

1. Create a new Google Form with 20 fields (see configuration guide)
2. Get your `formResponse` URL
3. Extract Entry IDs using pre-fill mode
4. Update configuration in HTML file:
```javascript
const GOOGLE_FORM_CONFIG = {
    formUrl: 'https://docs.google.com/forms/d/e/[YOUR-FORM-ID]/formResponse',
    entryIds: {
        rank: 'entry.XXXXXXX',
        name: 'entry.XXXXXXX',
        nrp: 'entry.XXXXXXX',
        // ... update all 20 entry IDs
    }
};
```

**Note:** Detailed setup instructions are available in the user manual (contact developer for access).

---

## 💻 System Requirements

### Minimum Requirements
- **Device**: Android smartphone or PC
- **OS**: Android 7.0+ / Windows 7+ / macOS 10.12+
- **RAM**: 2 GB
- **Storage**: ~1 MB free space
- **Browser**: Via Browser (recommended for Android), Chrome, Firefox
- **Internet**: Optional (only for Google Form sync)

### Recommended
- **RAM**: 4 GB or more
- **Screen**: 5.5 inch or larger
- **Processor**: Octa-core 2.0 GHz

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Storage**: LocalStorage API
- **Integration**: Google Forms API
- **Data Format**: CSV export support
- **Architecture**: Single-file application (no dependencies)

---

## 🔄 Workflow

1. **Setup**: Import personnel database from Excel
2. **Session**: Select weapon type (Long Barrel/Pistol)
3. **Input**: Search personnel, enter ring scores
4. **Calculate**: Automatic score and accuracy calculation
5. **Save**: Local storage + optional Google Form sync
6. **Export**: Download CSV for analysis and reporting

---

## 📱 Usage Scenarios

### Online Mode
- Data automatically synced to Google Sheets
- Real-time collaboration across multiple devices
- Centralized data repository
- Instant backup

### Offline Mode
- Full functionality without internet
- Data queued for sync when online
- CSV export for manual backup
- Perfect for field training locations

---

## 🔮 Project Status & Roadmap

### Current Version: v9 (Fixed & Verified)
✅ Core scoring functionality  
✅ Offline/Online hybrid mode  
✅ Multi-device support  
✅ Data export capabilities  

### Future Plans
- 🔄 Web-based monitoring dashboard
- 🤖 Automated target detection using computer vision
- 🎯 AI-assisted scoring with smartphone camera
- 📊 Advanced analytics and performance tracking
- 📱 Native mobile app (Android/iOS)

---

## ⚠️ Important Notes

### Data Privacy
- All personnel data is stored locally on your device
- Google Form integration is optional
- You control where your data is stored
- No data is sent to third-party servers (except your own Google Form)

### Security Considerations
- Keep your Google Form URL private
- Regularly backup your data
- Use secure networks for online sync
- Follow your institution's data security policies

### Disclaimer
This application is developed as a training support tool. Users are responsible for:
- Proper setup and configuration
- Data security and privacy compliance
- Following institutional regulations
- Regular data backups

The developer assumes no liability for misuse, data loss, or security breaches.

---

## 👨‍💻 Author

**Hardianto** ([@hardi2024](https://github.com/hardi2024))

Lead Developer - Target Scoring Application

*Developed in collaboration with training operations team to support shooting training management system.*

---

## 🤝 Acknowledgments

Special thanks to:
- System design and operations team
- Documentation team
- All contributors who made this project possible

---

## 📧 Contact & Support

### For Support:
- **GitHub Issues**: [Report bugs or request features](https://github.com/hardi2024/target-scoring-app-2025/issues)
- **Email**: hardiee15@gmail.com
- **Documentation**: User manual available upon request

### Contributing
Contributions, issues, and feature requests are welcome!

---

## 📄 License

**Free to Use**

This application is free to use, modify, and distribute for:
- ✅ Training purposes
- ✅ Educational purposes  
- ✅ Non-commercial use

**No Warranty:**
This software is provided "as is" without warranty of any kind.
Use at your own risk.

**Copyright © 2025 Hardianto**

---

## 🌟 Star History

If you find this project useful, please consider giving it a star ⭐

---

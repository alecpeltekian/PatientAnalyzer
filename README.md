# Medical PDF Analysis Dashboard

A professional web application for analyzing COGNISION medical reports with advanced clinical interpretation and beautiful visualization.

## 🌟 Features

- **PDF Upload & Analysis**: Drag-and-drop PDF upload with real-time processing
- **Clinical Interpretation**: Automatic analysis using established clinical ranges
- **Beautiful Dashboard**: Modern, responsive design with interactive metrics
- **Risk Assessment**: Color-coded risk levels (Normal, Borderline, High Risk, Critical)
- **Audiogram Analysis**: Comprehensive hearing threshold analysis
- **Export Results**: Download analysis results as CSV

## 🧠 Analyzed Metrics

### Core Clinical Features
- **Button Press Accuracy**: Attention and executive control assessment
- **False Alarms**: Inhibitory control evaluation  
- **Median Reaction Time**: Cognitive processing speed
- **P50 Amplitude**: Sensory gating mechanisms
- **P3b Amplitude & Latency**: Attentional resource allocation
- **Peak Alpha Frequency**: Cortical arousal and attention networks

### Audiogram Analysis
- Hearing threshold levels across frequencies (250Hz - 8kHz)
- Ear-to-ear asymmetry detection
- COGNISION test compatibility assessment
- Clinical hearing loss classification

## 🚀 Live Demo

Visit: [Your Render URL here]

## 💻 Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/medical-pdf-analyzer.git
cd medical-pdf-analyzer
```

2. Open `index.html` in your browser or serve with a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

## 📁 Project Structure

```
medical-pdf-analyzer/
├── index.html              # Main dashboard interface
├── medical_extractor.py     # Python backend code (reference)
├── README.md               # Project documentation
└── assets/                 # Additional assets (if needed)
```

## 🔧 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **PDF Processing**: PDF.js library
- **Styling**: Modern CSS with glassmorphism effects
- **Deployment**: Render static site hosting

## 📊 Clinical Ranges

The application uses established clinical reference ranges:

| Metric | Normal | Mild AD | Direction |
|--------|---------|---------|-----------|
| Button Press Accuracy | 94.1% | 82.2% | Lower risk |
| False Alarms | 1.1 | 4.9 | Higher risk |
| Median Reaction Time | 458ms | 499ms | Higher risk |
| P3b Amplitude | 6.03μV | 4.42μV | Lower risk |
| P3b Latency | 396ms | 419.6ms | Higher risk |
| Peak Alpha Frequency | 9.39Hz | 8.34Hz | Lower risk |

## 🎨 Features

### Visual Design
- Modern glassmorphism interface
- Responsive grid layout
- Color-coded risk assessment
- Smooth animations and transitions
- Professional medical theme

### Functionality
- Client-side PDF text extraction
- Real-time analysis and interpretation
- Interactive metric cards
- Clinical summary dashboard
- Error handling and validation

## 🔬 Clinical Interpretation

The dashboard provides automatic clinical interpretation based on:

- **Normal**: Values within healthy range
- **Borderline**: Values requiring monitoring
- **High Risk**: Values indicating potential cognitive decline
- **Critical**: Values requiring immediate retest (Peak Alpha <8Hz)

## 📱 Browser Support

- Chrome/Chromium 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🏥 Medical Disclaimer

This tool is for research and educational purposes only. Always consult qualified healthcare professionals for medical diagnosis and treatment decisions.

## 📞 Support

For issues or questions, please open a GitHub issue or contact [your-email@domain.com]

---

**Built with ❤️ for medical professionals and researchers**
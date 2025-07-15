# Medical PDF Analysis Dashboard - Full Stack

A professional web application with Python Flask API backend and beautiful HTML frontend for analyzing COGNISION medical reports.

## 🏗️ Architecture

**Backend (Python Flask API):**
- Uses your sophisticated `SimpleMedicalExtractor` class
- Handles PDF processing, text extraction, and clinical analysis
- RESTful API endpoints for analysis

**Frontend (HTML/CSS/JavaScript):**
- Beautiful glassmorphism design
- Drag & drop PDF upload
- Real-time analysis results display
- Responsive design for all devices

## 🌟 Features

- **Advanced PDF Analysis**: Uses your complete Python extraction logic
- **Clinical Interpretation**: Automatic analysis using established clinical ranges
- **Beautiful Dashboard**: Modern, responsive design with interactive metrics
- **Risk Assessment**: Color-coded risk levels (Normal, Borderline, High Risk, Critical)
- **Audiogram Analysis**: Comprehensive hearing threshold analysis with asymmetry detection
- **Study Findings**: Auto-generated clinical findings and discussion

## 📁 Project Structure

```
medical-pdf-analyzer/
├── app.py                   # Flask API server
├── medical_extractor.py     # Your medical extraction logic
├── index.html              # Frontend dashboard
├── requirements.txt        # Python dependencies
├── README.md              # Documentation
└── .gitignore             # Git ignore rules
```

## 🚀 Deployment on Render

### **Backend Setup (Web Service):**
1. **Service Type**: Web Service
2. **Language**: Python 3
3. **Build Command**: `pip install -r requirements.txt`
4. **Start Command**: `gunicorn app:app`
5. **Instance Type**: Free (512MB RAM)

### **Environment Variables:**
```
FLASK_ENV=production
PORT=10000
```

## 💻 Local Development

1. **Clone and setup:**
```bash
git clone https://github.com/yourusername/medical-pdf-analyzer.git
cd medical-pdf-analyzer
pip install -r requirements.txt
```

2. **Run locally:**
```bash
python app.py
```

3. **Access dashboard:**
```
http://localhost:5000
```

## 🔧 API Endpoints

- `GET /` - Main dashboard interface
- `POST /api/analyze` - Analyze PDF file
- `GET /api/health` - Health check
- `GET /api/clinical-ranges` - Get clinical reference ranges

## 📊 Analysis Features

### Core Clinical Metrics
- **Button Press Accuracy**: Attention and executive control
- **False Alarms**: Inhibitory control evaluation  
- **Median Reaction Time**: Cognitive processing speed
- **P50 Amplitude**: Sensory gating mechanisms
- **P3b Amplitude & Latency**: Attentional resource allocation
- **Peak Alpha Frequency**: Cortical arousal and attention networks

### Advanced Features
- **Audiogram Analysis**: Hearing threshold analysis across frequencies
- **Asymmetry Detection**: Ear-to-ear difference analysis
- **COGNISION Compatibility**: Test reliability assessment
- **Clinical Significance**: Auto-generated findings and discussion

## 🔬 Clinical Interpretation

The system provides automatic clinical interpretation based on:
- **Normal**: Values within healthy range
- **Borderline**: Values requiring monitoring  
- **High Risk**: Values indicating potential cognitive decline
- **Critical**: Values requiring immediate retest (e.g., Peak Alpha <8Hz)

## 🏥 Medical Disclaimer

This tool is for research and educational purposes only. Always consult qualified healthcare professionals for medical diagnosis and treatment decisions.

## 📞 Support

For issues or questions, please open a GitHub issue.

---

**Built with ❤️ for medical professionals and researchers**
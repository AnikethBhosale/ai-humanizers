# 🚀 Quick Start Guide - AI Text Humanizer Web UI

## Prerequisites
- Python 3.8 or higher
- pip package manager
- Internet connection (for first-time model downloads)

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/AnikethBhosale/ai-humanizers.git
cd ai-humanizers
```

### 2. Navigate to Web UI Directory
```bash
cd web_ui
```

### 3. Install Dependencies

**Option A: Using the setup script (Recommended)**
```bash
bash setup.sh
```

**Option B: Manual installation**
```bash
# Install Python packages
pip install -r requirements.txt

# Download spaCy model
python -m spacy download en_core_web_sm
```

### 4. Run the Application
```bash
streamlit run app.py
```

The app will automatically open in your browser at `http://localhost:8501`

## First Time Use

⚠️ **Important**: The first time you run the humanizer, it will download models and datasets. This may take 1-2 minutes. Subsequent runs will be much faster.

## Usage

1. **Select a Humanizer Type:**
   - 🟢 **Balanced**: Best for formal/professional content (80% transformation)
   - 🔴 **Aggressive**: Best for casual/creative content (95% transformation)

2. **Input Your Text:**
   - Paste directly into the text area
   - Upload a `.txt` file
   - Use a sample text

3. **Click "Humanize Text"**

4. **Review Results:**
   - Check transformation statistics
   - Download or copy the humanized text

## Troubleshooting

### "Module not found" errors
```bash
pip install -r requirements.txt
```

### "spaCy model not found"
```bash
python -m spacy download en_core_web_sm
```

### "Permission denied" on setup.sh
```bash
chmod +x setup.sh
bash setup.sh
```

### Port already in use
```bash
streamlit run app.py --server.port=8502
```

## Features

✅ Two humanization modes (Balanced & Aggressive)  
✅ Real-time statistics  
✅ File upload support  
✅ Download results  
✅ Sample texts for testing  
✅ Responsive design  
✅ Error handling  

## Performance Tips

- Shorter texts process faster
- Use Balanced mode for quicker results
- Models are loaded once and cached
- Internet needed only for first run

## Support

For issues or questions:
- Check the [README](README.md)
- Open an issue on GitHub
- Review the [CONTRIBUTING](../CONTRIBUTING.md) guide

---

**Made with ❤️ for Hacktoberfest 2025**

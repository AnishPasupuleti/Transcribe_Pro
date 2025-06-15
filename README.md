   
# Transcribe Pro 🎙️📝  
 
**Transcribe Pro** is a Flask-based web application that provides a simple interface for transcribing both audio and video files using Azure's Speech-to-Text API. It includes upload support, history tracking, and is deployable on cloud platforms for scalable use.    
  
## 🚀 Features    
        
- 🎧 Audio & 🎥 Video transcription support     
- 📂 Upload files (MP3, MP4, WAV)      
- 🧠 Uses Azure Speech-to-Text for accurate output   
- 📜 Displays transcription history for each session    
- 🧱 Lightweight and easy to deploy (Flask-based) 
 
## 🛠 Tech Stack

- **Python**
- **Flask**
- **Azure Speech SDK**
- **HTML/CSS (Jinja2)**
- **Bootstrap**

## 🧪 Setup Instructions

```bash
git clone https://github.com/AnishPasupuleti/Transcribe_Pro.git
cd Transcribe_Pro
pip install -r requirements.txt
python app.py
```

Visit `http://localhost:5000/` to start transcribing.

## 📁 File Structure

```
├── app.py                  # Flask backend
├── requirements.txt        # Python dependencies
├── static/                 # Static CSS/JS (if any)
├── templates/
│   ├── index.html          # Upload form
│   ├── result.html         # Transcription display
├── transcriptions.json     # History tracking
```

## 🔧 Azure Configuration

1. Set up a Speech resource at [Azure Portal](https://portal.azure.com)
2. Get the API key and region
3. Add to your code or .env:
   ```python
   speech_key = "your_key_here"
   service_region = "your_region_here"
   ```

## 🔮 Future Enhancements

- Support longer video/audio formats
- Add language switching for multilingual transcription
- Export as PDF or DOCX

## 📜 License

MIT License — feel free to adapt or deploy it for your own use.

---

> Built with care by [Anish Pasupuleti](https://github.com/AnishPasupuleti)

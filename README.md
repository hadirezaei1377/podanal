# podanal  
A powerful system for analyzing audio content that provides insights such as word count, key topics, sentiment analysis, and concise summaries of podcast conversations.  

---

## 📖 **Project Overview**  
**PodAnal** is an advanced tool designed to process and analyze podcasts and audio files, offering unique capabilities for users:  
- **Text Extraction from Audio:** Accurate conversion of audio files into text.  
- **Topic and Sentiment Analysis:** Identification of key topics and sentiment analysis in conversations.  
- **Automated Summarization:** Generate short, medium, or long summaries based on user needs.  
- **Advanced Search:** Quickly search and highlight keywords in the extracted text.  
- **Archive Storage:** Store audio files along with processed text for easy access.  

---

## 🎯 **Features and Capabilities**  
- **Text Extraction and NLP Analysis**  
- **Key Topics Identification**  
- **Sentiment Analysis**  
- **Interactive Dashboards:** Graphical representation of analysis results.  
- **Text Summarization:** Select summary length (short, medium, long).  
- **File Storage:** Save original and summarized text as files (e.g., TXT, HTML).  
- **Advanced Search:** Search keywords with highlighted results.  
- **Automatic Podcast Downloads from Online Sources**  
- **Archive Management:** Browse podcasts with search and filter options.  

---

## 🛠️ **Technologies and Tools**  
### Backend  
- **Programming Language:** Golang  
- **Dependency Management:** Go Modules  
- **Database:** PostgreSQL  
- **NLP Tools:** NLTK, spaCy  
- **Audio Processing:** FFmpeg, SpeechRecognition API  

### Frontend  
- **Framework:** React.js  
- **Charting Libraries:** Chart.js or D3.js for dashboards  

### DevOps  
- **Deployment:** Docker, Docker Compose  
- **Monitoring:** Prometheus, Grafana  
- **Web Server:** Nginx  
 

---

## 📥 **Installation and Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/hadirezaei1377/podanal.git
   cd podanal  
   ```  
2. Install Docker and run the project using Docker Compose:  
   ```bash
   docker-compose up --build  
   ```  
3. The service will be available at:  
   ```
   http://localhost:3000  
   ```  

---

## 📋 **How to Use**  
1. **Upload Audio Files:** Use the UI to upload an audio file.  
2. **Select Operation:**  
   - **Convert Audio to Text**  
   - **Automated Summarization**  
   - **Topic and Sentiment Analysis**  
3. **Download Results:** Download processed results as text or HTML files.  

---

## 🧪 **Testing and Validation**  
Run tests:  
```bash
go test ./...  
```  

---

## 👥 **Contributors**  
this project is open source and you can contribute, It makes me proud.
---

## 📜 **License**  
This project is licensed under the [MIT License](LICENSE).  




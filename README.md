<h1 align="center">The Lingual Lens Project</h1>

[![GitHub Issues](https://img.shields.io/badge/issues-0_open-orange)](https://github.com/meaviral17/LingualLens-Project/issues)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-green.svg)](https://github.com/meaviral17/LingualLens-Project)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Hits](https://hits.sh/github.com/meaviral17/hits.svg)](https://github.com/meaviral17/LingualLens-Project)

## Project Description

Lingual Lens tackles the prevalent challenge of language barriers in global communication. The project is a response to the existing problem where individuals from non-English-speaking communities face difficulties in understanding English content in documents and images. By providing a seamless solution for text recognition and translation, Lingual Lens transforms this challenge into an opportunity for inclusive communication. It innovatively leverages Azure technologies, creating a novel solution that transcends traditional language barriers. The project's goal is to bridge linguistic divides, empower marginalized communities, and foster a more connected and inclusive global society.

## Project Details
- [Project Demo URL(deployment link)](https://linguallens.azurewebsites.net/)
---

## Table of Contents
* [Tech Stack](#Tech-Stack)
* [Key Features](#Key-Features)
* [Explaination of Azure Services Used](#Explaination-of-Azure-Services-Used)
* [Clone and run this project](#Clone-and-run-this-project)
* [Steps to use LingualLens](#Steps-to-use-LingualLens)

---
## Tech Stack

- **Frontend:**
  - Streamlit (Python library for creating interactive web applications)
- **Backend:**
  - Azure App Service (Cloud-based platform for deploying and managing web applications)
- **OCR and Translation Services:**
  - Azure AI Document Intelligence (for detecting text from images and documents)
  - Azure AI Translator (for translating recognised text into multiple languages)
- **Development Environment:**
  - Visual Studio Code (Code editor for efficient development)
- **Cloud Management:**
  - Microsoft Azure Portal (for centralized management, configuration, and monitoring)
- **Programming Language:**
  - Python (utilized for backend development and integration with Streamlit)
- **Version Control:**
  - Git (for version control and collaborative development)
- **Dependency Management:**
  - Python Pip (for managing Python package dependencies)
---
## Key Features

1. **Multilingual Text Recognition:** Utilize cutting-edge OCR technology to accurately recognize text from images and documents in various formats, including JPEG, PNG, and PDF.
2. **Translation Diversity:** Seamlessly translate retrieved text into over 50+ languages, promoting inclusive communication for individuals in diverse communities.
3. **User-Friendly Interface:** Experience a smooth and intuitive interface designed for easy image uploads and document processing, ensuring accessibility for users of all technical backgrounds.
4. **Streamlined Deployment:** LinguaLens is deployed effortlessly with Azure App Service, providing a scalable and reliable platform for managing the web application.
5. **Azure Integration:** Leverage the power of Azure AI Document Intelligence and Azure AI Translator for robust text detection, translation, and seamless integration with the LinguaLens application.
6. **Global Collaboration:** Foster collaboration in a corporate setting by enabling smooth communication between colleagues who speak different languages.
7. **Educational Empowerment:** Empower individuals from marginalized communities with access to information in their native language, potentially opening doors to educational opportunities and knowledge.

---
## Clone and run this project
1. Clone this repository:
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```
2. Install the dependencies using pip command:
```bash
pip install -r requirements.txt
```
3. Run the Streamlit app script :
```bash
streamlit run main_script.py
```
---

## Steps to use LingualLens
1. Commence the process by initiating the upload of any image or PDF through the **Browse files** button.
![Commencement](Screenshots/s1.png)
---
-> The WebApp also contains a side menu offering various functionalities like Rerun, Record screencast, Print and Theme-related settings:

![image](https://github.com/meaviral17/LingualLens-Project/assets/81246801/bb38361d-16a6-4e50-85a5-66d400523739)

---
2. Following the selection of the file, the **Azure AI Document Intelligence** engages in processing, culminating in the presentation of the extracted text. Let's take the file given below as input.
![Text Extraction Process](Screenshots/sample.jpg)

---
3. Scrutinize the extracted text obtained from the provided image:
![Extracted Content](Screenshots/s2.png)

---
4. Proceed by navigating downwards to opt for the preferred language for translation.
5. Upon language selection, the **Azure AI Translator API** undertakes the translation process, showcasing the translated text underneath.
![Extracted Content](Screenshots/menu.png)

---
6. Observe the translated text in the chosen languages, illustrated here with Hindi, Tamil, Spanish, and Greek options:
---
**a. Spanish**
![Translation Outcome](Screenshots/spanish.png)

---
**b. Tamil**
![Translation Outcome](Screenshots/tamil.png)

---
**c. Hindi**
![Translation Outcome](Screenshots/hindi.png)

---
**d. Greek**
![Translation Outcome](Screenshots/greek.png)

---

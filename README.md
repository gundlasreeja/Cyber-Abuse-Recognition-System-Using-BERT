# [Cyber Abuse Recognition System Using BERT](Cyber-Abuse-Recognition-System-Using-BERT)

[![GitHub license](https://img.shields.io/github/license/gundlasreeja/Cyber-Abuse-Recognition-System-Using-BERT)](LICENSE)  [![GitHub issues](https://img.shields.io/github/issues/gundlasreeja/Cyber-Abuse-Recognition-System-Using-BERT)]()  [![GitHub contributors](https://img.shields.io/github/contributors/gundlasreeja/Cyber-Abuse-Recognition-System-Using-BERT)]()  [![GitHub last-commit](https://img.shields.io/github/last-commit/gundlasreeja/Cyber-Abuse-Recognition-System-Using-BERT)]()

Detect and prevent cyber abuse with the power of deep learning. The **Cyber Abuse Recognition System** uses the BERT model to identify harmful content in online communications and provide real-time moderation support.

---

## Table of Contents

- [About](#about)  
- [Limitations & Future Work](#limitations--future-work)  
- [Features](#features)  
- [Requirements](#requirements)  
- [Setup and Installation](#setup-and-installation)  
- [Usage](#usage)   
- [Screenshots](#screenshots)  
- [License](#license)  


---

## About

**Cyber abuse** includes harassment, trolling, impersonation, and other harmful behavior online. This project presents a detection system leveraging **BERT (Bidirectional Encoder Representations from Transformers)** to understand and classify text. It outperforms traditional models like Logistic Regression with higher accuracy and better contextual understanding.

- **Dataset**: Jigsaw Toxic Comment dataset  
- **Accuracy**: Improved from **93.5% (Logistic Regression)** to **96.5% (BERT)**  
- **Interface**: Web-based using **Flask (backend)**, **React (frontend)**, and **MySQL (database)**

---

## Limitations & Future Work

## Limitations

- Struggles with false positives/negatives  
- Heavy dependence on labeled data  
- Not real-time yet  
- Slower on large datasets with limited hardware

## Future Work

- Real-time detection  
- Integration with browser extensions  
- Enhanced UI/UX  
- Cross-platform deployment  
- Continuous learning from feedback  
- Integration with social media platforms  
- Stronger security & privacy protection

---

## Features

-  BERT-based deep learning model for text classification  
-  Preprocessing pipeline (lowercase, punctuation removal, stopwords)  
-  Flask backend with REST API  
-  React frontend  
-  MySQL database support  
-  Accuracy improvement from 93.5% to 96.5%

---

## Requirements

## Hardware

- CPU: Intel i3 or better  
- RAM: 8 GB or more  
- Storage: 500 GB or more  

## Software

- **Frontend**: React JS  
- **Backend**: Python 3.11  
- **Web Framework**: Flask  
- **Database**: MySQL  

## Python Libraries

```bash
transformers
pandas
scikit-learn
nltk
flask
flask_sqlalchemy
python-dotenv
```
## Setup and Installation
1. Clone the Repository
  ```
git clone https://github.com/gundlasreeja/Cyber-Abuse-Recognition-System-Using-BERT.git
cd Cyber-Abuse-Recognition-System-Using-BERT
```
2. Install Backend Requirements
```
pip install -r requirements.txt
```
3. Set Up Environment Variables
```
FLASK_APP=wsgi.py
FLASK_ENV=development
```
4. Run Flask Application
```
python wsgi.py
```
5. Run Frontend (if using React)
```
cd frontend
npm install
npm start
```
## Usage
Navigate to the web application.
Enter a sentence or comment into the input field.
Submit the text.
The system returns whether the input is abusive or not.

## Screenshots

**Login Page**
![Image](https://github.com/user-attachments/assets/b1580c48-e66f-4889-9c5c-7950eb9b9f0b)

**Register Page**
![Image](https://github.com/user-attachments/assets/6c176e3e-3a5f-4442-bc47-f048bd476797)

**Results Page1**
![Image](https://github.com/user-attachments/assets/3b45b130-0960-452f-b95c-40ea35670591)

![Image](https://github.com/user-attachments/assets/d5df795a-7828-4fea-bb36-024098d1fd9d)
**Results Page2**
![Image](https://github.com/user-attachments/assets/306cf51c-a518-4d94-8871-ebd1c960d4f1)

![Image](https://github.com/user-attachments/assets/351d302b-4794-417a-bce4-17758da7ef5e)

## License

This project is licensed under the [Apache License 2.0](LICENSE) - see the [LICENSE](LICENSE) file for details.

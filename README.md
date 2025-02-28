# Phishing URL Detection using Machine Learning

## Introduction
Phishing attacks are one of the most prevalent cybersecurity threats, tricking users into revealing sensitive information by imitating legitimate websites. This project leverages machine learning techniques to detect phishing URLs and prevent access to malicious sites.

The system includes a browser extension that analyzes URLs in real-time and blocks suspicious websites. It integrates machine learning (ML) and natural language processing (NLP) models for enhanced detection capabilities.

## Features
- **Real-time Phishing Detection:** Identifies and blocks malicious URLs.
- **Machine Learning & NLP-Based Analysis:** Uses advanced algorithms to classify websites as phishing or legitimate.
- **Browser Extension:** Provides seamless phishing protection while browsing.
- **Cloud-Based API:** Keeps the detection system updated with the latest threats.
- **User Feedback Mechanism:** Users can report false positives and negatives to improve accuracy.
- **Blocking Functionality:** Prevents access to detected phishing websites.

## Installation

### Prerequisites
Ensure you have Python installed along with the necessary dependencies.

### Steps to Run the Project
1. **Clone the repository:**
   ```bash
   git clone <repository-link>
   cd phishing-url-detection
   ```
2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the application:**
   ```bash
   python app.py
   ```

## Screenshots

## Introduction Page
<img width="504" alt="image" src="https://github.com/user-attachments/assets/1058d43a-ebc0-43c6-8d09-503955372b24" />

## Home Page
<img width="506" alt="image" src="https://github.com/user-attachments/assets/12cec1f0-c023-4fdf-88a9-b70bf9666a07" />
<img width="504" alt="image" src="https://github.com/user-attachments/assets/02931561-1263-4305-94b9-31491d858502" />
<img width="504" alt="image" src="https://github.com/user-attachments/assets/f45bd10a-e2f3-4d95-ba99-e2dfd2253c77" />
<img width="504" alt="image" src="https://github.com/user-attachments/assets/e6a30559-31c0-47bd-b52a-4b715e710ae7" />

## AboutPage
<img width="504" alt="image" src="https://github.com/user-attachments/assets/1d0f0424-63b7-4328-ba4e-2190364456ea" />

## Report url page
<img width="482" alt="image" src="https://github.com/user-attachments/assets/a6899cb1-5740-46fa-9342-f858d2f71020" />

## Login page
<img width="493" alt="image" src="https://github.com/user-attachments/assets/613f0f18-8a00-4543-924d-f3a1adcfbad8" />

## Signup page
<img width="504" alt="image" src="https://github.com/user-attachments/assets/0d49622f-f197-4733-bbba-443a7b22a238" />

### Running the Browser Extension
To use the browser extension, follow these steps:
1. Open Chrome and go to `chrome://extensions/`.
2. Enable **Developer Mode** (toggle switch on the top-right corner).
3. Click on **Load Unpacked** and select the `extension` folder from the project directory.
4. The extension will be loaded and ready to use.

<img width="504" alt="image" src="https://github.com/user-attachments/assets/d414c847-22b6-41b6-8594-523a2739536a" />

## Phishing Alert Page of Phishr-API
<img width="504" alt="image" src="https://github.com/user-attachments/assets/c14f4cb7-4fb2-41cf-ae62-2df4918a02eb" />

## Safe Website Notification of Phishr-API
<img width="504" alt="image" src="https://github.com/user-attachments/assets/bef6e8a5-bef7-4ee5-929c-8607243b03ce" />


## How It Works
1. **Data Collection:** Phishing and legitimate URLs are collected from trusted sources.
2. **Feature Extraction:** The ML model analyzes URL structure, domain features, and webpage content.
3. **Model Training:** Trained on a dataset using algorithms such as Random Forest and SVM.
4. **Real-Time Detection:** When a user visits a site, the system classifies it as safe or phishing.
5. **Blocking Mechanism:** If a phishing site is detected, access is blocked with a warning message.

## Technologies Used
- **Programming Language:** Python
- **Frameworks:** Flask, Scikit-Learn, TensorFlow
- **Frontend:** JavaScript (for browser extension)
- **Database:** SQLite (for user feedback and reports)

## Contact for Full Version
To access the full version of this project, contact:
- **Email:** omkarsatardekar4002@gmail.com
- **Phone:** +91 7276757607

## Future Enhancements
- **Mobile App Integration** for phishing detection on smartphones.
- **Email Security Module** to scan phishing emails.
- **AI-based Behavioral Analysis** to detect advanced phishing tactics.
- **Dark Web Monitoring** for proactive threat intelligence.

## Contributing
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request with your improvements.

## License
This project is open-source and licensed under [MIT License](LICENSE).


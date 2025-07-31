AI-vs-Human-Text-Detector
Overview
AI-vs-Human-Text-Detector is an open-source tool designed to distinguish between AI-generated and human-written text. Leveraging advanced Natural Language Processing (NLP) techniques and machine learning algorithms, this project aims to provide accurate classifications to ensure content authenticity.

Features
Text Classification: Determines whether a given text is AI-generated or human-written.

Machine Learning Models: Utilizes algorithms like Gradient Boosting for high-accuracy predictions.

NLP Feature Extraction: Analyzes various textual features such as word count, punctuation, and syntactic elements.

Web Interface: Offers a user-friendly interface built with Flask for easy interaction.

Extensibility: Modular design allows for easy integration of additional models or features.

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/AI-vs-Human-Text-Detector.git
cd AI-vs-Human-Text-Detector
Create a Virtual Environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the Flask Application:

bash
Copy
Edit
python app.py
Access the Web Interface:

Open your browser and navigate to http://localhost:5000.

Classify Text:

Enter the text you wish to analyze.

Click on the "Detect" button.

View the classification result indicating whether the text is AI-generated or human-written.

Methodology
The detection process involves:

Feature Extraction: Computing various textual features including:

Character and word counts

Punctuation usage

Part-of-speech tags (nouns, verbs, adjectives, etc.)

N-gram frequencies (bigrams, trigrams)

Readability scores

Model Training: Using labeled datasets to train machine learning models capable of distinguishing between AI and human text.

Prediction: Applying the trained model to new inputs to predict their origin.

Datasets
The model is trained on a combination of datasets comprising:

AI-generated texts from models like ChatGPT and GPT-4.

Human-written texts sourced from various domains to ensure diversity.

Evaluation Metrics
To assess the model's performance, the following metrics are used:

Accuracy: Proportion of correctly classified texts.

Precision: Correctly identified AI-generated texts among all identified as AI-generated.

Recall: Correctly identified AI-generated texts among all actual AI-generated texts.

F1-Score: Harmonic mean of precision and recall.

Contributing
Contributions are welcome! To contribute:

Fork the repository.

Create a new branch:

bash
Copy
Edit
git checkout -b feature/YourFeature
Make your changes and commit them:

bash
Copy
Edit
git commit -m "Add your feature"
Push to your forked repository:

bash
Copy
Edit
git push origin feature/YourFeature
Open a pull request detailing your changes.

License
This project is licensed under the MIT License.

Acknowledgements
Inspired by the advancements in AI text generation and the need for reliable detection mechanisms.

Utilizes open-source libraries and tools from the Python ecosystem.<img width="834" height="438" alt="gen ai " src="https://github.com/user-attachments/assets/10b0f018-1064-4e7e-8293-5ec73100c45e" />

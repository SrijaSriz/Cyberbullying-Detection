# 🛡️ NLP-Based Approach to Detect Cyberbullying in Social Media

This project is an NLP-based machine learning application designed to detect cyberbullying messages in social media text—specifically tweets. It performs sentiment analysis and classification using a Naive Bayes algorithm, with a clean interface built using Flask.

## 💡 Motivation

With the increasing prevalence of cyberbullying on social platforms, especially among adolescents, early detection is critical. This project focuses on identifying bullying messages using natural language processing techniques.

## 🚀 Features

- Text preprocessing: tokenization, stopword removal, lemmatization
- Sentiment polarity-based filtering
- Bullying vs. Non-Bullying classification
- Naive Bayes classifier implementation
- Web interface to upload and analyze datasets
- Visual insights (Histogram + Pie Chart)

- ## 🧠 Technologies Used

- **Python**
- **Flask** for web application
- **TextBlob** for sentiment analysis
- **NLTK** for lemmatization and preprocessing
- **Matplotlib** for visualizations
- **Pandas & NumPy** for data handling
- **Scikit-learn** for label encoding

## 📦 Dataset

- Twitter-based dataset containing labeled messages
- Contains Tweet text and sentiment labels
- Data preprocessing includes lemmatization, cleaning emojis and special characters

## 🗂️ Project Structure
project/ ├── app.py # Main Flask app
├── naiveb.py # Naive Bayes algorithm logic
├── templates/ # HTML templates
├── static/ # Plots (histogram, pie chart)
├── cleanprojectdataset.csv
├── combinedfile.csv # Final labeled dataset
├── output.csv # Bullying label results
├── wrongwords2.txt # List of bullying keywords

## 📊 Example Outputs

- **Positive / Negative / Neutral** messages
- **Histogram** of sentiment polarity
- **Pie Chart** of overall sentiment distribution

## 🧪 How to Run

1. **Clone the repo**
   
   git clone https://github.com/your-username/nlp-cyberbullying-detection
   cd nlp-cyberbullying-detection
   
2.  **Install dependencies**
    pip install -r requirements.txt

3.  **Run the app**
    python app.py
    
## 📉 Limitations

- Only supports text-based messages (no images/videos/audio)

- Works best with English language content

- Does not consider user metadata or post history

## 🔭 Future Enhancements

- Integration with real-time social media APIs

- Multilingual support

- Support for multimedia content

- Account blocking system for repeated bullying

## 📃 License

This project is licensed under the MIT License.

## 🙌 Acknowledgements

Kaggle datasets
TextBlob and NLTK
Inspired by IEEE research on cyberbullying detection

## 🔗 References

TextBlob Sentiment
Lemmatization Examples
Naive Bayes Classifier - Wiki  

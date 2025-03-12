# Sentiment Analysis App 🌟

Welcome to the Sentiment Analysis App! This project leverages a BERT-based model to predict the sentiment of a given sentence as Positive, Neutral, or Negative. The application is built using Streamlit, providing an intuitive and interactive user experience.

## 🎥 Demo

--> Videos and Screenshots

## 🚀 Features

  - Real-Time Sentiment Analysis: Enter any text and get instant sentiment predictions.
  - BERT-Based Model: Uses a fine-tuned BERT model for accurate sentiment classification.
  - Interactive UI: Built with Streamlit for a smooth and user-friendly experience.
  - Prediction History: Saves predictions with an ID and the corresponding sentiment.
  - Exportable Predictions: Predictions are saved in a JSON file for easy access and analysis.

## 🏗️ Project Structure

```
TEAM_PROJECT
├── src
│   ├── app.py                # Main Streamlit application
│   ├── inference.py          # Sentiment prediction logic
│   ├── model_training.py     # Model training script
│   ├── data_extraction.py    # Data extraction and cleaning functions
│   ├── data_processing.py    # Data preprocessing and transformation
│   ├── predictions           # Directory to store predictions
│   ├── predictions.json      # Saved prediction results in JSON format
│   └── reviews.csv           # Dataset for training/evaluation
├── tests
│   └── unit                  # Unit tests for different modules
├── .venv                     # Virtual environment
└── .gitignore                # Ignored files and folders
```

## 📝 Installation

1. Clone the repository:
   ```
   git clone https://github.com/username/sentiment-analysis-app.git
   cd sentiment-analysis-app
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv .venv
   source .venv/bin/activate
   # On Windows: .venv\Scripts\activate
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```
   streamlit run src/app.py
   ```

## 🧠 How It Works

1. The user inputs a sentence through the UI.
2. The sentence is processed by the BERT-based model to predict the sentiment.
3. The prediction and probabilities are displayed on the screen.
4. The result is saved in predictions.json for future reference.


## 📊 Example Results

<!-- screenshot of the app's output -->

## 📂 Saved Predictions

The predictions are stored in predictions.json in the following format:
```
{
    "1": ["I love this app!", "Positive"],
    "2": ["It is okay, not the best.", "Neutral"],
    "3": ["I hate waiting!", "Negative"]
}
```

## 🧪 Running Tests

Unit tests are located in the tests/unit directory. You can run them using:
```
pytest tests/unit
```

## 🙏 Credits

- Created with ❤️ by Axel & Asser.
- Built using Python, Streamlit, PyTorch, and Transformers.
- Model based on BERT from the Hugging Face library.

## 🌐 License

This project is licensed under the MIT License. See the LICENSE file for details.


## 💡 Future Improvements

  - Integrate more sentiment labels for fine-grained classification.
  - Add multi-language support.
  - Enhance model accuracy with fine-tuning on additional datasets.
  - Improve the UI with more visualizations and insights.

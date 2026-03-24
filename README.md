🎬 IMDB Movie Review Sentiment Analysis (RNN)
📌 Project Overview
This project focuses on building a Deep Learning model to classify movie review sentiments (Positive vs. Negative) using the IMDB Dataset. It demonstrates a complete NLP pipeline, from advanced text cleaning to building and training a Recurrent Neural Network (RNN) using PyTorch.

🚀 Key Performance Metrics
Accuracy: Achieved 85.89% on the test dataset.

Dataset Scale: Processed and cleaned 50,000 individual movie reviews.

Model Efficiency: Successfully reduced training loss to ~0.09 over 10 epochs.

🛠️ Technical Stack
Language: Python

Deep Learning Framework: PyTorch

NLP Tools: NLTK (Tokenization, Stopwords, PorterStemmer)

Data Science: Pandas, Scikit-learn (TfidfVectorizer, LabelEncoder)

💡 Implementation Workflow
Text Preprocessing: * Normalized text to lowercase.

Removed HTML tags, URLs, and punctuations using Regular Expressions (Regex).

Filtered English stopwords and applied Stemming to reduce words to their root form.

Feature Engineering:

Encoded sentiment labels (Positive/Negative) into binary format.

Vectorized text using TF-IDF with a 5,000-feature limit.

Deep Learning Pipeline:

Built a custom RNN architecture with a hidden layer size of 128.

Implemented a DataLoader system for efficient batch processing (Batch Size: 64).

Optimized the model using BCELoss and the Adam Optimizer.

📂 Project Structure
/notebooks: Contains the IMDB_rating_RNN.ipynb file with the full training loop.

/data: Information regarding the 50k record IMDB dataset.

README.md: Project summary and technical highlights.

📂 How to Run
Ensure the dataset file is in your local directory.

Install dependencies: pip install torch pandas nltk scikit-learn.

Run the Jupyter Notebook to train the model and evaluate results.

Contact: utkarshbachhav08@gmail.com | LinkedIn

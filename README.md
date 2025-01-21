### Sentiment Analysis with IMDB Reviews
This project is a Deep Learning-based Sentiment Analysis Application for IMDB movie reviews. It leverages a pre-trained Recurrent Neural Network (RNN) model to classify user-submitted reviews as positive or negative.

Features
Interactive Web Interface: Built with Streamlit to provide a user-friendly platform for text input and real-time sentiment classification.
Deep Learning Model: A pre-trained Simple RNN model using TensorFlow for robust and accurate predictions.
IMDB Dataset Integration: Utilizes the IMDB movie reviews dataset for tokenization and word index mapping.
Files
Prediction.ipynb: Notebook containing the training, evaluation, and saving of the Simple RNN model.
Sentiment Analysis - Deep Learning Project.ipynb: Detailed exploration of deep learning techniques used for sentiment analysis.
web_interface_streamlit.py: Streamlit application code for deploying the model as an interactive web tool.
How to Run
Clone the repository.
Install required dependencies (pip install -r requirements.txt).
Run the Streamlit app:
bash
Copy
Edit
streamlit run web_interface_streamlit.py
Enter a movie review in the text box and classify its sentiment.

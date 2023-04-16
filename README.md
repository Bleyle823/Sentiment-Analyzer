# Bleyle Sentiment Analyzer
This is a sentiment analysis tool that predicts the sentiment of a given review text as either positive or negative.
The sentiment analysis model used in this project is a Support Vector Machine (SVM) classifier, trained on a dataset of movie reviews. The model uses a Bag-of-Words approach to represent the review text as a vector of word frequencies, which is then used to predict the sentiment of the review.

# Usage
To use the Bleyle Sentiment Analyzer, simply enter a review text in the provided textbox and click the "Submit" button. The tool will then predict the sentiment of the review as either positive or negative.

# Dependencies
This project uses the following libraries:

gradio
scikit-learn
pandas

pip install gradio scikit-learn pandas
Launch
You can launch the Bleyle Sentiment Analyzer using the following command:

arduino
gradio run sentiment_analyzer.py
This will start a local server, and you can access the tool by opening the provided URL in your browser. You can also launch the tool on a public URL by setting the share=True argument when creating the Gradio interface.

# Credits
This project was created by [Bleyle Osewe].

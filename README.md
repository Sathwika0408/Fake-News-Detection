This project is a Fake News Detection System that uses Machine Learning and a simple desktop interface to help users determine whether a news article is real or fake. It is designed as a practical and easy-to-use tool that allows anyone to input a piece of news and instantly get a prediction based on a trained AI model. The project is ideal for learning Natural Language Processing (NLP), building end-to-end ML applications, and showcasing practical knowledge of real-world AI systems.

The main technologies used in this project are Python, Scikit-learn, and Tkinter. The model was trained using a dataset of real and fake news articles from Kaggle. The core model uses a Passive Aggressive Classifier combined with a TF-IDF vectorizer to analyze the textual data and classify it. The user interface is built using Tkinter and allows users to enter or paste any news content into a text box and receive a prediction instantly. It works completely offline and provides quick results.

The folder structure of the project includes two datasets (Fake.csv and True.csv), a training script (train\_fake\_news\_model.py), a GUI script (fake\_news\_gui\_ultimate.py). The training script combines and processes the datasets, trains the machine learning model, and saves it for future use. The GUI script loads the trained model and allows users to interact with the system in a friendly and intuitive way.

To run this project, you need to have Python installed along with libraries like pandas, scikit-learn, and joblib. First, you can run the training script to generate the model files if they are not already available. Then, you can simply run the GUI script, which opens a small desktop application. You enter a news article in the text area and click the Predict button to get the result — either REAL or FAKE.

This project demonstrates a strong understanding of text classification, machine learning workflows, and user-friendly application development. It is a great project for students, beginners in AI, or anyone looking to build a practical machine learning tool for their portfolio.

Due to GitHub’s file upload limits, if the dataset files are too large to upload directly, it is recommended to compress them into a zip file or provide an external link to the dataset source, such as Kaggle. The dataset used in this project can be found on Kaggle under the name "Fake and Real News Dataset."

This project was created by Sathwika Mateti, a B.Tech Computer Science Engineering student with an interest in Artificial Intelligence and real-world problem solving. It is open-source and intended for learning and portfolio development.


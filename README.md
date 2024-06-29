# Hotel Review Sentiment Analysis

## Project Overview
This project was part of an Intro to AI assignment where I performed sentiment analysis to predict hotel review ratings based on text data. The goal was to create and implement a machine learning model capable of accurately detecting ratings from review text.

## Technologies Used
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, NLTK, Scikit-learn
- **Models Implemented:** Linear Regression, Logistic Regression, SVM (Support Vector Machine)

## Project Details
1. **Data Preprocessing:**
   - Cleaned and prepared the text data by removing non-word characters, converting text to lowercase, tokenizing, and removing stop words.
   - Applied stemming and lemmatization to refine the text for analysis.
   - Utilized TfidfVectorizer to convert text into numerical features suitable for machine learning models.

2. **Model Development:**
   - Initially implemented a Logistic Regression model and explored the use of SVM.
   - Due to hardware restrictions and the large size of the dataset, a Linear Regression model was used to create a test model, achieving an accuracy of 62%. This demonstrated that the model was functioning correctly, even with a less suitable algorithm.
   - Estimated that with sufficient training time (20+ hours), the Logistic Regression model could achieve an accuracy of over 90%.

3. **Future Work:**
   - Discussed the potential for using Stochastic Gradient Descent (SGD) to improve model training efficiency and performance.

## Results
The project highlighted the challenges of working with large datasets and the importance of choosing appropriate machine learning models. Despite using Linear Regression, the test model showed promising results, indicating the potential for higher accuracy with more suitable algorithms and adequate training time.

## Conclusion
This project provided valuable hands-on experience in natural language processing (NLP) and machine learning, enhancing my skills in data preprocessing, model implementation, and performance evaluation. It also showcased my ability to adapt to technical challenges and explore alternative methods for improvement.

# Sentiment Analysis and Emotion Detection from Text

## Abstract
This project, titled **"Naïve Bayes and Logistic Regression for Sentiment Analysis and Emotion Detection from Text"** (Reviriego, A. and Raynova, R., 2024), was presented at the XXXIII International Scientific Conference Electronics (ET2024) on August 2, 2024. 

The paper presents a comprehensive approach to emotion detection using machine learning techniques by transforming text data into numerical vectors. The datasets were standardized into "Text" and "Label" columns, enabling the conversion of emotions into binary classifications. We selected Naïve Bayes and Logistic Regression models for this task, employing hyperparameter tuning through GridSearchCV and 5-fold cross-validation. 

- **Naïve Bayes**: Utilized hyperparameters such as alpha and fit_prior.
- **Logistic Regression**: Used hyperparameters C and solver.

Our results demonstrated that Logistic Regression exhibited robust performance, emphasizing the critical role of data preprocessing and hyperparameter tuning in enhancing model accuracy.

## Project Structure

### File Structure
- `Depression_Detection.ipynb`: Contains all the code used for the project.
- `documentation/`: This folder includes:
  - Project report
  - Presentation slides
  - Explanation video

### Datasets
Due to legal reasons, the datasets used in this project cannot be provided. However, the project is designed to be easily adaptable to similar datasets for those interested in reproducing the results.

## Technologies Used
The following languages and libraries were utilized in this project:
- **Python**: The primary programming language.
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **NLTK**: For natural language processing tasks.
- **Seaborn**: For data visualization.
- **Scikit-Learn**: For implementing machine learning algorithms.

## Getting Started
To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AdrianRevi/Depression-Detection.git
   
2. Navigate to the project directory:
   ```bash
   cd Depression-Detection

3. Open the jupyter notebook:
   ```bash
   jupyter notebook Depression_Detection.ipynb

## Conclusion

This project serves as a valuable resource for those interested in the fields of sentiment analysis and emotion detection. We hope that our findings and methodologies inspire further research and development in this area.

For any inquiries or further information, feel free to contact us at adrianreviriego@gmail.com.
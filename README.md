# Fake News Detection

## Overview
In this project, we learned how to detect fake news using Python. By utilizing a political dataset, we implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier, and fit our model. We achieved an accuracy of 92.82%.

## Getting Started

### Prerequisites
Ensure you have the following Python packages installed:
- `pandas`
- `scikit-learn`

You can install these packages using pip:
```sh
pip install pandas scikit-learn
```

### Data Acquisition
Obtain a political dataset containing both fake and real news articles. This dataset will be used to train and evaluate our model.

### Data Preparation
Using `pandas`, we'll load and preprocess the data to make it suitable for machine learning. This includes:
- Cleaning the text data
- Splitting the dataset into training and testing sets

### Model Training
We'll implement a TfidfVectorizer to convert text data into numerical form. Then, we'll initialize a PassiveAggressiveClassifier and fit our model to the training data.

### Model Evaluation
After training the model, we'll evaluate its performance on the testing set. Our model achieved an accuracy of 92.82%.

## Next Steps
- Experiment with different classifiers to improve accuracy.
- Use more advanced text preprocessing techniques.
- Implement cross-validation to further ensure the model's robustness.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Suggestions for enhancements are always welcome.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements
- The contributors to `pandas` and `scikit-learn` for their powerful tools.
- DataFlair for the project inspiration and guidance.

## Contact
For any questions or feedback, please reach out to me at [pranjaldhamane37@gmail.com].

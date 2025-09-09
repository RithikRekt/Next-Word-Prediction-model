This project is a Next Word Prediction system built using GPT-2 as the base model. The goal is to predict the most probable next word given a sequence of text. To make the system accessible, an interactive web interface has been developed using Streamlit, allowing users to type text and instantly receive predictions. The project also integrates scikit-learn for text preprocessing and evaluation.

The implementation relies on Python as the core programming language, with PyTorch and the Hugging Face Transformers library powering the GPT-2 model. Streamlit provides the front-end interface, while scikit-learn is used for preprocessing tasks and additional evaluation metrics. Together, these tools create a lightweight but powerful application for experimenting with natural language generation.

The repository includes an organized structure with files such as app.py for running the Streamlit interface, model.py for handling GPT-2 loading and prediction logic, and preprocessing.py for text cleaning and preparation. A requirements.txt file is provided to simplify installation, and notebooks are included for experiments and exploration.

To get started, clone the repository and create a virtual environment. After activating it, install the required dependencies using the provided requirements.txt. Once everything is set up, the application can be launched by running streamlit run app.py. This will open the app locally in your browser at http://localhost:8501.

For example, if you enter the text “The future of AI is”, the model might predict the next word as “bright”. This demonstrates how the system can generate meaningful continuations based on context.

The project requires Python 3.8 or higher along with PyTorch, Transformers, scikit-learn, and Streamlit. All of these are listed in the requirements file for easy setup.

Contributions are welcome, and pull requests can be submitted to add improvements or new features. The project is open-source and licensed under the MIT License, making it free to use and modify.

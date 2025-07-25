#**🚨 GBV Detection Model**
A deep learning model for classifying tweets into five categories of Gender-Based Violence (GBV): Sexual Violence, Emotional Violence, Harmful Traditional Practices, Physical Violence, and Economic Violence. This model was developed using data provided by the Zindi platform during a hackathon, designed for quick setup and deployment.

#**✨ Features**
**Multi-class Text Classification**: Identifies and categorizes GBV-related content across five distinct types.
**BERT-based**: Leverages the power of BERT for state-of-the-art text understanding.
**Easy to Use**: Minimal setup required for training and inference.
**Python-based**: Built with common deep learning libraries (Hugging Face Transformers, PyTorch).
**Ethical Focus**: Designed with responsible AI usage in mind.

#**📖 Usage**
##Training
Prepare your data in a CSV file with text (for the tweet content) and label (for the category, e.g., 0 for Sexual Violence, 1 for Emotional Violence, etc.) columns. Ensure your labels are encoded as integers from 0 to 4 corresponding to the five categories.
For detailed training steps and code, please refer to the train_model.py script or a dedicated Jupyter notebook in the repository.

##Prediction
To make predictions with a trained model, you will need to load the saved model and tokenizer, then pass your text input.
For detailed prediction steps and code, please refer to the predict_text.py script or a dedicated Jupyter notebook in the repository.

#**⚠️ Ethical Usage**
This model is a tool and should be used responsibly and ethically.
**Human Oversight**: Always ensure human review of model predictions, especially in sensitive contexts.
**Privacy**: Respect user privacy and data security when handling tweet data.
**Bias Awareness**: Be aware that models can reflect biases present in their training data. Continuous monitoring and fairness checks are crucial, especially with sensitive topics like GBV.
**Context is Key**: Automated classification should always be interpreted within the broader context of the tweet and user.
**Not for Surveillance**: Do not use this model for surveillance without explicit, informed consent.
If you or someone you know is experiencing GBV, please seek help from professional resources.

#**🙏 Acknowledgments**
Hugging Face Transformers library
PyTorch team
The [Zindi](https://zindi.africa) platform for providing the dataset for the hackathon.
The open-source community
[Daystar University](https://www.daystar.ac.ke) 

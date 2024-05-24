# End-to-End NLP Project with FastAPI and Hugging Face

This project implements an end-to-end Natural Language Processing (NLP) pipeline using FastAPI and Hugging Face transformers library. It consists of data ingestion, validation, transformation, model training, evaluation, and deployment stages.

## Project Overview:

- **Data Ingestion:** The pipeline begins by ingesting raw data using `DataIngestionTrainingPipeline`.
- **Data Validation:** Next, data is validated and cleaned using `DataValidationTrainingPipeline`.
- **Data Transformation:** Data is transformed and preprocessed for model training using `DataTransformationTrainingPipeline`.
- **Model Training:** The model is trained using Hugging Face transformers library with `ModelTrainerTrainingPipeline`.
- **Model Evaluation:** The trained model is evaluated for performance metrics using `ModelEvaluationTrainingPipeline`.
- **Model Deployment:** Finally, the model is deployed using FastAPI for real-time predictions.

## Usage Instructions:

1. **Run Stages:** Execute each stage of the pipeline in sequence by running the corresponding Python script.
2. **Access Endpoints:** Utilize the FastAPI endpoints for training (`/train`) and predictions (`/predict`).
3. **Customize Pipeline:** Customize each stage of the pipeline as per specific project requirements.

Refer to the code and inline comments for detailed instructions and customization options.

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. Update the conponents
6. Update the pipeline
7. Update the main.py
8. Update the app.py

## Requirements:

- Python 3.x
- FastAPI
- Hugging Face transformers
- uvicorn

---

## About:

This project demonstrates an end-to-end NLP pipeline implementation using FastAPI and Hugging Face transformers. From data preprocessing to model deployment, it offers a comprehensive solution for NLP tasks. Explore the capabilities and unleash the power of state-of-the-art NLP models with ease.

# Artificial Intelligence (CSC 1401) – Project 2

## Group Members & Model Assignments

| Student Name | Student ID | Assigned Model | Tasks |
| :--- | :--- | :--- | :--- |
| Eiman Alatwy | 451000436 | **General Model**: `Qwen/Qwen2.5-0.5B-Instruct` | Tasks 1 & 2 |
| Aseel Alshamlani | 451006284 | **General Model**: `Qwen/Qwen2.5-0.5B-Instruct` | Tasks 1 & 2 |
| Kholood Majrashi | 451009278 | **Code Model**: `Qwen/Qwen2.5-Coder-0.5B-Instruct` | Tasks 1 & 2 |

*Note: All group members collaborate on the following project components:*
- Environment Setup and Data Preparation.[span_0](start_span)[span_0](end_span)
- Task 3: Chat Interface.[span_1](start_span)[span_1](end_span)
- Final Project Presentation.[span_2](start_span)[span_2](end_span)

---

## Dataset Splits (CoNaLa Curated)

This project uses the curated version of the CoNaLa Dataset, obtained from Hugging Face[span_3](start_span)[span_3](end_span).

The training dataset was divided into 90% for training and 10% for validation using `seed=42` to ensure reproducibility[span_4](start_span)[span_4](end_span).

| Dataset Split | Number of Rows | Purpose |
| :--- | :--- | :--- |
| **Training Set** | **2,141** | Fine-tuning the models (Task 2)[span_5](start_span)[span_5](end_span) |
| **Validation Set** | **238** | Monitoring validation loss during fine-tuning (Task 2)[span_6](start_span)[span_6](end_span) |
| **Test Set** | **500** | Final model evaluation and performance metrics (Tasks 1 & 2)[span_7](start_span)[span_7](end_span) |

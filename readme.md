# Personalized Learning Platform with LLM Integration

- **Name**: Kshitij Joshi  
- **Program**: Masters in Data Science (AMS Dept.)  
- **Email**: kjoshi15@jhu.edu  

---

## **Project Overview**

This project aims to develop a **Personalized Learning Platform** that leverages state-of-the-art AI techniques to tailor educational content to each student’s individual needs. By analyzing student attributes like learning pace, performance, and interests, the platform will recommend personalized study plans and materials. Additionally, **Large Language Models (LLMs)** are fine-tuned to generate customized content and provide interactive explanations, making learning engaging and efficient.

---

## **Initial Plan**

The original approach involved a comprehensive design with the following components:
- **Transformer Models** to provide personalized study plans based on the user’s past performance and interests.
- **LLMs like GPT-4** to generate explanations of complex topics in a conversational manner.
- **Retrieval-Augmented Generation (RAG)** to integrate existing LLMs with a retrieval system for enhancing the contextual relevance of responses.
- **A Data Processing Pipeline** to analyze student performance and track progress.
- **A Backend API** to store learning records and deliver customized recommendations.
- **A Frontend Dashboard** for students to view personalized study materials and track their progress.

---

## **Revised Approach**

Due to **time and resource constraints**, several iterations and adjustments were made to the original plan:

1. **RAG Integration**:
   - Initially planned to integrate a Retrieval-Augmented Generation (RAG) pipeline with existing LLMs.
   - **Challenge**: Computational resources required for setting up a RAG pipeline were not feasible within the constraints.

2. **Direct API Integration**:
   - Considered using APIs for LLMs like GPT-4 for quick deployment of conversational explanations.
   - **Challenge**: Limited scope for showcasing advanced data science techniques.

3. **Transformer-Based Approach**:
   - Explored using pre-trained transformer models for fine-tuning on a domain-specific dataset (e.g., Coursera courses).
   - **Final Decision**: Fine-tune **GPT-2** on the Coursera dataset to demonstrate model training capabilities and personalized content generation.

---

## **Solution**

The final implementation focuses on:

- **Fine-Tuning GPT-2**:
  - The model is trained on the **Coursera Courses Dataset**, which includes fields such as course titles, descriptions, universities, difficulty levels, and skills.
  - Fine-tuning allows the model to provide domain-specific responses tailored to educational content.

- **Personalized Study Recommendations**:
  - Use student profiles to generate targeted study plans based on their learning performance and goals.

- **Key Features**:
  - **Customized Content**: Fine-tuned LLM generates course descriptions and study tips tailored to the dataset.
  - **Scalability**: The model architecture can be extended to include more educational datasets.
  - **Frontend Dashboard**: A Svelte-based dashboard is planned to provide an interactive interface for users.

---

## **Key Technologies**

- **Large Language Models (LLMs)**: GPT-2 is fine-tuned to generate educational content.
- **Dataset**: Coursera Courses Dataset (2021), which includes metadata and descriptions of various courses.
- **Hugging Face Transformers**: For fine-tuning the GPT-2 model.
- **Python**: Used for data preprocessing, model fine-tuning, and API integration.
- **Frontend**: Planned integration with Svelte for a user-friendly dashboard.

---

## **Future Scope**

While the current implementation is focused on fine-tuning, future iterations may include:

1. **RAG Integration**:
   - Incorporate a retrieval system for contextual knowledge augmentation.

2. **Multi-Language Support**:
   - Extend the platform to support additional languages by fine-tuning multilingual LLMs.

3. **Enhanced Personalization**:
   - Develop advanced clustering and recommendation algorithms to better tailor content to individual users.

---

**Contact Information**  
For further details or collaboration opportunities, please reach out to:  
- **Email**: kjoshi15@jhu.edu

# Amazon Bedrock LLM - Serverless event driven architecture

![Screenshot 2024-02-18 224709](https://github.com/ragerumal/AmazonBedrockLlmAudiotoSentiment/assets/126337647/903fb4b1-d257-49eb-ab2b-245febd339bc)

## Sentiment analysis of Voice recordings

# Serverless Sentiment Analysis System Design

Credit: [Learn.DeepLearning.AI](https://learn.deeplearning.ai/serverless-LLM-apps-amazon-bedrock)

This system design for serverless sentiment analysis is scalable and automatic. It caters to various use cases, including:

- Call center issue management for a product.
- Performing sentiment analysis on feature topics by Product Owner.
- Medical transcription of patient diagnosis and treatment plans from Doctor audio prescriptions.
- Product reviews analysis based on text or audio.

## Tools and Technologies Used

- **AWS Lambda (Python):** The compute layer helps invoke Bedrock/LLM.
- **S3 Storage:** Stores input media MP3 files and results in JSON format.
- **Amazon Transcribe:** Transfers audio to text format for conversations in MP3.
- **Amazon Bedrock:** Facilitates the connection to LLM to obtain the conversation summary.
- **Jinja2 LLM:** This model helps to return summaries based on the dictionary set for the summary response.





# Banking Customer Support Chatbot with Fine-Tuned Llama 2 model

This project fine-tunes a Llama 2 model to build a Banking Customer Support Chatbot that can answer common banking questions related to various banking scenarios. These scenarios include but are not limited to bank account information, credit card applications, loans, and account types.

## Project Steps

### 1. Define Model Purpose, Temperature, and Number of Examples
   - Clearly specify the purpose of the model.
   - Set the temperature (ranging from 0 to 1) to control the randomness of the model's responses.
   - Determine the number of examples needed for training and testing.

### 2. Generate Dataset from GPT-3.5 Turbo
   - Use GPT-3.5 Turbo to generate a comprehensive dataset of banking-related questions and answers.

### 3. Generate a System Message for the Model
   - Create a system message to guide the model on how to respond to user queries accurately and consistently.

### 4. Create a DataFrame with the Generated Data
   - Organize the generated data into a structured DataFrame for easy manipulation and processing.

### 5. Split Dataset into Train and Test
   - Divide the dataset into training and testing sets to evaluate the model's performance.

### 6. Save Train and Test Datasets to JSON Files
   - Save the training and testing datasets in JSON format for easy loading and processing.

### 7. Define Hyperparameters of the Llama 2 Model
   - Specify the hyperparameters required for fine-tuning the Llama 2 model, such as learning rate, batch size, and number of epochs.

### 8. Train the Model with the Custom Dataset
   - Fine-tune the Llama 2 model using the custom dataset to improve its performance on banking-related queries.

### 9. Hyperparameter Tuning to Optimize the Model
   - Perform hyperparameter tuning to find the optimal settings that maximize the model's accuracy and efficiency.

### 10. Inference
   - Use the fine-tuned model to ask questions and provide accurate responses to banking-related queries.


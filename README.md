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

## Project Results

| Epoch | Training Loss | Validation Loss |
|-------|---------------|-----------------|
|   0   |      2.7336   |      2.12169    |
|   1   |      1.9289   |      1.5676     |
|   2   |      1.3802   |      1.07865    |
|   3   |      0.9321   |      0.753138   |
|   4   |      0.6239   |      0.638141   |
|   5   |      0.4703   |      0.609385   |
|   6   |      0.4343   |      0.532492   |
|   7   |      0.3503   |      0.463649   |
|   8   |      0.2541   |      0.447891   |
|   9   |      0.2598   |      0.439263   |
|  10   |      0.2002   |      0.451156   |
|  11   |      0.1526   |      0.447681   |

### References
https://github.com/mshumer/gpt-llm-trainer
https://www.youtube.com/watch?v=VJkZFiuZrlw
https://www.youtube.com/watch?v=zcMQXID447sTask
  

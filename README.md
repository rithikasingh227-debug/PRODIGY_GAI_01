# PRODIGY_GAI_01
Text Generation using GPT-2 with Python and Transformers library.

🔹 **Code Description**

This project implements **text generation using a fine-tuned GPT-2 model**. The model is built using the **Transformers library by Hugging Face** and is trained on a custom dataset to generate contextually relevant text.

The workflow includes:

* Loading the pre-trained **GPT-2** model and tokenizer
* Preparing and encoding a custom text dataset
* Fine-tuning the model using the Trainer API
* Saving the trained model for future use
* Generating text based on user-defined prompts

The implementation demonstrates how generative AI models can be adapted to specific domains using fine-tuning techniques.

🔹 **Output / Results**

After fine-tuning, the model is able to generate more **coherent, structured, and domain-specific text** compared to the base GPT-2 model.

**Prompt:** Artificial Intelligence
**Generated Text:**
Artificial Intelligence is transforming industries by enabling automation, improving efficiency, and supporting data-driven decision making.

**Prompt:** Data Analytics
**Generated Text:**
Data analytics helps organizations identify patterns, optimize performance, and make informed strategic decisions.

 **Before vs After Fine-Tuning**

| Before Fine-Tuning      | After Fine-Tuning                   |
| ----------------------- | ----------------------------------- |
| Generic and random text | Structured and domain-specific text |
| Less coherence          | Improved contextual relevance       |
| No specific style       | Learns dataset style                |

 **Conclusion**

The fine-tuned GPT-2 model successfully adapts to the custom dataset and generates meaningful text aligned with the training data. This demonstrates the effectiveness of **Generative AI and model fine-tuning** in real-world applications.


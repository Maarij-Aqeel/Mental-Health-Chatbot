# Mental Health Support Chatbot – Fine-Tuned GPT-Neo 2.7B

## Task Objective (X)

I developed an **AI-powered Mental Health Support Chatbot** designed to engage in empathetic, supportive, and non-judgmental conversations with individuals facing emotional stress, anxiety, or loneliness. The primary goal was to fine-tune a large language model on emotionally rich dialogues to deliver **compassionate and context-aware responses** in real time.

---

## How I Measured Success (Y)

- Improved **empathy score** and **response relevance** across multiple test cases  
- Achieved significant alignment with **emotional tone** and **contextual flow**  
- Positive evaluation through **manual testing** and **sample interaction audits**  
- Demonstrated potential for **peer-level emotional support**, not clinical diagnosis  

---

## How I Built It (Z)

### Dataset Used

- **EmpatheticDialogues** – Facebook AI Research  
  - Approximately 25,000 human-to-human conversations grounded in emotional scenarios  
  - Annotated with emotion labels and designed to encourage empathetic, context-aware responses  
  - Suitable for emotion recognition, dialogue generation, and compassion-oriented training tasks  

---

### Model Applied

- **Base Model**: [`EleutherAI/gpt-neo-2.7B`](https://huggingface.co/EleutherAI/gpt-neo-2.7B)  
- **Fine-tuned Model**: [`Maarij-Aqeel/Mental_Health_chatbot`](https://huggingface.co/Maarij-Aqeel/Mental_Health_chatbot)  
- **Fine-tuning Technique**: LoRA (Low-Rank Adaptation) for efficient training  
- **Frameworks Used**:
  - Hugging Face Transformers and Datasets  
  - PEFT (Parameter-Efficient Fine-Tuning)  
  - PyTorch + Accelerate for performance optimization  

---

### Key Results and Findings

- **Improved emotional alignment** across varied emotional states (e.g., sadness, loneliness, frustration)  
- **Reduced generic responses** compared to the base GPT-Neo model  
- **Contextually rich and coherent multi-turn conversations** maintained over several exchanges  
- Custom safeguards added to promote **safe and responsible conversation handling**

---

## Use Cases

- AI support assistant in **mental wellness platforms**  
- **Anonymous chat services** offering emotionally intelligent companionship  
- Tool for **training conversational AI models** in empathy-oriented dialogue tasks  

---

## Technical Stack

- **Model Architecture**: GPT-Neo 2.7B  
- **Training**: PyTorch + Hugging Face Trainer API  
- **Fine-tuning**: LoRA-based efficient adaptation  
- **Evaluation**: Manual review, test prompt scenarios, and quality scoring  
- **Dataset**: EmpatheticDialogues (Facebook AI)

---

## Future Work

- Integrate an **emotion detection classifier** to guide responses in real time  
- Extend training with **multilingual emotion-rich dialogues**  
- Add **voice-based interface** using Vapi or similar tools  
- Deploy using **FastAPI** for backend inference and **Streamlit or Next.js** for the UI demo  

---

## Model Access

You can explore and use the model here:  
**[Maarij-Aqeel/Mental_Health_chatbot on Hugging Face](https://huggingface.co/Maarij-Aqeel/Mental_Health_chatbot)**

---

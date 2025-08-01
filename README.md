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

- **EmpatheticDialogues (Facebook AI Research)**
  - Contains ~25k human-to-human conversations grounded in emotional situations
  - Annotated with emotion labels and designed to encourage empathy
  - Ideal for tasks focused on **emotion recognition** and **empathetic response generation**

---

### Model Applied

- **Base Model**: `EleutherAI/gpt-neo-2.7B`
- **Fine-tuning Approach**: Parameter-efficient fine-tuning using **LoRA (Low-Rank Adaptation)**
- **Frameworks**: 
  - Hugging Face Transformers
  - PEFT (Parameter-Efficient Fine-Tuning) Library

---

### Key Results and Findings

- The fine-tuned model:
  - Exhibited **significantly improved emotional alignment**
  - Maintained **response coherence** over multiple turns
  - Adapted tone dynamically based on user input (e.g., sadness vs frustration)
- Observed reduction in **generic responses** compared to base GPT-Neo
- Safe and supportive language maintained across interactions with custom safeguards

---

## Use Cases

- Emotional support for students, remote workers, and isolated individuals
- Integration into **mental wellness apps** or **anonymous chat platforms**
- Can act as a **first line of empathetic conversation** before human referral

---

## Technical Stack

- **Model**: GPT-Neo 2.7B (EleutherAI)
- **Training**: PyTorch + Hugging Face Trainer API
- **Fine-tuning method**: LoRA
- **Dataset**: EmpatheticDialogues (Facebook AI)
- **Evaluation**: Custom scripts + manual review

---

## Future Work

- Add **emotion classification module** to better steer responses
- Expand dataset with **multilingual dialogues**
- Integrate **voice-based interaction** for more natural user experience
- Deployment via **FastAPI or Streamlit** for demo interface

---


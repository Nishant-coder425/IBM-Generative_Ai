# 📰 Fake News Generator and Detector using Generative AI and NLP

This project implements a **Fake News Generator and Detector** using state-of-the-art NLP models: **GPT-2** for generating fake news headlines and **BERT** for detecting whether a given news headline is fake or real. A simple and interactive **Gradio** interface is provided for easy access to both functionalities.

---

## 🚀 Features

- **Fake News Generator**:
  - Uses the GPT-2 model from Hugging Face.
  - Input: A topic (e.g., `Generate Fake news on <topic>`).
  - Output: generated fake news headlines based on the input topic.

- **Fake News Detector**:
  - Uses a fine-tuned BERT model (`jy46604790/Fake-News-Bert-Detect`).
  - Input: Any news text.
  - Output: Classification result: `"Fake News"` or `"Not A Fake News"`.

- **Gradio Web Interface**:
  - A web-based UI to test both functionalities interactively.
  - Users can switch between the Generator and Detector tabs.

---

## 📁 Dataset Used

- **True News** and **Fake News** samples were used for model training.
- BERT model (`jy46604790/Fake-News-Bert-Detect`) was fine-tuned on publicly available datasets like:
  - Fake and real news dataset from Kaggle
  - LIAR dataset (optional depending on training)

---

## 🧠 Models Used

| Task        | Model                                   | Source               |
|-------------|------------------------------------------|----------------------|
| Generation  | GPT-2 (`gpt2`)                          | Hugging Face         |
| Detection   | BERT (`jy46604790/Fake-News-Bert-Detect`)| Hugging Face         |

---

## 🛠 Installation

1. Install required dependencies:

```bash
pip install transformers torch gradio

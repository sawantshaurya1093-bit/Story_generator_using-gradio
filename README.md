# 🤖 Creative AI Story Generator (GPT-2 & Gradio)

### **A small generative AI project demonstrating text completion and interactive web deployment.**

This project allows users to input a custom story prompt and generate a creative text continuation using a pre-trained Large Language Model (LLM). The application is hosted publicly using Gradio and Hugging Face Spaces for a permanent, shareable demo link.


## ✨ Features

* **Text Generation:** Uses the powerful **GPT-2** (Generative Pre-trained Transformer 2) model from Hugging Face Transformers.
* **Interactive UI:** Built with **Gradio**, allowing users to easily interact with the model via a simple web interface.
* **Parameter Control:** Control the output with custom settings for:
    * **Prompt:** The story starter text.
    * **Max Length:** Limits the length of the generated story.
    * **Temperature:** Controls the randomness/creativity of the output (higher = more creative).
* **Minimal Dependencies:** Requires only standard Python libraries and Hugging Face ecosystem tools.

---

## ⚙️ Getting Started (Local Setup)

Follow these instructions if you want to run the application locally on your machine.

### Prerequisites

You need **Python 3.8+** installed.

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Your-Username]/[Your-Repo-Name].git
    cd [Your-Repo-Name]
    ```

2.  **Install Dependencies:**
    All required libraries are listed in `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

### Usage

Run the main application file from your terminal:

```bash
python app.py

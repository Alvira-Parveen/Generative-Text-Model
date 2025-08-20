## 📝 Generative Text Model

This project demonstrates text generation using two approaches :
- 🤖 GPT-2 – A pre-trained transformer model from Hugging Face capable of generating coherent paragraphs based on a given prompt.
- 🧠 Word-level LSTM – A custom Long Short-Term Memory neural network trained on a small dataset to generate text word by word.

This notebook highlights the differences between state-of-the-art transformer models and custom sequence models, and it’s lightweight and easy to run. 🚀

---

## ✨ Features 

- Generate coherent paragraphs with GPT-2.
- Generate demo text using a small LSTM model.
- Temperature-based sampling for LSTM to reduce repetition and increase creativity. 🔥
- Fully documented notebook with Markdown explanations. 📄
- Ready-to-run on Mac M1 using PyTorch GPU (MPS) acceleration. 🍏

--- 

## ⚡ Installation & Setup

1. Clone the repository :

git clone <your-repo-link>
cd "Generative Text Model"

2. Create a virtual environment and activate it :

python3 -m venv venv
source venv/bin/activate

3. Install required packages :

pip install -r requirements.txt

4. Launch the notebook :

jupyter notebook

--- 


## 🚀 Usage

1) Open Generative_Text_Model.ipynb.

2) Run Cell 1 – Basic Imports and Setup
                Import PyTorch, TensorFlow, Transformers, NumPy.
                Initialize the GPT-2 pipeline.

3) Run Cell 2 – GPT-2 Text Generation : provide your prompt and generate multiple paragraphs using GPT-2.

4) Run Cell 3 – LSTM Text Generation : Train a small LSTM model on a sample text.
                        Use word-level tokenization and temperature-based sampling.
                        Generate new text based on a seed phrase.

---


## 📦 Dependencies 

Python 3.12+ 🐍

torch==2.8.0

transformers==4.55.2

tensorflow-macos==2.16.1

tf-keras==2.19.0

numpy

---


## 🎯 Key Takeaways

- GPT-2 produces coherent, paragraph-level text effortlessly.
- LSTM demonstrates how custom models learn from small datasets.
- Temperature sampling improves variety in generated text. ✨
- A perfect demo of generative AI for education or content creation. 📚

---


## ⚠️ Notes & Warnings
- LSTM generates text word by word; results may be less coherent on small datasets.
- GPT-2 outputs are probabilistic; same prompt can produce different text.
- For LSTM, temperature affects creativity: higher → more diverse, lower → more predictable.
- Ensure your environment meets Python 3.12+ and required packages to avoid errors.

---


## 👩‍💻 Author

**Name**  : ALVIRA PARVEEN  
🔗 [LinkedIn](https://www.linkedin.com/in/alvira-parveen-78022536b)  
🌐 [GitHub](https://github.com/Alvira-Parveen)

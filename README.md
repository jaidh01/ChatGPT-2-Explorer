# ChatGPT-2-Explorer

### Overview
**ChatGPT-2-Explorer** is a conversational AI project built on the GPT-2 architecture. This repository provides tools and code for training, testing, and exploring a chatbot to understand GPT-2 architecture, designed to demonstrate conversational capabilities on custom datasets. The model is fine-tuned on conversational data to deliver interactive responses.

### Features
- **Custom Dataset Training**: Uses provided datasets for chatbot training.
- **Interactive Chatbot Interface**: Enables conversation with the trained model.
- **GPT-2 Customization**: Easily modify parameters for experimentation.

### Files
- **`trainig.py`**: Code for fine-tuning GPT-2 on the dataset.
- **`chatbot.py`**: Script to initialize and interact with the trained chatbot.
- **`torch examples.ipynb`**: Examples for PyTorch usage in the project.
- **`vocab.txt`**: Vocabulary file used for model tokenization.
- **`wizard_of_oz.txt`**: Sample conversational dataset.

### Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jaidh01/ChatGPT-2-Explorer.git
   ```
2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Train the Model**:
   ```bash
   python trainig.py
   ```
4. **Run the Chatbot**:
   ```bash
   python chatbot.py
   ```

### Requirements
- Python 3.8+
- PyTorch
- Transformers library

### Example Usage
After running `chatbot.py`, you can engage with the model directly via the terminal, exploring the chatbot's responses.

### Future Plans
- Integrate a web-based UI for a more interactive experience.
- Add support for larger datasets.

### Contributions
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

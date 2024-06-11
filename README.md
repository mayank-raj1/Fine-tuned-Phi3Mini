## Fine-tuned Microsoft Phi-3 Mini (3b) with DPO for Informative Text Generation

This repository contains the code for fine-tuning the Microsoft Phi-3 Mini (3b) base model using Direct Preference Optimization (DPO) to generate more informative and concise responses.

###  Key Points

- **Focus:** Informative and concise text generation
- **Fine-tuned from:** Microsoft Phi-3 Mini (3b)
- **Training data:** Intel/orca_dpo_pairs dataset
- **Benefits:**
    - Reduced number of tokens required for instructions (improved efficiency)
    - More informative responses compared to out-of-the-box LLMs

### Getting Started

**1. Visit Hugging Face:**

Access the model card and full details on Hugging Face: [Link to the model card on Hugging Face](https://huggingface.co/MayankRaj/MayankDPOPhi-3-Mini)

**2. Explore the Notebook:**

This repository includes the Google Colab notebook used for fine-tuning: [Link to Google Colab notebook](https://github.com/mayank-raj1/Fine-tuned-Phi3Mini/blob/main/FineTune_Phi.ipynb)

**3. Explore the Results:**

Detailed results of the fine-tuning process, including metrics and evaluation, are available here: [Link to results](https://github.com/mayank-raj1/Fine-tuned-Phi3Mini/blob/main/Fine%20tuning%20Report%20Weights%20%26%20Biases.pdf)

Here is a brief overview of results:
![Main Results](https://raw.githubusercontent.com/mayank-raj1/Fine-tuned-Phi3Mini/main/MainResult.png)

### Additional Information

- **Dataset:** The model was fine-tuned on the Intel/orca_dpo_pairs dataset, containing text prompts and corresponding informative response pairs.
- **DPO Approach:** Direct Preference Optimization (DPO) helps the model adapt to the expected format of responses, leading to more efficient inference.

**Please note:** This repository serves as a starting point for exploring the fine-tuned model. For in-depth details and usage instructions, refer to the provided links.

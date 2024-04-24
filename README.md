# Text-Summarization-Using-Transformers

Introduction – 
The task of news summarization aims to distil lengthy documents into concise headlines without losing the essence of the document. With the exponential growth of online text data, automated text summarization has become quite crucial. Recognizing this need, our project has tried to address the challenge of automatic summarization using a custom-built transformer architecture. Leveraging the foundational components of encoders, decoders, multi-head attention layers, and masking techniques, we have crafted a solution that sifts through complex texts, extracting key points, and presenting them concisely in headline form.

Methodology - 
Our project’s follows the methodology of building transformer based on the famous “Attention is all you need” published in 2017.
1)	Data Collection and Preprocessing:
•	Gather a dataset of documents paired with their corresponding headline summaries.
•	Preprocess the data by tokenizing the documents and headlines, converting them into numerical sequences, and applying any necessary text cleaning techniques.
•	Split the dataset into training and testing sets to evaluate the model's performance.
2)	Model Architecture:
•	Implement the transformer architecture described in the "Attention is All You Need" paper, including the encoder and decoder components.
•	Construct the encoder using self-attention layers, position-wise feedforward networks, and layer normalization.
•	Design the decoder with similar components, augmented with masked multi-headed attention layers to prevent the model from attending to future tokens during training.
3)	Training Procedure:
•	Initialize the parameters of the transformer model randomly or with pre-trained embeddings.
• GloVe 6B 50D is a pre-trained word embedding model trained on a corpus of 6 billion tokens with a vocabulary size of 400,000. It represents words as 50-dimensional vectors, capturing semantic relationships and contextual information for natural language processing tasks.
•	Utilize optimization techniques i.e. Adam optimizer with a custom learning rate to minimize the loss function, which could be a suitable loss function for sequence generation tasks like document summarization, such as cross-entropy loss.
 
![diagram](https://github.com/Shadow-1622/Text-Summarization-Using-Transformers/assets/64398826/6b49b023-6bcf-4150-9088-2f95ca3416f9)


References – 
“ Attention is all you need to “ : (Ashish Vaswani, 2017)

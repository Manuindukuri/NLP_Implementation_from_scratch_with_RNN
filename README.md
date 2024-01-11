# A Deep Dive into NLP with Recurrent Neural Networks
This project embarks on an ambitious journey to explore the depths of Natural Language Processing (NLP) through the lens of Recurrent Neural Networks (RNNs). It stands at the intersection of linguistic creativity and the precision of machine learning, aiming to push the boundaries of what's achievable with current NLP methodologies. By delving into the intricacies of language modeling, the project attempts to build models that not only mimic human language but also understand its nuances to a certain degree.

![NLP](https://github.com/Manuindukuri/NLP_from_scratch_with_RNN/assets/114769115/81443c3a-380d-4f90-9ecd-14598643b172)

# Objectives
**1. Enhancing a Shakespearean Sonnet Generator:** To develop a model that can generate text in the style of Shakespeare, going beyond predicting sentence endings to include generating coherent subsequent words.

**2. Creating a Non-English Language Corpus:** To showcase the versatility and adaptability of NLP techniques across languages, this part of the project focuses on developing a corpus in a language other than English.

**3. RNN for Addition:** This objective shifts the focus to a more structured task, using RNNs for the numerical task of addition, treating it as a sequence-to-sequence learning problem.

**4. Dense Network for Number Addition**: In contrast to the RNN, a dense network is employed here to perform the same addition task, allowing for a comparison between the two types of neural networks.

**5. Theoretical Exploration:** An essential part of the project is a detailed exploration of the theoretical differences between dense networks and recurrent networks, providing a deep understanding of their respective architectures and applications.

# Methodology and Implementation

### 1. Finishing Shakespeare

This section is a testament to the project's creative prowess. By training a model on Shakespearean text, the goal is to create a generator capable of producing text that resembles the literary style of Shakespeare.

**Data Preprocessing**

- The corpus comprised Shakespeare's sonnets.
- Preprocessing steps included tokenization, normalization of text, and conversion of words into numerical representations suitable for RNN training.
   
**Model Building**

- The RNN architecture was chosen for its ability to handle sequential data and its effectiveness in capturing the temporal dependencies characteristic of human language.
- The model comprised LSTM (Long Short-Term Memory) units, known for their ability to remember information over extended time intervals.
  
**Training and Challenges**

- The model was trained to predict the next word in a sequence, given a sequence of words.
- One of the main challenges was to balance the creativity of the model with linguistic coherence.

## 2. Non-English Language Corpus
   
**Corpus Development**

- A non-English language was chosen to demonstrate the universality of NLP techniques.
- Corpus collection involved gathering authentic text sources, ensuring a wide range of vocabulary and sentence structures.

**Adaptation to a New Language**

- Significant effort was dedicated to adapting existing NLP preprocessing techniques to accommodate the linguistic peculiarities of the chosen language.
- Challenges included handling unique characters, different syntactic structures, and potential lack of NLP resources in the chosen language.

## 4. RNN for Addition

**Model Architecture**

- The model was structured to treat addition as a sequence-to-sequence learning problem.
- Each digit and operation symbol was one-hot encoded to serve as input to the RNN.

**Training and Evaluation**

- The model's performance was evaluated based on its accuracy in performing addition on a set of test examples.
- This part of the project showcased the flexibility of RNNs in learning structured, non-linguistic tasks.

## 5. Dense Network for Number Addition
   
**Comparing to RNN**

- A dense neural network was implemented for the same addition task.
- The project then engaged in a comparative study of the performance of the dense network versus the RNN, providing valuable insights into the strengths and limitations of each architecture.
  
## 6. Theoretical Insights

**Dense vs Recurrent Networks**

- This section provided a deep dive into the theoretical underpinnings of dense and recurrent networks.
- The project elucidated the fundamental differences in architecture, data handling, and application scenarios for each type of network.



# 🎶 Song Lyric Generation with NLP Models

Overview:

This project focuses on generating song lyrics using advanced Natural Language Processing (NLP) techniques. The primary objective was to implement and compare the performance of three different models: Naive Bayes N-Gram, Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM), and GPT-2 Transformers. The dataset used for this task consisted of Taylor Swift’s song lyrics, offering a rich collection of text data that enabled the training of models capable of generating creative and coherent lyrics. 

The project implemented a Naive Bayes N-Gram model, a simple probabilistic approach that generates sequences of words based on their frequency and co-occurrence in the text. Although this model is computationally efficient, it struggled with long-term dependencies in the text, resulting in higher perplexity scores (~200). We also used a more sophisticated RNN-LSTM model, which is known for its ability to handle sequential data and long-term dependencies. This model achieved a 96.16% accuracy after being trained for 20 epochs. Lastly, the GPT-2 Transformer model, which uses a self-attention mechanism to capture relationships between words over long distances, outperformed the other models. With 1.5 billion parameters, GPT-2 generated high-quality, human-like lyrics, maintaining rhyme schemes like “aabb” and “abab” and showcasing the power of modern transformers in text generation.

The dataset used for this project was sourced from Kaggle and HuggingFace, containing 762 songs and 35,250 words. The dataset included song titles, albums, and lyrics, structured in a way that allowed the models to learn the natural flow of song structures such as verses, choruses, and bridges. Various preprocessing techniques were applied, including tokenization, stop-word removal, and lemmatization, to prepare the text for training. Each model was evaluated using different metrics: the RNN-LSTM model’s accuracy was recorded at 96.16%, the N-Gram model had an average perplexity score of 200, and the GPT-2 model was assessed using ROUGE scores, which reflected its ability to produce fluent and coherent lyrics.

Overall, the GPT-2 Transformer model demonstrated the best performance, generating the most coherent and contextually correct lyrics. However, the RNN-LSTM model performed well in generating grammatically accurate sentences, although it sometimes struggled to maintain rhyming patterns. The Naive Bayes N-Gram model was effective in maintaining rhymes but had difficulty with long-term context due to its limited scope and reliance on word frequency.




# w266 Final Project: Diplomatic Lie Detector

## Overview
"Diplomatic Lie Detector" is a groundbreaking research project focused on enhancing the detection of deception in online text communications, particularly in the strategic game of Diplomacy. Our work builds upon the foundational research by Peskov et al., exploring advanced neural network architectures and diverse tokenization strategies.

## Key Features
- **Advanced Model Architecture**: Combination of a Bidirectional Long Short-Term Memory (Bi-LSTM) network with a Convolutional Neural Network (CNN).
- **Unigram Tokenization**: Employed for its superiority in handling the variability and richness of natural language, crucial for identifying deceptive communication.
- **Enhanced Performance**: Our model outperforms traditional models and sets a new benchmark in deception detection.

## Research Highlights
- **Exploration of Tokenization Methods**: We delved beyond standard Keras tokenizer, investigating Byte Pair Encoding (BPE), Unigram tokenization, and SpaCy linguistic tags.
- **Critical Analysis of BERT**: Informed by Peskov et al.'s findings, we scrutinized BERT’s limitations in the context of written deception, leading us to alternative methods.
- **Innovative Use of Neural Networks**: We experimented with different RNN configurations including GRUs, Bi-LSTM, and CNN layers, concluding that Bi-LSTM with CNN offers the best results.

## Achievements
- **Deception Detection in Diplomacy**: Our model adeptly identifies 'lie' messages, a vital aspect in the game of Diplomacy.
- **Surpassing Human Benchmark**: Achieved a macro F1 score of 0.595 and a lie F1 score of 0.273, surpassing human-level performance in lie detection.
- **Combining Architectures and Tokenization**: Integration of Bi-LSTM, CNN, and Unigram tokenization led to the most effective model for this complex task.

## Conclusion
Our study not only improves upon existing baselines but also paves the way for future research in linguistic deception detection, especially in digital communication platforms.

## References
- Denis Peskov et al. 2020. *It Takes Two to Lie: One to Lie, and One to Listen*.
- V. Gupta et al. 2019. *Bag-of-Lies: A Multimodal Dataset for Deception Detection*.

---

For more detailed information, check out our full research paper.

---

*This project is a part of our ongoing efforts to enhance understanding and technology in the field of natural language processing and online communication.*

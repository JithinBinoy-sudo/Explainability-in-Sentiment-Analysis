# Explainability-in-Sentiment-Analysis

**ABOUT**

Sentiment analysis is a key natural language processing (NLP) task with applications across business, social sciences, public health, and politics. While transformer-based models such as BERT and its variants achieve state-of-the-art accuracy by capturing contextual relationships in text, their opaque decision-making raises concerns about trust, bias, and accountability. To address these challenges, this study proposes an interpretable sentiment analysis workflow that combines intrinsic explanations through attention visualization with post-hoc explanations from the model-agnostic LIME method and validates them using faithfulness testing.
Using a DistilBERT model fine-tuned for sentiment classification, we applied this approach to a sample of IMDb movie reviews. Attention heatmaps revealed the model’s internal focus on particular tokens, providing intuitive but incomplete explanations, while LIME offered clearer, word-level insights into feature importance. Faithfulness testing, conducted by removing top-ranked words, showed that the model’s predictions often remain unchanged, demonstrating that transformer-based sentiment classification relies on distributed contextual semantics rather than individual tokens. This highlights the model’s ability to integrate meaning across the sentence, rather than depending solely on single-word signals.
The results demonstrate that combining intrinsic and post-hoc methods produces richer and more trustworthy explanations than using either approach alone. This hybrid framework enhances transparency, supports accountability, and provides practical guidance for deploying sentiment analysis models in real-world applications. Overall, the study underscores the importance of context-aware interpretability techniques for building trustworthy and reliable NLP systems in domains where model decisions have significant consequences.

**HOW TO RUN IT**

1) Click on the link to Google Colab
2) Run the cells
3) Observe the output

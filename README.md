# <center> Attention Is All You Need

The paper "Attention Is All You Need," published in 2017, represents a crucial milestone in the evolution of artificial intelligence by introducing the Transformer model. Prior to this breakthrough, recurrent neural networks dominated natural language processing applications but faced challenges such as computational inefficiency and difficulty in handling lengthy sequences. The Transformer, on the other hand, introduced an attention mechanism that allowed the model to focus on specific parts of the input without relying on a fixed sequential structure. This revolutionary concept enabled significantly improved performance across a variety of NLP tasks such as machine translation, text summarization, and text generation.
 Furthermore, the Transformer set new standards in terms of scalability and parallel training. With its highly parallelizable architecture, it became possible to efficiently train models on massive datasets. This not only boosted model performance but also facilitated significant advancements in complex NLP tasks such as natural language understanding and coherent text generation.
Since then, the Transformer has been widely adopted and adapted in various artificial intelligence applications, establishing itself as a fundamental cornerstone for many subsequent developments. Its flexibility and effectiveness not only solidified the role of attention as an essential mechanism in machine learning models but also paved the way for new approaches and research in the field of AI.

references:<br>
    https://arxiv.org/abs/1706.03762 <br>
    https://www.deeplearningbook.com.br/



In this short guide, we will understand how the main factor that gave life to the transformative architecture works, which is the attention mechanism. We will implement it without using frameworks to make the understanding a little clearer.

- Our aim is to focus on the attention mechanism.
- I will implement the attention mechanism with just one head to facilitate understanding.
- We will not implement the back farward mechanism
- We will only make one pass (Farward)
- We will not use frameworks

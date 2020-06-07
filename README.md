# tl_dr_abstractive
## Project
We live in a world where advances in technology have increased the production of information. One concern is that massive amounts of information can be distracting and negatively impact productivity, decision-making and cognitive control (information overload), another concern might also be the ‘contamination’ of useful information with information that might not be totally accurate (information pollution).
In this pilot project, we will try a new approach to address the first concern, information overload, by leveraging the power of deep learning.

In a previous project, we already explored other approaches, such as extractive summarization. Extractive methods yield good accuracy overall but the inherent nature of the process of selecting a subset of the words or sentences in an existing document and assembling them together to make a summary makes the result less cohesive. The extracted sentences are basically concatenated to each other and there is no smooth transition between ideas or concepts in different sentences. 

To overcome this problem, one good approach to explore is abstractive text summarization which basically consists in generating summaries from texts from the main ideas. New sentences are generated from the original text and the sentences generated through abstractive summarization might not be in the original text, this makes for a more cohesive result which might look more like a human generated summary.

Transformers and Transfer Learning are still active areas of research so new theories, approaches and concepts are being developed on a regular basis. Consequently, this project builds on recent papers, articles as well as a few tutorials in order to construct the transformer and reuse the bert pre trained model for transfer learning.

Our approach is based on using the power of transfer learning along with the transformer architecture to create a model that will be able to ‘interpret’ meaning and generate summary sentences based on attention mechanisms (See Reference Section)

* [💻 Notebook](https://colab.research.google.com/drive/1oBbeQk0rLOhEaIcvQITXCfAR48zyJkN9?usp=sharing)
* [🎆 Slides](https://docs.google.com/presentation/d/1W0NHpYWegngecw-dgrn0ryVD6Suc9k-vscN4g4DUc0A/edit?usp=sharing)

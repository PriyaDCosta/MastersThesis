
### Abstract:

Text augmentation is the process of generating synthetic variations of existing text data to expand the dataset, improve model performance, and enhance generalization capabilities in Natural Language Processing (NLP) tasks. Manually creating augmented samples for a large dataset can be a time-consuming process. It requires human annotators to carefully devise and implement augmentation strategies, which can be labor-intensive and slow down the overall development process. Manual text augmentation also has limited scope for scalability.

Large Language Models (LLMs) powered by Artificial Intelligence (AI), such as OpenAI's GPT-3, have revolutionized NLP tasks and offer immense potential for text augmentation. Some other benefits of using LLMs for text augmentation include possibly reduced data bias (as LLMs are trained on a diverse range of sources compared to a single human annotator) and opportunities for iterative augmentation, which may not be as easy in manually augmented samples.

In summary, text augmentation using LLMs is a powerful and beneficial approach to enhance the performance and generalization capabilities of NLP models. There are many research works which study text augmentation, including surveys on different methods of text augmentation <sup>[1]</sup>, scenario specific text augmentation <sup>[2]</sup> and text augmentation for specific machine-learning methods <sup>[3] & [4]</sup>. 

### Existing Research:

There exists only one pre-print  <sup>[5]</sup> with a similar theme. This preprint focuses on using a popular LLM, i.e Chat GPT for augmenting text data for developing a text augmentation model called Chataug. It only studies text augmentation using a single LLM i.e Chat GPT-4,while there exist many other LLMs such as XLNet, DyloGPT, BlenderBot and Bard.

Secondly, Chataug, is tested using three types of data - Amazon product reviews (Customer reviews from 24 product categories), Symptoms dataset (Transcripts of audio data of common medical symptom descriptions over 8 hours) and PubMed20K dataset (Around 20,000 annotated scientific abstracts from the biomedical field). This data is primarily factual in nature, and is mostly related to the field of medicine. Non-factual text data - such as opinions, questions, creative writing and sarcastic comments are not considered in the training set. Similarly, it does not factor in the readability score of the data under consideration.

### Experimental Design :

We propose an experimental design that involves applying text augmentation methods (paraphrasing, back translation, synonym replacement, alternate spelling, and sequence alteration) using various LLMs (Chat GPT, XLNet, DyloGPT, BlenderBot, and Bard) across different data contexts such as  sarcastic data, data with varied emotions (customer reviews), data in the form of questions, opinion-based data and conversations data 

To measure semantic similarity, we will use text similarity measures like Cosine Similarity, Dice's Coefficient, Manhattan Distance, Jaccard Distance, and Overlap Coefficient. The outcomes will be analyzed to draw causal inferences addressing the research questions. The experiments and analysis will be conducted in Python.

*This approach is tentative*

### Research Questions:

#### RQ1:
How semantically similar is the original text and the augmented text generated by the LLMs? How do these vary by the context of the data , by the text augmentation methods used and by the LLM used?

#### RQ2: 
Are there any peculiarities noticed in any context or augmentation method? Are there any plausible reasons for the same? Does this make any LLMs more suited for any method or context of text augmentation?

### Novel Contributions:

Text augmentation using LLMs is highly dependent on the context of the data, and their efficacy must be studied with respect to the context. Text data is an important input to Computational Social Science, and we anticipate that future works in the space will be influenced by LLMs. Through this study, we aim to contribute meaningful insights around how LLMs can be used for text augmentation tasks, and whether certain LLMs must be specifically used for augmentation of certain types of text data / certain augmentation methods.

### Intended Publication:

We intend to publish our work in the [Journal of Big Data](https://journalofbigdata.springeropen.com/about?gclid=Cj0KCQjwtO-kBhDIARIsAL6LoreoKKime2jQw6ywZ1qPJRIJDfSbK3nXOORzRwvp9r5b1YhR3NvAHnMaAr4qEALw_wcB), which is focused on examining the challenges facing big data today and going forward.

### Citations:

[1] [P. Liu, X. Wang, C. Xiang and W. Meng, "A Survey of Text Data Augmentation," 2020 International Conference on Computer Communication and Network Security (CCNS), Xi'an, China, 2020, pp. 191-195, doi: 10.1109/CCNS50731.2020.00049.
](https://ieeexplore.ieee.org/document/9240734/)

[2] [Feng, Z., Zhou, H., Zhu, Z., & Mao, K. (2022). Tailored text augmentation for sentiment analysis. Expert Systems with Applications, 205, 117605.](https://www.sciencedirect.com/science/article/pii/S0957417422009162?ref=pdf_download&fr=RR-2&rr=7e01722bcc6b18d0)

[3] [Mosolova, A., Fomin, V., & Bondarenko, I. (2018). Text Augmentation for Neural Networks. AIST (Supplement), 2268, 104-109.
](https://ceur-ws.org/Vol-2268/paper11.pdf)

[4] [Shorten, C., Khoshgoftaar, T.M. & Furht, B. Text Data Augmentation for Deep Learning. J Big Data 8, 101 (2021).](https://link.springer.com/article/10.1186/s40537-021-00492-0)

[5] [Dai, Haixing & Liu, Zhengliang & Liao, Wenxiong & Huang, Xiaoke & Wu, Zihao & Zhao, Lin & Liu, Wei & Liu, Ninghao & Li, Sheng & Zhu, Dajiang & Cai, Hongmin & Li, Quanzheng & Liu, Tianming & Li, Xiang. (2023). ChatAug: Leveraging ChatGPT for Text Data Augmentation. 
](https://arxiv.org/pdf/2302.13007.pdf)https://arxiv.org/pdf/2302.13007.pdf

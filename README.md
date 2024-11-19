## GIL-IIMAS UNAM at SemEval-2024 Task 1: SAND Regression

This repository consists of the code created and used by the GIL-IIMAS UNAM team at the 2024 Semeval Competition for the North American Chapter of Computational Linguistics (NAACL 2024). The dataset is available in [SemEval Task 1](https://semantic-textual-relatedness.github.io/), once the paper is published a link will be posted here.


More about AnglE Embeddings can be found [here (Github)](https://github.com/SeanLee97/AnglE) and [here (arXiv)](https://arxiv.org/abs/2309.12871).

Regarding Sentence Transformers [here (Official Documentation)](https://sbert.net/) and [here (HuggingFace)](https://huggingface.co/sentence-transformers).


If you want to cite this paper please use the following:

@inproceedings{lopez-ponce-etal-2024-gil,
    title = "{GIL}-{IIMAS} {UNAM} at {S}em{E}val-2024 Task 1: {SAND}: An In Depth Analysis of Semantic Relatedness Using Regression and Similarity Characteristics",
    author = "Lopez-ponce, Francisco  and
      Cadena, {\'A}ngel  and
      Salas-jimenez, Karla  and
      Bel-enguix, Gemma  and
      Preciado-m{\'a}rquez, David",
    editor = {Ojha, Atul Kr.  and
      Do{\u{g}}ru{\"o}z, A. Seza  and
      Tayyar Madabushi, Harish  and
      Da San Martino, Giovanni  and
      Rosenthal, Sara  and
      Ros{\'a}, Aiala},
    booktitle = "Proceedings of the 18th International Workshop on Semantic Evaluation (SemEval-2024)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.semeval-1.186",
    doi = "10.18653/v1/2024.semeval-1.186",
    pages = "1288--1292",
    abstract = "The STR shared task aims at detecting the degree of semantic relatedness between sentence pairs in multiple languages. Semantic relatedness relies on elements such as topic similarity, point of view agreement, entailment, and even human intuition, making it a broader field than sentence similarity. The GIL-IIMAS UNAM team proposes a model based in the SAND characteristics composition (Sentence Transformers, AnglE Embeddings, N-grams, Sentence Length Difference coefficient) and classical regression algorithms. This model achieves a 0.83 Spearman Correlation score in the English test, and a 0.73 in the Spanish counterpart, finishing just above the SemEval baseline in English, and second place in Spanish.",
}

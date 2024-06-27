НЕЙРОСЕТЕВЫЕ МЕТОДЫ РАСПОЗНАВАНИЯ ФРАГМЕНТОВ БИБЛЕЙСКИХ ТЕКСТОВ В КОРПУСЕ НАУЧНО-ПОПУЛЯРНЫХ СТАТЕЙ 
МЕДИКО-БИОЛОГИЧЕСКОЙ НАПРАВЛЕННОСТИ ЖУРНАЛА The Economist ЗА 2000-2024 гг.

Презентация:
https://docs.google.com/presentation/d/1vA5Hn9FVDL_7mSOnBTIoRzf-LO4d5IP93HTcKVE8Tok/edit?usp=sharing

sentence_bert.pth:
https://drive.google.com/file/d/1iug7LGdzxhVTRk_Shdu4clHrzfWVfHMs/view?usp=drive_link 

sentence_bert_NO_SW.pth:
https://drive.google.com/file/d/1wJXLioB3RvGXgxo6cRXXHTHV0LEsZKE4/view?usp=drive_link 

econ_embeds.npy:
https://drive.google.com/file/d/1fjdlnKB2fOzV8okLM48go2H7SqbP6QBR/view?usp=drive_link 

bible_embeds.npy:
https://drive.google.com/file/d/1kyRWw5YrwdUQMwTIdzNk-KgVam9qfikC/view?usp=drive_link

with_SW_word_clf.pth:
https://drive.google.com/file/d/1FnaRHxCqJ_qUQn18QYulV-_Kq5crKOUM/view?usp=drive_link 


Models:
1. https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_core_sci_sm-0.5.4.tar.gz

@inproceedings{neumann-etal-2019-scispacy,
    title = "{S}cispa{C}y: {F}ast and {R}obust {M}odels for {B}iomedical {N}atural {L}anguage {P}rocessing",
    author = "Neumann, Mark  and
      King, Daniel  and
      Beltagy, Iz  and
      Ammar, Waleed",
    booktitle = "Proceedings of the 18th BioNLP Workshop and Shared Task",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W19-5034",
    doi = "10.18653/v1/W19-5034",
    pages = "319--327",
    eprint = {arXiv:1902.07669},
    abstract = "Despite recent advances in natural language processing, many statistical models for processing text perform extremely poorly under domain shift. Processing biomedical and clinical text is a critically important application area of natural language processing, for which there are few robust, practical, publicly available models. This paper describes scispaCy, a new Python library and models for practical biomedical/scientific text processing, which heavily leverages the spaCy library. We detail the performance of two packages of models released in scispaCy and demonstrate their robustness on several tasks and datasets. Models and code are available at https://allenai.github.io/scispacy/.",
}

2. DistilBertForSequenceClassification: https://github.com/huggingface/transformers?files=1
3. DistilBERT for MultiLabel Text Classification: https://colab.research.google.com/github/DhavalTaunk08/Transformers_scripts/blob/master/Transformers_multilabel_distilbert.ipynb
4. SentenceTransformer("distiluse-base-multilingual-cased-v2"): https://sbert.net/docs/pretrained_models.html.
   

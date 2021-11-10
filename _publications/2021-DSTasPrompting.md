---
title: "Dialogue State Tracking with a Language Model using Schema-Driven Prompting"
collection: publications
permalink: /publication/2021-DSTasPrompting
excerpt: 
date: 2021-09-01
venue: 'EMNLP'
paperurl:
citation:
---
*Chia-Hsuan Lee*, Hao Cheng, Mari Ostendorf [[PDF]](https://aclanthology.org/2021.emnlp-main.404.pdf)
<pre style="background-color: rgb(230,230,230);white-space: pre-wrap;">
<font size="1">
@inproceedings{lee-etal-2021-dialogue,
    title = "Dialogue State Tracking with a Language Model using Schema-Driven Prompting",
    author = "Lee, Chia-Hsuan  and
      Cheng, Hao  and
      Ostendorf, Mari",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.emnlp-main.404",
    pages = "4937--4949",
    abstract = "Task-oriented conversational systems often use dialogue state tracking to represent the user{'}s intentions, which involves filling in values of pre-defined slots. Many approaches have been proposed, often using task-specific architectures with special-purpose classifiers. Recently, good results have been obtained using more general architectures based on pretrained language models. Here, we introduce a new variation of the language modeling approach that uses schema-driven prompting to provide task-aware history encoding that is used for both categorical and non-categorical slots. We further improve performance by augmenting the prompting with schema descriptions, a naturally occurring source of in-domain knowledge. Our purely generative system achieves state-of-the-art performance on MultiWOZ 2.2 and achieves competitive performance on two other benchmarks: MultiWOZ 2.1 and M2M. The data and code will be available at https://github.com/chiahsuan156/DST-as-Prompting.",
}
</font>
</pre>

## Abstract
Task-oriented conversational systems often use dialogue state tracking to represent the user's intentions, which involves filling in values of pre-defined slots. Many approaches have been proposed, often using task-specific architectures with special-purpose classifiers. Recently, good results have been obtained using more general architectures based on pretrained language models. Here, we introduce a new variation of the language modeling approach that uses schema-driven prompting to provide task-aware history encoding that is used for both categorical and non-categorical slots. We further improve performance by augmenting the prompting with schema descriptions, a naturally occurring source of in-domain knowledge. Our purely generative system achieves state-of-the-art performance on MultiWOZ 2.2 and achieves competitive performance on two other benchmarks: MultiWOZ 2.1 and M2M.

---
title: "KaggleDBQA: Realistic Evaluation of Text-to-SQL Parsers"
collection: publications
permalink: /publication/2021-kaggledbqa
excerpt: 
date: 2021-08-01
venue: 'ACL'
paperurl:
citation:
---
*Chia-Hsuan Lee*, Oleksandr Polozov, Matthew Richardson [[PDF]](https://aclanthology.org/2021.acl-long.176.pdf) [[Corpus]](https://www.microsoft.com/en-us/research/publication/kaggledbqa-realistic-evaluation-of-text-to-sql-parsers/)
<pre style="background-color: rgb(230,230,230);white-space: pre-wrap;">
<font size="1">
@inproceedings{lee-etal-2021-kaggledbqa,
    title = "{K}aggle{DBQA}: Realistic Evaluation of Text-to-{SQL} Parsers",
    author = "Lee, Chia-Hsuan  and
      Polozov, Oleksandr  and
      Richardson, Matthew",
    booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.acl-long.176",
    doi = "10.18653/v1/2021.acl-long.176",
    pages = "2261--2273",
}
</font>
</pre>

## Abstract
The goal of database question answering is to enable natural language querying of real-life relational databases in diverse application domains. Recently, large-scale datasets such as Spider and WikiSQL facilitated novel modeling techniques for text-to-SQL parsing, improving zero-shot generalization to unseen databases. In this work, we examine the challenges that still prevent these techniques from practical deployment. First, we present KaggleDBQA, a new cross-domain evaluation dataset of real Web databases, with domain-specific data types, original formatting, and unrestricted questions. Second, we re-examine the choice of evaluation tasks for text-to-SQL parsers as applied in real-life settings. Finally, we augment our in-domain evaluation task with database documentation, a naturally occurring source of implicit domain knowledge. We show that KaggleDBQA presents a challenge to state-of-the-art zero-shot parsers but a more realistic evaluation setting and creative use of associated database documentation boosts their accuracy by over 13.2%, doubling their performance.

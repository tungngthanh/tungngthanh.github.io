---
title: "RST Parsing from Scratch"
collection: publications
permalink: /publication/2021-06-06-rst-parsing-scratch
excerpt: 'We introduce a novel top-down end-to-end formulation of document level discourse parsing in the Rhetorical Structure Theory (RST) framework. In this formulation, we consider discourse parsing as a sequence of splitting decisions at token boundaries and use a seq2seq network to model the splitting decisions. Our framework facilitates discourse parsing from scratch without requiring discourse segmentation as a prerequisite; rather, it yields segmentation as part of the parsing process. Our unified parsing model adopts a beam search to decode the best tree structure by searching through a space of high scoring trees. With extensive experiments on the standard RST discourse treebank, we demonstrate that our parser outperforms existing methods by a good margin in both end-to-end parsing and parsing with gold segmentation. More importantly, it does so without using any handcrafted features, making it faster and easily adaptable to new languages and domains.'
date: 2021-06-06
venue: 'Online'
paperurl: 'https://aclanthology.org/2021.naacl-main.128.pdf'
citation: '@inproceedings{nguyen-etal-2021-rst,
    title = &quot;{RST} Parsing from Scratch&quot;,
    author = &quot;Nguyen, Thanh-Tung  and
      Nguyen, Xuan-Phi  and
      Joty, Shafiq  and
      Li, Xiaoli&quot;,
    booktitle = &quot;Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies&quot;,
    month = jun,
    year = &quot;2021&quot;,
    address = &quot;Online&quot;,
    publisher = &quot;Association for Computational Linguistics&quot;,
    url = &quot;https://aclanthology.org/2021.naacl-main.128&quot;,
    doi = &quot;10.18653/v1/2021.naacl-main.128&quot;,
    pages = &quot;1613--1625&quot;,
    abstract = &quot;We introduce a novel top-down end-to-end formulation of document level discourse parsing in the Rhetorical Structure Theory (RST) framework. In this formulation, we consider discourse parsing as a sequence of splitting decisions at token boundaries and use a seq2seq network to model the splitting decisions. Our framework facilitates discourse parsing from scratch without requiring discourse segmentation as a prerequisite; rather, it yields segmentation as part of the parsing process. Our unified parsing model adopts a beam search to decode the best tree structure by searching through a space of high scoring trees. With extensive experiments on the standard RST discourse treebank, we demonstrate that our parser outperforms existing methods by a good margin in both end-to-end parsing and parsing with gold segmentation. More importantly, it does so without using any handcrafted features, making it faster and easily adaptable to new languages and domains.&quot;,
}'
---
We introduce a novel top-down end-to-end formulation of document level discourse parsing in the Rhetorical Structure Theory (RST) framework. In this formulation, we consider discourse parsing as a sequence of splitting decisions at token boundaries and use a seq2seq network to model the splitting decisions. Our framework facilitates discourse parsing from scratch without requiring discourse segmentation as a prerequisite; rather, it yields segmentation as part of the parsing process. Our unified parsing model adopts a beam search to decode the best tree structure by searching through a space of high scoring trees. With extensive experiments on the standard RST discourse treebank, we demonstrate that our parser outperforms existing methods by a good margin in both end-to-end parsing and parsing with gold segmentation. More importantly, it does so without using any handcrafted features, making it faster and easily adaptable to new languages and domains.

[Download paper here](https://aclanthology.org/2021.naacl-main.128.pdf)

Recommended citation: @inproceedings{nguyen-etal-2021-rst,
    title = "{RST} Parsing from Scratch",
    author = "Nguyen, Thanh-Tung  and
      Nguyen, Xuan-Phi  and
      Joty, Shafiq  and
      Li, Xiaoli",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.128",
    doi = "10.18653/v1/2021.naacl-main.128",
    pages = "1613--1625",
    abstract = "We introduce a novel top-down end-to-end formulation of document level discourse parsing in the Rhetorical Structure Theory (RST) framework. In this formulation, we consider discourse parsing as a sequence of splitting decisions at token boundaries and use a seq2seq network to model the splitting decisions. Our framework facilitates discourse parsing from scratch without requiring discourse segmentation as a prerequisite; rather, it yields segmentation as part of the parsing process. Our unified parsing model adopts a beam search to decode the best tree structure by searching through a space of high scoring trees. With extensive experiments on the standard RST discourse treebank, we demonstrate that our parser outperforms existing methods by a good margin in both end-to-end parsing and parsing with gold segmentation. More importantly, it does so without using any handcrafted features, making it faster and easily adaptable to new languages and domains.",
}
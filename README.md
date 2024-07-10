## A Dataset for Ambiguous Implicit Discourse Relations

This repository contains the ambiguous implicit discourse relations dataset for English. It includes paired examples with ambiguous implicit relations alongside two different preceding context sentences, each forcing either a causal or concessive reading.

## Dataset Contents

- **data/ambiguous_relations.csv**: The primary dataset file containing examples of ambiguous implicit discourse relations for English.
- **README.md**: A detailed description of the dataset, including the structure and annotations.

## Copyright and License

AmbiguousIDRs © 2023 by Ahmed Ruby, Sara Stymne and Christian Hardmeier is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Reference
If you use this resource, please consider citing:
```plaintext
@inproceedings{ruby-etal-2023-unpacking,
    title = "Unpacking Ambiguous Structure: A Dataset for Ambiguous Implicit Discourse Relations for {E}nglish and {E}gyptian {A}rabic",
    author = "Ruby, Ahmed  and
      Stymne, Sara  and
      Hardmeier, Christian",
    editor = "Strube, Michael  and
      Braud, Chloe  and
      Hardmeier, Christian  and
      Li, Junyi Jessy  and
      Loaiciga, Sharid  and
      Zeldes, Amir",
    booktitle = "Proceedings of the 4th Workshop on Computational Approaches to Discourse (CODI 2023)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.codi-1.16",
    doi = "10.18653/v1/2023.codi-1.16",
    pages = "126--144",
    abstract = "In this paper, we present principles of constructing and resolving ambiguity in implicit discourse relations. Following these principles, we created a dataset in both English and Egyptian Arabic that controls for semantic disambiguation, enabling the investigation of prosodic features in future work. In these datasets, examples are two-part sentences with an implicit discourse relation that can be ambiguously read as either causal or concessive, paired with two different preceding context sentences forcing either the causal or the concessive reading. We also validated both datasets by humans and language models (LMs) to study whether context can help humans or LMs resolve ambiguities of implicit relations and identify the intended relation. As a result, this task posed no difficulty for humans, but proved challenging for BERT/CamelBERT and ELECTRA/AraELECTRA models.",
}

# cimt-argument-mining-dataset

January 17, 2021 (corpus version 1.1)

About

This directory contains a dataset of public participation contributions coded with argument components. The dataset was used in the publication "Citizen Involvement in Urban Planning - How Can Municipalities Be Supported in Evaluating Public Participation Processes for Mobility Transitions?", published in the Proceedings of the 8th Workshop on Argument Mining by the Association for Computational Linguistics. The dataset is further described in the publication "A Corpus of German Citizen Contributions in Mobility Planning: Supporting Evaluation Through Multidimensional Classification", submitted to LREC 2022.

This work is based on research in the project CIMT/Partizipationsnutzen, which is funded by the Federal Ministry of Education and Research as part of its Social-Ecological Research funding priority, funding no. 01UU1904. (for more information, visit https://www.cimt-hhu.de/en/)
----------

Content

Each of the five folders contains the coded dataset and the corresponding terms of use. The dataset tsv-files contain one entry per sentence with the following information.
id: unique sentence id
document_id: document id
sentence_nr: sentence number in document
content: textual content of sentence
code: annotation label (see Argumentation Scheme)
title/text: denotes whether a sentence is taken from the title or the body text of a document
curated/single: denotes whether the sentence (i.e. document) was curated or coded by a single person (more information in the paper)
dataset: name of the dataset
url: original url of document (depending on the respective terms of use)

----------

Argumentation Scheme

Each sentence of the five datasets, which originate from German-language citizen participation procedures, is annotated according to the following argumentation scheme. More detailed information can be found in the paper.
mpos: sentence contains options for actions or decisions that occur in the discussion
premise: sentence contains reasons that attack or support a major position or another premise
mpos+premise: sentence contains both types of arguemtation components
non-arg: sentence contains no argumentation component (neither major position nor premise)

----------

Citation

If you use the dataset, please cite the following paper:

@inproceedings{romberg-conrad-2021-citizen,
    title = "Citizen Involvement in Urban Planning - How Can Municipalities Be Supported in Evaluating Public Participation Processes for Mobility Transitions?",
    author = "Romberg, Julia and Conrad, Stefan",
    booktitle = "Proceedings of the 8th Workshop on Argument Mining",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.argmining-1.9",
    pages = "89--99",
}

----------

License

The annotated data corpus is available under the Creative Commons CC BY-SA License (https://creativecommons.org/licenses/by-sa/4.0/).

----------

Contact Person

Julia Romberg, julia.romberg@hhu.de, https://www.cimt-hhu.de/en/team/romberg/

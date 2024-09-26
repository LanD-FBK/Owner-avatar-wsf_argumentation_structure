# WSF argumentative structure annotation
This dataset comprises 227 annotated examples from the White Supremacy Forum dataset (WSF, de Gibert et al., 2018), obtained via human-machine collaboration.

![alt text](https://github.com/helenabon/wsf_argumentation_structure/blob/main/example_wsf_arg.png)

## Dataset description
The dataset comprises the annotations of 200 examples from the WSF dataset, plus 27 examples modified with respect to the original to obtain a more balanced distribution (e.g. more examples where the weak part is not identical to the hateful part).

## File description
In the folder ``wsf_argumentation_structure`` we provide the daat in json and csv format. Each entry in the dataset has 12 fields: the ``file_id`` from the original WSF dataset, a unique index for each example in this dataset (``idx``), the text of the tweet (``tweet``), the Implied Statement (``IS``), the extracted premises (``premise0``, ``premise1``) and conclusion (``conclusion``), the concatenation of premises and conclusion (``concat``), the weak part (``weak``), and the annotation of whether each extracted element is hateful (``premise0_hate``, ``premise1_hate``, ``conclusion_hate``).

## Citation
Further details can be found in our paper (to appear in Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing):

Helena Bonaldi, Greta Damo, Nicolás Benjamín Ocampo, Elena Cabrio, Serena Villata and Marco Guerini. 2024. Is Safer Better? The Impact of Guardrails on the Argumentative Strength of LLMs in Hate Speech Countering. Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing. 2024.

```
@inproceedings{bonaldi-etal-2024-is,
    title = "Is Safer Better? The Impact of Guardrails on the Argumentative Strength of LLMs in Hate Speech Countering.",
    author = "Bonaldi, Helena  and
      Damo,Greta  and
      Ocampo, Nicolás Benjamín and
    Cabrio, Elena and
    Villata, Serena and
      Guerini, Marco",
    booktitle = "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2024",
    publisher = "Association for Computational Linguistics"
}

```

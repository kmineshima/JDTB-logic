# Japanese Discourse Relation Treebank focusing on Concessive Relations

A repositor for our LREC-Coling2024 paper "Annotation of Japanese Discourse Relations Focusing on Concessive Inferences."

## Data

The fields in the files `data/nagara.tsv`, `data/tsutsu.tsv`, `data/tokorode.tsv` are defined as follows:

- `kainoki-id`: ID in [the Kainoki Treebank](https://kainoki.github.io/)
- `first_half`: The first half of the sentence where the connective appears
- `connective`: The target connective
- `second_half`: The second half of the sentence where the connective appears
- `arg1`: The first discourse relation unit (the first argument that appears
in the clause that is syntactically bound to the connective)
- `arg2`: The second discourse relation unit (the second argument that appears
in the clause that is syntactically bound to the connective)
- `classification_label`: Discourse relation label
- For linguistic feature labels `ASP`, `NEG`, `MOD`, `CNJ`, `FOC`, `QUE`, `IMP`, see Section 4.1 of our paper.

## Citation
If you use this data in any published research, please cite the following:

- Ai Kubota, Takuma Sato, Takayuki Amamoto, Ryota Akiyoshi, and Koji Mineshima. 2024. [Annotation of Japanese Discourse Relations Focusing on Concessive Inferences](https://aclanthology.org/2024.lrec-main.109/). In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), pages 1215–1224.


```
@inproceedings{kubota-etal-2024-annotation-japanese,
    title = "Annotation of {J}apanese Discourse Relations Focusing on Concessive Inferences",
    author = "Kubota, Ai  and
      Sato, Takuma  and
      Amamoto, Takayuki  and
      Akiyoshi, Ryota  and
      Mineshima, Koji",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    year = "2024",
    address = "Torino, Italia",
    url = "https://aclanthology.org/2024.lrec-main.109",
    pages = "1215--1224"
}
```

## Contact

For questions, please contact minesima@abelard.flet.keio.ac.jp.

## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
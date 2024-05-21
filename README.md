# Metaphors in Online Religious Communication: A Detailed Dataset and Cross-Genre Metaphor Detection

This repository contains all data used in the paper [Metaphors in Online Religious Communication: A Detailed Dataset and Cross-Genre Metaphor Detection](https://aclanthology.org/2024.lrec-main.982/) presented at LREC-COLING 2024 in Turin.

If you want to use any of the data, please cite our paper:
```
@inproceedings{reimann-scheffler-2024-metaphors-online,
    title = "Metaphors in Online Religious Communication: A Detailed Dataset and Cross-Genre Metaphor Detection",
    author = "Reimann, Sebastian  and
      Scheffler, Tatjana",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.982",
    pages = "11236--11246",
    abstract = "We present the first dataset of fine-grained metaphor annotations for texts from online religious communication, where figurative language plays a particularly important role. In addition to binary labels, metaphors are annotated for deliberateness, that is, whether they are communicated explicitly as metaphors, and we provide indicators for such deliberate use. We further show that cross-genre transfer metaphor detection (from the widely used VUA corpus to our Reddit data) leads to a drop in performance due to the shift in topic and metaphors from source domains that did not occur in the training data. We solve this issue by adding a small amount of in-genre data in fine-tuning, leading to notable performance increases of more than 5 points in F1. Moreover, religious communication has the tendency for extended metaphorical comparisons, which are problematic for current metaphor detection systems. Adding in-genre data had slightly positive effects but we argue that to solve this, architectures that consider larger spans of context are necessary.",
}
```

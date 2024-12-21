# datasets

## Stack Exchange

All questions and their answers up to 14 August 2023, in the following categories:

* Law [[GitHub](https://github.com/ymoslem/datasets/blob/main/StackExchange/law-stackexchange-questions-answers.json.zip)] [[HuggingFace](https://huggingface.co/datasets/ymoslem/Law-StackExchange)]
* Medical Sciences [[GitHub](https://github.com/ymoslem/datasets/blob/main/StackExchange/medical-stackexchange-questions-answers.json)] [[HuggingFace](https://huggingface.co/datasets/ymoslem/MedicalSciences-StackExchange)]

The process uses the official Stack Exchange API and the code in this [notebook](https://github.com/ymoslem/datasets/blob/main/StackExchange/StackExchange.ipynb).

### License

The original questions and answers are licensed under CC-BY-SA and so is the dataset.

## Tatoeba Translations

This is the latest version of Tatoeba translations as of December 2024. The sentences are downloaded from the Tatoeba collection website. The dataset is processed through mapping `sentences.tar.bz2` using `sentences_base.tar.bz2` to find source (`sentence_src`) and target (`sentence_tgt`) sentences. While `lang_src` and `lang_tgt` columns follow the mapping provided by Tatoeba, the lang_pair column merely lists the two languages in the translation pair.

You can download the processing [notebook](https://github.com/ymoslem/datasets/blob/main/Tatoeba/Tatoeba-Translations.ipynb) and the [HuggingFace dataset](https://huggingface.co/datasets/ymoslem/Tatoeba-Translations).

### Statistics
The Tatoeba dataset includes 8,547,819 unique translation pairs in 414 languages, covering ~5,917 language pairs.


### License

The original Tatoeba collection is licensed under CC-BY 2.0 FR and so is the dataset.


# PET-iPET_BHTC
[PET and iPET](https://arxiv.org/pdf/2001.07676.pdf) procedure examination for the Basque language, using [BERTeus](https://huggingface.co/ixa-ehu/berteus-base-cased). as a pre-trained model and Basque Headlines Topic Classification (BHTC) as corpus. It uses the [GitHub](https://github.com/timoschick/pet) with the implementation of PET and iPET.

To be able to use the repository you should:

1. Uncomment the PET and iPET repo installation from the code.
2. Replaced the  **tasks.py** and **pvp.py** files with the ones in this repository.
3. Download the [BTHC corpus](https://hizkuntzateknologiak.elhuyar.eus/es/recursos) and put it inside a folder with the name **bhtc_corpus**.
4. Add the suffix **\_original** to the train.tsv and dev.tsv files.

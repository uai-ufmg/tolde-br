ToLDE-Br is a dataset derived from the [ToLD-Br](https://github.com/joaoaleite/ToLD-Br) database. In this version, 1000 sentences were filtered, comprising:

* 500 sentences classified as **toxic** by more than two evaluators.
* 500 sentences considered **non-toxic**.


In the set of toxic texts, a labeling process was carried out to identify which specific words (spans) contributed to their classification as toxic.

* **Annotators:** The database was labeled by 11 volunteers.
* **Consistency:** Each comment was examined by three different people.
* **Instructions:** The annotators were informed that the texts contained toxicity, but they did not know which of the toxicity subclasses the text had previously received. The instruction given was to identify the words that made the text perceived as offensive and containing hate speech.

The annotation process was inspired by the work of [HateXplain](https://github.com/hate-alert/HateXplain).

The ToLDE-Br dataset was developed as part of the master's thesis "O que torna uma frase tóxica? Uma análise crítica de modelos especialistas em detecção de toxicidade" authored by Gabriel Melo and  Flávio Figueiredo. The thesis was defended in March 2025 at the  Programa de Pós-Graduação em Ciência da Computação (PPGCC) of the Universidade Federal de Minas Gerais (UFMG)```
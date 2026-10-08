# NLP Coursework 1 – Statistical POS tagger / PCFG parser (Penn Treebank)

Run the notebooks in this order (Python 3; `pip install nltk pandas numpy matplotlib seaborn scikit-learn openpyxl tabulate`). All three are submitted already executed, with outputs saved.

| Task | File(s) | Contents |
|---|---|---|
| **Task 1 (40%)** | `Task1_POS_Tagger_and_PCFG_Model.ipynb` | Bigram HMM tagger and PCFG induced from the labelled NLTK Penn Treebank (train data), with validation |
| | `model/` | **PCFG parser data**: transition matrix and counts, emission probabilities, unknown-word model, tag counts, lexicalised PCFG (`pcfg_grammar_lexicalised.txt`, `pcfg_rules.csv`), CNF parser grammar, `pos_pcfg_model.pkl`, figures |
| **Task 2 (10%)** | `task2_150_tagged_sentences.xlsx` / `.csv` / `.txt` | **The 150 manually tagged sentences** (course tag set, plus the mapped PTB tags) |
| | `Task2_Tagged_Sentences.ipynb` | Tokenisation, tag validation, export, corpus profile |
| | `task2_tagging_sheet.xlsx` | The tagging sheet (read by the Task 2 notebook) |
| | `task2_raw_sentences.txt`, `task2_sources.txt` | Raw sentences and Daily Mirror article URLs |
| **Task 3 (50%)** | `Task3_Test_Results.ipynb` | **Test results**: per-sentence metrics, tagging P/R/F1 and κ, perplexities, PCFG parsing, clustering |
| | `results/` | `Task3_test_results.xlsx`, `per_sentence_results.csv`, overall and per-tag metrics, clusters, alignment by article, figures |
| **Report** | `NLP_CW1_Report.docx` | Method, model statistics, experimental results and discussion |

Note: the Kaggle `ptb.train.txt` is the unlabelled language-modelling version of the PTB. As instructed by the lecturer, the labelled NLTK Penn Treebank was used instead.

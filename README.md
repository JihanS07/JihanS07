# Jihaan Sakariya

Economics and Computer Science at the University of Rochester, class of 2028.

I like building things from first principles and measuring whether they actually work. Right now
that means LLM agents and how to evaluate them. 

## Projects

**[text_to_sql_agent](https://github.com/JihanS07/text_to_sql_agent)**
A tool-using LLM agent that answers plain-English questions about a SQL database, written on the
raw Claude API with no agent framework. Most of the repo is the evaluation harness: 500 questions
from the BIRD benchmark, an ablation where each configuration changes one thing, confidence
intervals and paired significance tests.
`Python` `LLM agents` `Evals` `SQLite` `Inspect AI`

**[retrieval-engine](https://github.com/JihanS07/retrieval-engine)**
A small search engine built from an inverted index up: TF-IDF, BM25, SVD semantic search and a
hybrid of the two.
`Python` `Information retrieval` `NumPy`

**[English-Premier-League-Predictor](https://github.com/JihanS07/English-Premier-League-Predictor)**
Match outcome prediction with 15+ engineered features (Elo ratings, form, rest days, head to head)
and logistic regression, random forest and gradient boosting models. On seasons the models never
saw, the best one gets 55% accuracy against 46% for always picking the home team. I got there after
finding and fixing two data leaks that had pushed the score close to 100%.
`Python` `scikit-learn` `Feature engineering`

**[mysh](https://github.com/JihanS07/mysh)**
A Unix shell in C built on `fork`, `execvp`, `pipe` and `dup2`. It runs pipelines of any length
with redirection and quotes, and CI runs its 27 tests on Linux and macOS, also under AddressSanitizer.
`C` `Systems`

## Elsewhere

This summer I worked as a data science research assistant in Copenhagen, building a pipeline that
merged GPS bus telemetry, transit schedules and census data across 1,274 census tracts.

Email: jihansakariya33@gmail.com

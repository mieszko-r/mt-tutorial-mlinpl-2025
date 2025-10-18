# MT tutorial - ML in PL conference 2025 

# Task 1
1. Download the dataset `allegro/ConECT` and work on its subset (e.g. 100 rows)
2. Translate the dataset from Czech to Polish with greedy decoding. Use model of your preference (e.g. `allegro/multislav-5lang`)

# Task 2
Evaluate translations with:
1. Lexical metrics: BLEU, chrF using `sacrebleu` library
2. Neural metrics: Comet (`Unbabel/wmt22-comet-da`), Comet QE (`Unbabel/wmt20-comet-qe-da`)

# Task 3
1. Generate translation hypotheses with epsilon sampling, N hypotheses for each source sentence (N=10, 50)

# Task 4
1. Decode candidates with MBR, use `mbrs` library
2. Evaluate translations with lexical and neural metrics

# Task 5
1. Decode candidates with QE reranking
2. Evaluate translations with lexical and neural metrics

# Task 6
1. Repeat task 4 or 5 for different N (e.g. 5, 10, 25, 50, 75)
2. Plot metrics as a function of N
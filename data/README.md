# Data download

## Prerequisites
```bash
pip install huggingface-hub
```

## open-llm-leaderboard
```bash
huggingface-cli download open-llm-leaderboard/results --repo-type dataset --local-dir-use-symlinks False --local-dir open-llm-leaderboard
```

## chatbot-arena-leaderboard
```bash
huggingface-cli download lmsys/chatbot-arena-leaderboard --repo-type space --local-dir-use-symlinks False --local-dir chatbot-arena-leaderboard
```

## alpaca-eval
```bash
wget https://github.com/tatsu-lab/alpaca_eval/raw/main/docs/data_AlpacaEval/alpaca_eval_gpt4_leaderboard.csv
```
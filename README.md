# FED

- This repo is for replication of FED paper
    - [Unsupervised Evaluation of Interactive Dialog with DialoGPT](https://arxiv.org/pdf/2006.12719.pdf)
- Codes for the FED score are sourced from the original repo
    -  [https://github.com/Shikib/fed](https://github.com/Shikib/fed)
- Please open the 'FED_replication.ipynb' file for a replication

## Original README.md
```
import fed

# Load model
model, tokenizer = fed.load_models("microsoft/DialoGPT-large")

# Evaluate
conversation = "<|endoftext|> Hi! <|endoftext|> Hello, how is your day? <|endoftext|> It's good. It's raining a bit, but I am enjoying a good book. How about you? <|endoftext|> It's good, I just got back from walking my dog What book did you read?"
scores = fed.evaluate(conversation,
                      model,
                      tokenizer)
```

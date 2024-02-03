# Spellchecker_LLM_02

This is a more finegrained prototype for an English spellchecker.
I finetuned Helsinki-NLP/opus-mt-en-ROMANCE on a dataset of 1772 messages in slang English, and manually translated into standard English.
The model can be found in Huggingface: https://huggingface.co/Lipas007/seq2seq-finetuned-slang-en


Limitations:
The dataset in question is limited, and it was a first approach. I am working on expanding and improving the dataset.
I am also working on applying this to other languages. 

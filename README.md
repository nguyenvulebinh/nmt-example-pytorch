## Neural Machine Translation using PyTorch

#### Dataset: using a dataset of English–French sentence pairs from the [Tatoeba Project](http://www.manythings.org/anki/)

#### For POC, the subset of the data selected consists of the English sentences that begin with “i am,” “he is,” “she is,” “they are,” “you are,” or “we are.”11

#### Source code contain:
- vocabulary.py Define class for keeping vocab data, sequence task data
- nmt_model.py Define seq2seq model, contain encoder and decoder class
- nmt_dataset.py Define instance dataset of pytorch, contain dataset split (for train, dev, test process), creating batch.
- train_and_valid.py process train and valid
- infer.py process infer model, run test process
- utils.py some utils function (acc, convert ids to sentences, config args for model,...)
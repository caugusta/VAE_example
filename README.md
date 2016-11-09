# VAE_example
Small test case for a neural variational document model

The training data is found in train_reviews_small.json
The vocabulary is in vocab_reviews_small.pkl

There are 100 reviews, and 1207 words in the vocabulary

File create_train_small.py creates the vocabulary.
minibatch_small.py has the NVDM model for a minibatch (from Sarath, with a few edits)
testchunk_small.py has the preprocessing for the dataset
train_model_CA_small.py does the actual model training

total_loss_Nov8_small.txt contains the average cost for the model, saved for each epoch, for each minibatch. Format: "epoch" + ' ' + "minibatch" + ' ' + "cost"


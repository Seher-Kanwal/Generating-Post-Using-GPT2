# Generating-Post-Using-GPT2
This app generate text about the given words.


# Working
Here we use transformer library.
We use pre trained model "GPT2LMHeadModel".
We import model along with tokenizer. We write a string convert it into some vector representation so that our model can understand it.
Than we pass this vector representation to our model to genrate text about it.
Our model return us with a text about the topic we provide it as an output.


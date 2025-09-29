#Custom Transformer Based Abstractive Summarization on News

- Created a Custom Transformer architecture for Abstractive Summarization on news using the hugging face dataset "nlplabtdtu/xlsum_en"
- Implemented both Byte Level BPE and pre-trained BART tokenizer, with trainable positional encodings in our project
- Implemented both Greedy and Beam Search approach for decoding
- Following is the measure of rogue scores calculated on the model
|   epoch |   rouge1 |    rouge2 |   rougeL |
|---------+----------+-----------+----------|
|       5 | 0.271596 | 0.0710721 | 0.211202 |
|      10 | 0.290982 | 0.0851596 | 0.226525 |
|      15 | 0.300244 | 0.0915641 | 0.234104 |
|      16 | 0.299387 | 0.0918897 | 0.232703 |
|      17 | 0.300989 | 0.0920619 | 0.234134 |
|      20 | 0.30415  | 0.0948534 | 0.236394 |
|      25 | 0.305513 | 0.0959938 | 0.237651 |

## Recurrent Neural Networks for Sarcasm Detection

Using `rmisra/news-headlines-dataset-for-sarcasm-detection` dataset.

### Observations

I found that the model performed _quite bad_. I believe this is because rnns generally have lower memory capabilities. Since the news headlines were quite long, when the model attempts to predict it word-by-word, the actual weight that word plays gets diluted and hence the model fails.

Upon doing some research, I found out that LSTMs solve this issue and that's what I'll be tackling next.
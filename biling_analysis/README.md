# Notebooks for model training and experiments

- To train both models use either Naive Transformer - Flickr30k-PT or Naive Transformer - Flickr30k-EN (it is assumed that the Flickr30k images are inside a Flickr30k/flickr30k-images folder)
- To produce the experiments and the plots, first run testModel-multilayer-V2_GITHUB-{PT|EN}.ipynb to create the plots like Figures 5 or 6 (with the attention heads distributions for each word), or the ones in Figures 7 and 8 with the means of attention heads, produce the jsons with the attention's matrix, means and stds and to produce the metrics obtained by each model
- Use one of the "analyze-word-heads-differences.ipynb"s notebooks to produce images such as in Figures 9 and 12, with the attention head's differences.
# Artist-Identification-CNN
For our CMPS 287 (Artificial Intelligence) project, we decided to tackle the issue of artist identification from paintings. Our aim is to accurately identify the artist of a painting using transfer learning by training different Convolutional Neural Networks (CNNs) with varying Residual Networks (ResNet). We have acquired our dataset from the Kaggle competition "best-artworks-of-all-time". Previously, most attempts at identifying artists from paintings used Linear SVMs, Multi-class SVMs, or Naive Bayes classifiers. Due to the high-dimensional nature of the paintings, numerous features had to be extracted in order to get meaningful results; however, this poses a problem since it is field specific. Such features included Line Features, TextonHistograms, Color Histograms, Geometric Probability Map, brush strokes, and Geometry Specific Histograms. Such attempts would explicitly learn distinctive features, which would perform on artists with varying painting styles, but our aim with the CNN was to make it learn features on its own instead.

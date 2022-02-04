# Hieroglyph-classifier


This is a deep learning approach to classify the glyphs into their corresponding Gardiner's codes using the Siamese network by performing a pairwise comparison with a labeled batch which got accuracy of 85%. However performing the comparison with 3 labeled arrays increases the accuracy to 87.5%. Finally adding a tri-gram language model increased the accuracy even more to 88.5%<br/>

This is the classification part of a hieroglyphic translator found [here](https://github.com/youthamj/HieroScan)! <br/>

## Dataset

The dataset used is The one used [here](https://github.com/morrisfranken/glyphreader)! <br/>
The context for the language model is found in Assets/EGYPT_DICTIONARY.csv.


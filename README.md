# BLP
Binary LegaL Product cLassifier

BLP is the repository of a research work that proposes to develop a binary classifier of products through the analysis of their images and texts, such as title, description, details and attributes.

Based on Artificial Intelligence techniques, more specifically Convolutional Neural Networks for images and LSTM for textual verifications, the application aims to improve the analysis and exclusion of products that are considered illegal for commercialization, with legal bases.


The repository is divided into 2 folders:
- *parsers:* where you can find scripts to retrieve and process data from different databases, such as scrapping results in dark web markets; and
- *experiments:* where you can se the Neural Network scripts to classify the data, as well as the scripts made to train and see how CNN and LSTM work

---
## Considerations

The images retrieved from the dark markets scrapping are not available, as they contain sensitive data from people, such as documents, licenses and passports. However, the scripts used to retrieve the files are available (folder *parsers*). The zip containing the scrapping is also publicly available.

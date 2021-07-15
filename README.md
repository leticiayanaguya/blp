# BL²P:: Binary LegaL Product cLassifier


BL²P is the repository of a research work that proposes to develop a binary classifier of products through the analysis of their images and texts, such as title, description, details and attributes.

Based on Artificial Intelligence techniques, more specifically Convolutional Neural Networks for images and LSTM for textual verifications, the application aims to improve the analysis and exclusion of products that are considered illegal for commercialization, with legal bases.


The repository is divided into 2 folders:
- *parsers:* where you can find scripts to retrieve and process data from different databases, such as scrapping results in dark web markets; and
- *experiments:* where you can se the Neural Network scripts to classify the data, as well as the scripts made to train and see how CNN and LSTM work

---
## Considerations

### About the scripts for data parsing and the data
The images retrieved from the dark markets scrapping are not available, as they contain sensitive data from people, such as documents, licenses and passports. However, the scripts used to retrieve the files are available (folder *parsers*). The zip containing the scrapping is also publicly available [here]

The scripts for data parsing are a little bit messy. I've changed the basis throughout development (such as removing prices and flag to check if the product had a image or not), as the idea for the networks matured. I'll try to improve these scripts in the future. They don't have good complexities, having a performance far from great.

The ideal solution would be to integrate scripts that clean the data, making only single images and texts be saved in the final folder/table.

This model utilizes the all-mpnet-base-v2 sentence transformer to compute the similarity score of an instagram caption and compare it to a previously created dataset of health claims. The goal is to find out if something in an instagram caption contains a possible health claims that might violates regulations.

steps:
1- read health claims dataset and create embeddings</br>
2- read an instagram caption, break it into separate sentences and create embeddings for each sentence
3- compare the distance between each sentence within the instagram caption, to each item in the dataset. 
4- report sentences within the instagram caption that exceeds a threshold score.

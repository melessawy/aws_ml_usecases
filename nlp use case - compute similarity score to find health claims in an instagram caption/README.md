This model utilizes the all-mpnet-base-v2 sentence transformer to compute the embeddings of an instagram caption and compare it to tje embeddings of a previously created dataset of health claims. </br></br>
The goal is to find out if something in an instagram caption contains a possible health claims that might violates regulations, using a computed similarity score.</br></br>

steps:</br></br>
1- read health claims dataset and create embeddings</br>
2- read an instagram caption, break it into separate sentences and create embeddings for each sentence.</br>
3- compare the distance between each sentence within the instagram caption, to each item in the dataset. </br>
4- report sentences within the instagram caption that exceeds a threshold score.</br>

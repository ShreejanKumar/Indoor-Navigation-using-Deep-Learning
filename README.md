# Indoor-Navigation-using-Deep-Learning

The project initially considered two approaches for assisting visually impaired individuals in navigation: explicit guidance through a 3D representation or autonomous determination of pathways based on obstacle locations. After surveying visually impaired participants, the latter approach was chosen. 
Using ViLT for visual question answering, we detected potential obstacles in images and segmented them with ClipSeg. Centroids of segmented objects were then computed to inform users of obstacle locations relative to their position. Depth estimation models helped prioritize obstacles, indicating the nearest and farthest objects. Finally, an LLM was used to generate instructions, which were delivered via text-to-speech based on survey insights.




![image](https://github.com/ShreejanKumar/Indoor-Navigation-using-Deep-Learning/assets/99002627/1bbf5766-86ec-424c-ac05-0b54905d0cac)


Dataset Link - https://www.kaggle.com/datasets/dotran0101/daquar <br>
ViLT - https://arxiv.org/abs/2102.03334 <br>
ClipSeg - https://huggingface.co/docs/transformers/en/model_doc/clipseg <br>
GLPN - https://huggingface.co/docs/transformers/main/en/model_doc/glpn <br>

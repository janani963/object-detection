# object-detection

object detection is used to detect the things in the image

**NMS**
Non-Maximun Suppression- it is a technique to select the one entity (bounding boxes) out of many overlapping entities.

1. Installed the Tensorflow 
2. imported the coco.names 
3. imported the image using opencv
4. loaded the weights and models

so by ensemble technique we are combining the two models where by updating the weights of the model 
    
**Advantage:**
    1. Requires very little data to train the combined model because most learning is derived from the combined models.
    2.It takes less time to build a combined model compared to building a new model.
    3.Requires less computing resources when models are combined.
    4.New combined models have higher accuracy and higher capabilities than those combined to obtain the new model.
   
**Disadvantage:**
    1. average pooling assumes a single mode with a single centroid, if your distribution has more than one mode or you have outliers, your average pooling won’t be accurate.
   
          
                         
                         

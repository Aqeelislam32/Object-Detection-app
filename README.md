 

 

### **Object Detector: Real-Time Object Detection Using Faster R-CNN**

This Streamlit application allows users to upload an image and performs real-time object detection using a pre-trained Faster R-CNN model with a ResNet-50 backbone. The app identifies objects in the image, draws bounding boxes around them, and displays the predicted labels with their corresponding probabilities.

---

**Key Features:**

- **Pre-trained Model:** The application uses the Faster R-CNN model with a ResNet-50 backbone, fine-tuned on the COCO dataset. The model is loaded with pre-trained weights (`FasterRCNN_ResNet50_FPN_V2_Weights.DEFAULT`) and set to evaluation mode for predictions.

- **Image Upload:** Users can upload images in PNG, JPG, or JPEG formats. The app processes the uploaded image and prepares it for object detection.

- **Object Detection:** The app applies the Faster R-CNN model to the uploaded image, generating predictions that include bounding boxes, labels, and confidence scores.

- **Bounding Boxes:** The app draws bounding boxes around detected objects in the image. It highlights "person" objects in red and other objects in green.

- **Predicted Labels and Probabilities:** The app displays the predicted object labels and their corresponding probabilities, excluding the bounding box coordinates.

- **Visualization:** The processed image with bounding boxes is displayed using Matplotlib within the Streamlit interface.

---

This application is suitable for users interested in applying state-of-the-art computer vision techniques to analyze images and detect objects in real time.

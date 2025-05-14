# Image_Recognition_Model

🔹 Problem Statement

In today’s digital world, classifying and recognizing objects in images quickly and accurately is a crucial task for applications like

security systems, medical imaging, and e-commerce. However, building high-accuracy models from scratch can be computationally expensive

and time-consuming.

🔹 Proposed System/Solution

To address this issue, we developed a lightweight image recognition system using a pre-trained MobileNetV2 model, which provides accurate

predictions with lower computational overhead. The model is deployed as a web app where users can upload images and get predictions

instantly.

🔹 System Development Approach (Technology Used)

Frontend & Backend: Flask (Python Web Framework)

Model: TensorFlow Keras (MobileNetV2 pre-trained on ImageNet)

Image Handling: NumPy, PIL (Python Imaging Library)

Hosting/Deployment: Localhost (can be extended to cloud deployment)

🔹 Algorithm & Deployment

Image uploaded via web interface.

Preprocessing: Resize and normalize the image.

Model loads MobileNetV2 with ImageNet weights.

Prediction: Output top 3 labels with confidence scores.

Deployment: Flask app runs locally to accept and display results.

🔹 Conclusion

This system demonstrates how pre-trained models can be effectively reused for real-world applications without the need for large 

training datasets or expensive hardware. The lightweight MobileNetV2 model ensures fast and accurate recognition suitable for 

deployment on limited-resource environments.

🔹 Future Scope

Deploy the app on cloud platforms like Heroku or AWS.

Add more user interface features like drag-and-drop, image gallery, or prediction history.

Extend model capabilities to handle custom training for domain-specific classification.

🔹 References

TensorFlow MobileNetV2 Documentation

Flask Web Framework Official Docs

ImageNet Dataset

NumPy & PIL Python Libraries

